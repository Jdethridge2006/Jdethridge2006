- 👋 Hi, I’m @Jdethridge2006
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Jdethridge2006/Jdethridge2006 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
This is my xmrig setup
{
    "api": {
        "id": null,
        "worker-id": null
    },
    "http": {
        "enabled": true,
        "host": "0.0.0.0",
        "port": 4444,
        "access-token": null,
        "restricted": true
    },
    "autosave": true,
    "background": false,
    "colors": true,
    "title": true,
    "randomx": {
        "init": -1,
        "init-avx2": -1,
        "mode": "fast",
        "1gb-pages": false,
        "rdmsr": false,
        "wrmsr": true,
        "cache_qos": false,
        "numa": true,
        "scratchpad_prefetch_mode": 2
    },
    "cpu": {
        "enabled": true,
        "huge-pages": true,
        "huge-pages-jit": true,
        "hw-aes": null,
        "priority": 2,
        "memory-pool": true,
        "yield": false,
        "asm": "intel",
        "argon2-impl": null,
        "astrobwt-max-size": 1200,
        "astrobwt-avx2": true,
        "argon2": [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11],
        "astrobwt": [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11],
        "astrobwt/v2": [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11],
        "cn": [
            [1, 0],
            [1, 2],
            [1, 4],
            [1, 6],
            [1, 8],
            [1, 10]
        ],
        "cn-heavy": [
            [1, 0],
            [1, 2],
            [1, 4]
        ],
        "cn-lite": [
            [1, 0],
            [1, 1],
            [1, 2],
            [1, 3],
            [1, 4],
            [1, 5],
            [1, 6],
            [1, 7],
            [1, 8],
            [1, 9],
            [1, 10],
            [1, 11]
        ],
        "cn-pico": [
            [2, 0],
            [2, 1],
            [2, 2],
            [2, 3],
            [2, 4],
            [2, 5],
            [2, 6],
            [2, 7],
            [2, 8],
            [2, 9],
            [2, 10],
            [2, 11]
        ],
        "cn/upx2": [
            [2, 0],
            [2, 1],
            [2, 2],
            [2, 3],
            [2, 4],
            [2, 5],
            [2, 6],
            [2, 7],
            [2, 8],
            [2, 9],
            [2, 10],
            [2, 11]
        ],
        "ghostrider": [
            [8, 0],
            [8, 2],
            [8, 4],
            [8, 6],
            [8, 8],
            [8, 10]
        ],
        "rx": [-1, -1, -1, -1, -1, -1],
        "rx/wow": [-1, -1, -1, -1, -1, -1],
        "cn-lite/0": false,
        "cn/0": false,
        "rx/arq": false,
        "rx/keva": false
    },
    "opencl": {
        "enabled": false,
        "cache": true,
        "loader": null,
        "platform": "AMD",
        "adl": true,
        "cn-lite/0": false,
        "cn/0": false
    },
    "cuda": {
        "enabled": false,
        "loader": null,
        "nvml": true,
        "cn-lite/0": false,
        "cn/0": false
    },
    "log-file": null,
    "donate-level": 1,
    "donate-over-proxy": 0,
    "pools": [
        {
            "algo": "rx",
            "coin": null,
            "url": "rx-us.unmineable.com:3333",
            "user": "ltc:MSETLgsyZiQaNzmcgeKYNegMSGfwGEphGY.ltcACER1#md55-n1a5",
            "pass": "x",
            "rig-id": null,
            "nicehash": false,
            "keepalive": true,
            "enabled": true,
            "tls": false,
            "wss": false,
            "tls-fingerprint": null,
            "daemon": false,
            "socks5": null,
            "self-select": null,
            "submit-to-origin": false
        }
    ],
    "retries": 1,
    "retry-pause": 1,
    "print-time": 3600,
    "health-print-time": 6000,
    "dmi": true,
    "syslog": false,
    "tls": {
        "enabled": false,
        "protocols": null,
        "cert": null,
        "cert_key": null,
        "ciphers": null,
        "ciphersuites": null,
        "dhparam": null
    },
    "dns": {
        "ipv6": false,
        "ttl": 30
    },
    "user-agent": null,
    "verbose": 0,
    "watch": true,
    "pause-on-battery": false,
    "pause-on-active": false
}
this is my phenix miner for0 etc with radeon 6500 (not recomended 14 hash is all) and 5500 recomended 25 to 27 hash
# PhoenixMiner configuration file
-pool etchash-us.unmineable.com:3333
-pool2 etchash-us.unmineable.com:13333
-wal ltc:MSETLgsyZiQaNzmcgeKYNegMSGfwGEphGY.ltcACER3#md55-n1a5
-gpus 1,5
-cdmport 14444
-clkernel 0,0
-mi 14,14
-gt 0,0
-eres 40,40
-straps 0,5
-nvmem 0,0
-vmr 100,100
-rxboost 100,100
-prate .09
nvidia 1650 super kawpow 14 to 16 hash
{
    "api": {
        "id": null,
        "worker-id": null
    },
    "http": {
        "enabled": true,
        "host": "0.0.0.0",
        "port": 12222,
        "access-token": null,
        "restricted": true
    },
    "autosave": true,
    "background": false,
    "colors": true,
    "title": true,
    "randomx": {
        "init": -1,
        "init-avx2": -1,
        "mode": "fast",
        "1gb-pages": false,
        "rdmsr": true,
        "wrmsr": true,
        "cache_qos": true,
        "numa": true,
        "scratchpad_prefetch_mode": 2
    },
    "cpu": {
        "enabled": false,
        "huge-pages": true,
        "huge-pages-jit": true,
        "hw-aes": null,
        "priority": null,
        "memory-pool": -1,
        "yield": true,
        "asm": true,
        "argon2-impl": null,
        "astrobwt-max-size": 550,
        "astrobwt-avx2": false,
        "argon2": [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11],
        "astrobwt": [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11],
        "astrobwt/v2": [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11],
        "rx": [0, 2, 4, 6, 8, 10],
        "rx/wow": [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11],
        "cn-lite/0": false,
        "cn/0": false,
        "rx/arq": "rx/wow",
        "rx/keva": "rx/wow"
    },
    "opencl": {
        "enabled": false,
        "cache": true,
        "loader": null,
        "platform": "AMD",
        "adl": true,
        "cn-lite/0": false,
        "cn/0": false
    },
    "cuda": {
        "enabled": true,
	"mode": "fast",
	"max-thread-hint": "hint",
	"asm": true,
        "loader": null,
        "nvml": true,
        "kawpow": [
            {
                "index": 1,
                "threads": 256,
                "blocks": 40960,
                "bfactor": 6,
                "bsleep": 25,
                "affinity": -1
            }
        ],
        "cn-lite/0": false,
        "cn/0": false
    },
    "log-file": null,
    "donate-level": 1,
    "donate-over-proxy": 1,
    "pools": [
        {
            "algo": "kawpow",
            "coin": "ltc",
            "url": "kp-us.unmineable.com:3333",
            "user": "ltc:MSETLgsyZiQaNzmcgeKYNegMSGfwGEphGY.ltcACER2#md55-n1a5",
            "pass": "x",
            "rig-id": null,
            "nicehash": false,
            "keepalive": true,
            "enabled": true,
            "tls": false,
            "wss": false,
            "tls-fingerprint": null,
            "daemon": false,
            "socks5": null,
            "self-select": null,
            "submit-to-origin": false
        }
    ],
    "retries": 1,
    "retry-pause": 1,
    "print-time": 6000,
    "health-print-time": 6000,
    "dmi": true,
    "syslog": false,
    "tls": {
        "enabled": false,
        "protocols": null,
        "cert": null,
        "cert_key": null,
        "ciphers": null,
        "ciphersuites": null,
        "dhparam": null
    },
    "dns": {
        "ipv6": false,
        "ttl": 30
    },
    "user-agent": null,
    "verbose": 0,
    "watch": true,
    "pause-on-battery": false,
    "pause-on-active": false
}
nvidia 3060 not bad overclocked 37 to 39 hash
# PhoenixMiner configuration file
-pool ethash-us.unmineable.com:3333
-pool2 ethash-us.unmineable.com:13333
-wal ltc:MSETLgsyZiQaNzmcgeKYNegMSGfwGEphGY.ltcACER3#md55-n1a5
-gpus 4
-cdmport 8888
-clkernel 2
-mi 14
-gt 0
-eres 100
-straps 6
-nvmem 2
-vmr 100
-rxboost 100
-prate .09
if these setups help you please run it alittle for a tip THANKS!
ltc cash out every day
