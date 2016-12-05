具有自主知识产权的连麦内核，欢迎大家试用，并提建议,如果喜欢请star~
## 效果图
![效果图](https://github.com/ksvc/KSYRTCLive_iOS/wiki/images/xiaoguo.png)
## 1. 功能特性
### 1.1 连麦功能
* 基于 [KSYLiveSDK](https://github.com/ksvc/KSYLive_iOS/)的 连麦功能。
### 1.2 文档
[手把手教你学会如何连麦](https://github.com/ksvc/KSYRTCLive_iOS/wiki)

### 1.3 集成方式
- 需要导入的动态库（pod方式）：
```
pod 'KSYRTCLive’,:path => '../'
pod 'libksygpulive/KSYGPUResource', :git => 'https://github.com/ksvc/KSYLive_iOS.git', :tag => 'v1.8.7’
pod 'libksygpulive/libksygpulive', :git => 'https://github.com/ksvc/KSYLive_iOS.git', :tag => 'v1.8.7’
```
- 需要导入的动态库（手动方式):
```
framework下的libksyrtclivedy.framework库。
［ksylive_ios主版本］（https://github.com/ksvc/KSYLive_iOS/releases/tag/v1.8.7）
```
- 需要导入的文件（连麦）：
```
source目录下 KSYRTCStreamerKit.h/m
```
- 需要导入的文件（私聊）：
```
source目录下 KSYSChatKit.h／m
```


## 2. 连麦大事记
### 2.1 发布大事记
- 2016.08.04 初始版本;
- 2016.08.10 支持纯语音连麦;
- 2016.08.15 支持美颜连麦;
- 2016.08.26 支持AEC(回音消除);
- 2016.09.26 音视频质量极致优化,超稳定版本v1.8.5发布。
- 2016.11.22 和rtc主版本分离，更加易于集成。开源[KSYRTCStreamerKit.m]
- 2016.12.01 发布私聊版本。

### 2.2 近期工作
- 2016.12.xx 多人连麦；

## 3. 商务合作
demo中有测试评估账号，可以直接实现一对一连麦。  
正式上线需要申请金山云账号，请联系金山云商务。

## 4. 反馈与建议
- 主页：[金山云](http://v.ksyun.com)
- 邮箱：<zengfanping@kingsoft.com>
- QQ讨论群：574179720
- Issues: <https://github.com/ksvc/KSYRTCLive_iOS/issues>
