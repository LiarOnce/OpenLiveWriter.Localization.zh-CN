# OpenLiveWriter.Localization.zh-CN
Chinese translation for OpenLiveWriter 0.6.2.0  
注意！：该补丁只适用于最新版 0.6.2.0 ！    
目前该补丁可能还有未汉化部分，如有发现请在issue中提出。

## 如何使用
1，下载该 [DLL文件](https://github.com/LiarOnce/OpenLiveWriter.Localization.zh-CN/raw/master/OpenLiveWriter.Localization.dll)  
2，定位到 Open Live Writer 主程序目录（一般是 app-0.x.x ）。  
3，复制并将主程序目录中的原 DLL 文件替换为下载的 DLL 文件即可。

## 如何编译
1，下载 `localization` 下的 `Properties.resx` 和 `Strings.resx` 文件备用。  
2，克隆 Open Live Writer 最新版源码。  
3，转到 Open Live Writer 项目路径，运行`build.cmd`直到结束。
4，转到 `src\managed\OpenLiveWriter.Localization` 覆盖下载的 `Properties.resx` 和 `Strings.resx` 文件。
5，转到上一级目录，双击 `writer.sln`，找到 `OpenLiveWriter.Localization` 检查 `Properties.resx` 和 `Strings.resx`中的字符是否为中文字符。
6，如果是，调为 `Release` 模式，右键 `OpenLiveWriter.Localization` 点击生成，在 `src\managed\bin\Release\i386\Writer` 下即可找到已编译的DLL文件。如果不是，请将原项目的 `Properties.resx` 和 `Strings.resx` 排除并重新添加，再进行一次编译。

## 截图
就这样了：  

![screenshot](./screenshot.png)

## 感谢

大部分汉化内容：[chonghua/OpenLiveWriter-zh-CN](https://github.com/chonghua/OpenLiveWriter-zh-CN)
