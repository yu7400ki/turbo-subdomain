FROM node:20-slim
ENV PNPM_HOME="/usr/local/pnpm-global/bin"
ENV PATH="$PNPM_HOME:$PATH"
RUN corepack enable
RUN userdel -r node
