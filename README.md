# QQ-emoji-pack
Android 用户从 QQ 应用中导出表情包文件并进行修复 项目使用 JavaScript 脚本 来处理导出的无扩展名文件 使其恢复正常可用的图片格式 该项目适合想备份或提取 QQ 原生表情包的用户
### 第一步
- 下载zerotermux安装并打开
- 输入以下命令：
```
pkg install nodejs -y && pkg install wget -y && cd /storage/emulated/0/&& mkdir q表情包 && cd q表情包 && mkdir Ori && wget https://raw.githubusercontent.com/ovoox/QQ-emoji-pack/main/fix-images.js
```

### 第二步
- 下载MT管理器安装并打开
- 输入以下路径并跳转：
```
/storage/emulated/0/Android/data/com.tencent.mobileqq/Tencent/QQ_Favorite/
```
- 之后你会看到一堆没有后缀的文件
- 再输入以下路径并跳转
```
/storage/emulated/0/q表情包/Ori/
```
- 将一堆没有后缀的文件复制到刚跳转的目录里面

### 第三步
- 打开zerotermux输入以下命令并执行
```
node ./fix-images.js
```
- 之后回到MT管理器查看结果

Telegram资源分享频道：
https://t.me/xoxxxa
