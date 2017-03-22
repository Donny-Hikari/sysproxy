# Introduction / 介绍
This is a script to enable/disable system-wide proxy in ubuntu.
一个开启/关闭系统代理的脚本。试验环境基于Ubuntu。

# Install / 安装
Put this script somewhere handy so that you can execute it easily.  
把这个脚本放在你随时都能够得着的地方～
Don't forget to give it +x permission.  
记得给它+x的运行权限。
```bash
sudo ug+x sysproxy
```

# Configuration / 设定
Change the following variable to the proxy port you want.  
把下面的变量值改为你所需要设定的端口。
```bash
PROXY_PORT=1081 # Proxy http,https,ftp,socks to the same port.
```

# Usage / 用法
+ To enable proxy / 启用代理:  
```bash
sysproxy enable
```
+ To disable proxy / 禁用代理:  
```bash
sysproxy disable
```
+ To check proxy status / 检查代理状态:  
```bash
sysproxy status/state
```
+ -e option / 使用系统环境选项:  
  Optional. Change system environment directly. Notice that in this way a reboot or logout is required.  
  可选。直接改变系统环境变量。注意这种方式将在重启后生效。
```bash
sysproxy enable/disable/status/state -e/envir/environment
```

# Author / 作者
[![Donny](https://avatars.githubusercontent.com/u/22200374?v=3&s=150 "Donny")](https://github.com/Donny-Hikari)

