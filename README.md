## 基于人脸识别的宿舍考勤app



> 大学生涯第一个比赛项目，望勿喷

### 技术栈
基于mui.js框架通过Hbuilder打包构建的webapp
基于SSM框架和mysql数据库构建的后端

全局通过ajax进行数据交互，人脸识别通过调用python后端接口，传照片和视频流过去进行识别，不可以进行离线识别。

通过实现clmtrackr.js人脸活体检测

通过高德地图api实现实时定位

### 具体功能

* 登陆，修改密码
* 后台发通知公告前台展示
* 人脸识别、活体检测、实时定位 打卡签到功能
* 请假功能、签到倒计时
* 用户信息维护 （用户提供三张照片提取人脸特征值，并存于数据库）
* 签到情况统计（待完善）

### 打包构建app

用HBuilder打开，通过usb运行到手机，运行到模拟器等。可通过本地打包和HBuilder提供的云打包。

可以下载unpackage/release下的apk安装，点击修改密码进入免登录进入app





### 展示图
![kaoqin-1.jpg](https://i.loli.net/2020/03/03/FeZjnUOlpxNMaiv.jpg)
![kaoqin-8.jpg](https://i.loli.net/2020/03/03/M9OmWD14lyRaHNd.jpg)
![kaoqin-2.jpg](https://i.loli.net/2020/03/03/6rgHPK2zFdGwVfo.jpg)
![kaoqin-4.jpg](https://i.loli.net/2020/03/03/n83Zfj7AFdYmwvp.jpg)
![kaoqin-9.png](https://i.loli.net/2020/03/03/ulW2VckpvBF61fr.png)
![kaoqin-6.png](https://i.loli.net/2020/03/03/XFtzkeL5Mn3soDm.png)
![kaoqin-5.jpg](https://i.loli.net/2020/03/03/bHIiFoyrZVOtDnq.jpg)
![kaoqin-3.png](https://i.loli.net/2020/03/03/D8JZRAfj1GxmpTL.png)
![kaoqin-7.jpg](https://i.loli.net/2020/03/03/xsJy1AOPSBLUYod.jpg)