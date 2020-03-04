FROM debian:latest
LABEL maintainer="Bryan Flood <bryanfloodcontact@gmail.com>"
LABEL description="🐳 Clang Latest Stable Docker Debian Environment"
LABEL url="https://github.com/KnowledgePending/Clang-Docker"
RUN apt-get update && \
    apt-get install -y lsb-release wget gnupg2 software-properties-common && \
    apt-get clean all && \
    wget https://apt.llvm.org/llvm.sh && \
    chmod +x llvm.sh && \
    ./llvm.sh