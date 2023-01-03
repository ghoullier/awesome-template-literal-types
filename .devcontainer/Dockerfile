ARG VARIANT=18-bullseye
FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:0-${VARIANT}

RUN corepack enable
RUN corepack prepare pnpm@latest --activate