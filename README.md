# shadowsocks-chrome-utorrent-ipv4--ipv6
## shadowsocks config:
'''json
{
    "server":"::",
    "port_password":
    {
        "8888": "pwd",
        "8889": "pwd"
    },
    "local_address": "127.0.0.1",
    "local_port":1080,
    "timeout":300,
    "method":"aes-256-cfb",
    "prefer_ipv6": true
}
'''
## chrome config:
Proxy SwitchyOmega use localhost for proxy
## utorrent config:
Use localhost for proxy