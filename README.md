# 概述

南阳理工学院 深澜校园网登录 python 脚本，可用于任何支持 python 的设备的网络命令行登录或命令行登录。

# 原项目介绍

[深澜校园网登录的分析与 python 实现-北京理工大学版 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/122556315)

# 文件说明

|       文件       |                  说明                  |
| :--------------: | :------------------------------------: |
|  BitSrunLogin/   |             深澜登录函数包             |
|     demo.py      |              登录示例脚本              |
| always_online.py | 在线监测脚本，如果监测到掉线则自动重连 |

always_online.py 可采用 `nohup`命令挂在后台：

```bash
nohup python always_online.py &
```
