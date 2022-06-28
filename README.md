# ws scrcpy 的 Docker 镜像

用来在浏览器中控制 Android 设备。

## 使用

```
docker run --name ws-scrcpy -d -p 8000:8000 scavin/ws-scrcpy
docker exec ws-scrcpy adb connect android.device.ip:5555

```

注意修改 android.device.ip 为 Android 设备 IP 地址。

## 参考链接

* https://github.com/Genymobile/scrcpy
* https://github.com/NetrisTV/ws-scrcpy
* https://meta.appinn.net/t/topic/33828
