FROM nextcloud:latest

# 安装 bz2 扩展
RUN apt-get update && \
    apt-get install -y libbz2-dev && \
    docker-php-ext-install bz2
