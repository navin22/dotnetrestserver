  
FROM mcr.microsoft.com/vscode/devcontainers/universal:linux

# Avoid warnings by switching to noninteractive
ENV DEBIAN_FRONTEND=noninteractive

# Configure apt and install packages
RUN sudo apt-get install mysql-server

# Switch back to dialog for any ad-hoc use of apt-get
ENV DEBIAN_FRONTEND=dialog