# tuic script

Tuic V4 + V5 协议一键部署脚本

## 一键脚本地址
Test:

```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/Felix-zf/Tuic-Scripts/main/tuic.sh && bash tuic.sh
```
📦 Modify:

To install tuic-server using the tuic-installer, run the following command:
```
bash <(curl -fsSL https://raw.githubusercontent.com/felix-zf/Tuic-Scripts/main/tuic-installer.sh)
```
💬 Usage:

Once you run the script, you'll be greeted with options if tuic-server is detected:
```
Reinstall: Start fresh by removing the current version.
Modify: Change your port or password settings on-the-fly.
Uninstall: Cleans up tuic-server and its configurations.
```

## 客户端配置
***Windows (V2rayN)***
- 首先在此：https://github.com/EAimTY/tuic/releases/tag/tuic-client-1.0.0 下载客户端。（Windows 的一般下载tuic-client-1.0.0-x86_64-pc-windows-msvc.exe），解压至v2rayN的bin/tuic目录中，并重命名为tuic-client.exe
- 依次点击“服务器”→“添加自定义服务器”，输入别名、导入json文件，Core类型选择 tuic，端口输入 6080

***Hiddify***
- 查看配置文件.yaml
- 导入客户端配置文件

## 感谢
- eaimty的blog：https://www.eaimty.com
- Tuic协议：https://github.com/EAimTY/tuic
- deathline94的pj: https://github.com/deathline94/tuic-v5-installer

