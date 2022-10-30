
## Mac 客户端
- 推荐 [V2rayU](https://github.com/yanue/V2rayU/releases)

## Terminal 代理
``` bash
# .config/fish/config.fish
alias all_proxy='export http_proxy=http://127.0.0.1:1087;export https_proxy=http://127.0.0.1:1087;export ALL_PROXY=socks5://127.0.0.1:1080'
```

## git ssh 代理
```
# .ssh/config
Host github.com
    User git
    ProxyCommand nc -v -x 127.0.0.1:1080 %h %p
```
<!--more-->