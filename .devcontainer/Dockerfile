FROM ghcr.io/tom-tan/ldc:latest AS digger

RUN git clone --recursive https://github.com/CyberShadow/Digger.git
WORKDIR Digger
RUN rdmd --build-only digger && strip digger && cp digger /usr/bin


FROM mcr.microsoft.com/vscode/devcontainers/cpp:0-ubuntu

COPY --from=digger /usr/bin/digger /usr/bin/digger

RUN mkdir -p /workspaces/digger && chown -R vscode:vscode /workspaces/digger

ENV PATH=/workspaces/digger/result/bin:${PATH}
