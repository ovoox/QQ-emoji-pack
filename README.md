# QQ-emoji-pack
QQ表情包导出修复教程

### 第一步
- 下载zerotermux安装并打开
- 输入以下命令：
```
pkg install nodejs -y && pkg install wget -y && cd /storage/emulated/0/&& mkdir q表情包 && cd q表情包 && mkdir Ori && wget https://raw.githubusercontent.com/ovoox/QQ-emoji-pack/main/fix-images
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

