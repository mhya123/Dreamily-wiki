# 梦幻互通整合包

## 下载整合包
```
访问 https://www.minebbs.com/resources/paper-1-20-4-new.4663/
```

## 启动前的依赖

### 安装JDK21
> 本整合包依赖于JDK21
```
# 下载(直接点击)
https://download.oracle.com/java/21/latest/jdk-21_windows-x64_bin.msi
```
### 解压整合包

```bash
# 推荐使用 bandizip 7z WinRAR 等专业软件进行解压操作

# 这种操作应该不需要图了吧

```

### 启动服务端

<h3> 安装好VC运行库了和解压出来了就该开启一个服务器了.</h3>
梦幻整合包\java_path.txt 设置JAVA路径
<h4>直接点击启动脚本就可以启动了</h4>

# 修改一些配置文件
## 菜单配置文件
``` bash
# 路径 plugins/DeluxeMenus/gui_menus
# 请一定不要使用记事本编辑！！！
```
## 修改TAB配置文件
``` bash
# 路径 plugins\TAB
修改 config.yml 
# 请一定不要使用记事本编辑！！！
```
## 修改 MOTD
``` 
# 路径 plugins\MiniMOTD
修改 main.conf
# 颜色代码是16进制 https://www.toolhelper.cn/Color/RGBToHex 
```
## 修改Geyser配置文件
``` bash
# 路径 plugins\Geyser-Spigot
修改 config.yml 
# 请一定不要使用记事本编辑！！！
```
## 修改全息影像配置文件
``` bash
# 路径 plugins/DecentHolograms
# 请一定不要使用记事本编辑！！！
```
## 修改进群连接配置文件
``` bash
# 路径plugins/Skript/scripts
# 请一定不要使用记事本编辑！！！
```
## 修改自动公告配置文件
``` bash
# 路径 plugins/ChatManager 和 plugins/Infiniteannouncements
# 请一定不要使用记事本编辑！！！
```
# 部分指令
``` bash
给玩家用户组 lp user %player_name% parent set {权限组}'
/skins 打开皮肤菜单
/tpr 随机传送
/tpa 玩家互传
/point 或者是 /playerpoint 打开点券系统
```
# 常见问题解答
* A 为什么我启动了启动脚本自动打开了JDK下载页面
* B 你没有安装JDK 21 或者是没配置path 要是安装了请前往 启动脚本指定一个JDK21路径 
* A 为什么我的自动更新检测器没用啊
* B 可能是你的服务器屏蔽了海外尝试重新打开