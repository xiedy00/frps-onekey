Frp-onekey-Install-Shell
===========
Frp 是一个高性能的反向代理应用，可以帮助您轻松地进行内网穿透，对外网提供服务，支持 tcp, http, https 等协议类型，并且 web 服务支持根据域名进行路由转发。


* 详情：fatedier (https://github.com/fatedier/frp）
* 此脚本原作者：clangcn （https://github.com/clangcn/onekey-install-shell）

这个是frps一键服务端配置脚本，已更新最新版本：0.23.1
## Server
------

### Install（安装）

```Bash
wget https://raw.githubusercontent.com/jacko1045/frp-onekey/master/install-frps.sh -O ./install-frps.sh;chmod +x install-frps.sh
./install-frps.sh install
```

### Uninstall（卸载）
```Bash
./install-frps.sh uninstall
```
### Update（更新）
```Bash
./install-frps.sh update
```
### Server management（服务管理器）
```Bash
 Usage: /etc/init.d/frps {start|stop|restart|status|config|version}
```