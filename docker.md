# 安装docker和Docker Compose

1. 运行以下命令以安装 Docker 的依赖项：
  sudo apt-get update
  sudo apt-get install apt-transport-https ca-certificates curl software-properties-common

2. 

  2.添加 Docker 的官方 GPG 密钥：
  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o
  /usr/share/keyrings/docker-archive-keyring.gpg

  

  3.添加 Docker 的稳定存储库：
  echo "deb [arch=amd64 signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://downl
  oad.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee
  /etc/apt/sources.list.d/docker.list > /dev/null

  

  4.更新软件包列表并安装 Docker
  sudo apt-get update
  sudo apt-get install docker-ce docker-ce-cli containerd.io

  

  5.验证 Docker 是否已成功安装：
  sudo docker run hello-world





安装Docker Compose：

1.使用以下命令下载最新版本的Docker Compose二进制文件：
sudo curl -L "https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

2.授予执行权限：
sudo chmod +x /usr/local/bin/docker-compose

3.创建一个符号链接：
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose

4.验证Docker Compose是否成功安装：
docker-compose --version