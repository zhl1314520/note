**检查是否安装**

```
wsl --status
```

**下载**

```
wsl --install -d Ubuntu-24.04
```

**查看当前Linux发行版**

```
wsl -l -v
```

**账号、密码**

```
administrator
abcd123456
```

**安装 nvm**

```
sudo apt update
sudo apt install -y curl
```

**安装 nvm 官方安装脚本**

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.7/install.sh | bash
```

**加载 nvm**

```
source ~/.bashrc
```

**安装 node22**

```
nvm install 22
```

**验证安装**

```
node -v
npm -v
nvm ls
```