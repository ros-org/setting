##### Linux下node环境配置

```bash
# 检查架构
uname -m

# 进入/usr/local
cd /usr/local

# 下载 （arm64与x64）
# arm64
sudo wget https://nodejs.org/dist/v16.18.1/node-v16.18.1-linux-arm64.tar.xz
# x64
sudo wget https://nodejs.org/dist/v16.18.1/node-v16.18.1-linux-x64.tar.xz

# 解压
sudo tar xf node-v16.18.1-linux-arm64.tar.xz

# 建立软连接
sudo ln -s /usr/local/node-v16.18.1-linux-arm64/bin/node /usr/local/bin/
sudo ln -s /usr/local/node-v16.18.1-linux-arm64/bin/npm /usr/local/bin/

# 检查
node -v
npm -v
```



