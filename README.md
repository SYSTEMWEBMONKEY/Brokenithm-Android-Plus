## Brokenithm-Android

A version of Brokenithm, inspired by the [Brokenithm-iOS](https://github.com/esterTion/Brokenithm-iOS) project.
Supports UDP and TCP connection to host, UDP for Wireless connection and TCP for `adb reverse` port forward (over USB for lower latency?).

The Windows server is in [another repository](https://github.com/tindy2013/Brokenithm-Android-Server).

这个项目基于Tindy2013的Brokenithm-Android进行改写，添加了IPV6支持，可搭配公网IPV6实现便携式CHUNITHM
仓库根目录的624_TCP.py可以把52469端口上的IPv6 TCP请求以IPv4方式转发到本地的52468端口的Brokenithm-Server上，可搭配IPv6公网实现低延迟远程游玩
