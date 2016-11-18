# openwrt-kcptun

Binary in Release for download.

More details please refer to https://github.com/xtaci/kcptun

luci-app-kcptun please refer to https://github.com/kuoruan/luci-app-kcptun

Sample config file for MT7620 router with 64M memory. Speed could boost up to 3-4Mbps while original at 0.5-1Mbps.

    "localaddr": ":1234",
    "remoteaddr": "xxx.xxx.xxx.xxx:1234",
    "key": "yourkeys",
    "crypt": "salsa20",
    "mode": "fast",
    "conn": 1,
    "autoexpire": 300,
    "mtu": 1350,
    "sndwnd": 128,
    "rcvwnd": 128,
    "datashard": 10,
    "parityshard": 3,
    "dscp": 46,
    "nocomp": true,
    "acknodelay": false,
    "nodelay": 0,
    "interval": 20,
    "resend": 2,
    "nc": 1,
    "sockbuf": 4194304,
    "keepalive": 10
