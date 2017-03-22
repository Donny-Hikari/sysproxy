# Introduction
This is a script for enable/disable proxy system-wide in ubuntu.

# Install
Put this script somewhere handy so that you can execute it easily.  
Don't forget to give it +x permission.  
```bash
sudo ug+x sysproxy
```

# Configuration
Change the following variable to the proxy port you want.  
```bash
PROXY_PORT=1081 # Proxy http,https,ftp,socks to the same port.
```

# Usage
+ To enable proxy:  
```bash
sysproxy enable
```
+ To disable proxy:  
```bash
sysproxy disable
```
+ To check proxy status:  
```bash
sysproxy status/state
```
+ -e option:  
  Optional. Change system environment directly. Notice that in this way a reboot or logout is required.
```bash
sysproxy enable/disable/status/state -e/envir/environment
```

# Author
[![Donny](https://avatars.githubusercontent.com/u/22200374?v=3&s=150 "Donny")](https://github.com/Donny-Hikari)

