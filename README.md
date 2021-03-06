# 团子翻译器 - 基于OCR的生肉翻译软件


[![最新版本](https://img.shields.io/badge/%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-Ver3.6.2-ff69b4)](https://github.com/PantsuDango/Dango-Translator)
[![更新时间](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%B6%E9%97%B4-2021--08--19-ff69b4)]()
[![更新时间](https://img.shields.io/badge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F-win7--10-ff69b4)]()
[![GitHubStars](https://img.shields.io/github/stars/PantsuDango/Dango-Translator)]()
[![GitHubForks](https://img.shields.io/github/forks/PantsuDango/Dango-Translator)]()
[![作者](https://img.shields.io/badge/QQ-%E8%83%96%E6%AC%A1%E5%9B%A2%E5%AD%90-ff69b4)](https://github.com/PantsuDango/ImageHub/blob/master/DangoTranslate/public/%E4%BD%9C%E8%80%85.png)
[![群号](https://img.shields.io/badge/%E6%9C%80%E6%96%B0%E4%BA%A4%E6%B5%81%E7%BE%A4-4%E7%BE%A4-ff69b4)](https://github.com/PantsuDango/ImageHub/blob/master/DangoTranslate/public/4%E7%BE%A4.jpg)

  
## 简介

团子翻译器是一款生肉翻译软件，通过OCR识别屏幕特定范围内的文字，然后将识别到的文字调取各大厂的翻译，并输出翻译结果。

+ 搭载了离线OCR，项目地址：[DangoOCR](https://github.com/PantsuDango/DangoOCR) 
+ 实现自动模式，循环识别区域内的文本并翻译
+ 配置了12种翻译源
+ 账号系统，能够自动云端保存配置


  
## 安装版下载

- 群文件下载：[![作者](https://img.shields.io/badge/%E6%9C%80%E6%96%B0%E4%BA%A4%E6%B5%81%E7%BE%A4-4%E7%BE%A4-ff69b4)](https://github.com/PantsuDango/ImageHub/blob/master/DangoTranslate/public/4%E7%BE%A4.jpg)  
- 百度网盘下载（提取码-975h）：[下载地址](https://pan.baidu.com/s/1AD9JWSAKS69gOawwvMXXQw)
- GitHub下载：[下载地址](https://github.com/PantsuDango/Dango-Translator/releases/download/Ver3.6.2/DangoTranslate-Ver3.6.2.zip)
- 解压密码：Dango


  
## 更新日志

#### 翻译器相关 

[![最新版本](https://img.shields.io/badge/%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-Ver3.6.2-ff69b4)]()
[![更新时间](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%B6%E9%97%B4-2021--08--19-ff69b4)]()

+ 修复如果挂了代理可能会导致无法注册和登录的问题；  
+ 修复了离线OCR在识别到个别异体繁体字可能导致出错的问题；  
+ 翻译器上各翻译API的注册按钮，由原来的弹出本地教程文档，改为弹出在线文档的网页；  
+ 更多更新日志：[查看](https://github.com/PantsuDango/Dango-Translator/blob/master/docx/%E6%9B%B4%E6%96%B0%E6%97%A5%E5%BF%97.md)  

#### OCR相关

[![最新版本](https://img.shields.io/badge/%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-Ver1.2-ff69b4)]()
[![更新时间](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%B6%E9%97%B4-2021--08--19-ff69b4)]()

+ 大幅度加快了识别速度;
+ 识别准确度略有提高;
+ 对环境的适配稳定性更好了；
+ 安装时会输出一堆红色ERROR的吓人信息；
+ 修复了安装时会报 'No module named 'cv2' 的问题;
+ 修复了安装时会报 'No module named 'paddle.fluid.core_noavx' 的问题;

+ 更多更新日志：[查看]()


  
## 使用教程

[翻译器教程](https://github.com/PantsuDango/Dango-Translator/blob/master/docx/%E7%BF%BB%E8%AF%91%E5%99%A8%E6%95%99%E7%A8%8B.md)

[离线OCR教程]()


  
## 原理说明

![](https://github.com/PantsuDango/ImageHub/blob/master/DangoTranslate/public/%E6%B5%81%E7%A8%8B%E5%9B%BE.png)


  
## 更新计划

#### 新增项

- [ ] 升级Ver4.0，全新的界面设计，更舒服的交互
- [ ] 加入DeepL 翻译
- [ ] 离线OCR加入GPU模式
- [ ] 加入云服务在线OCR（收费）
- [ ] 加入自定义OCR API接口功能，可以自由添加想要的OCR API接口（需要略懂开发）

#### 优化项

- [ ] 优化公共翻译和网页翻译，提高翻译质量，降低抽风率
- [ ] 离线OCR取消黑窗，加入简单的GUI界面，最小化从任务栏改为系统托盘
- [ ] 对屏幕缩放比例175%以上做适配
- [ ] 离线OCR加入竖排文本检测模式用于翻译生肉本

#### 修复项

- [ ] 修复快捷键会失效的问题
- [ ] 修复手动模式下，程序概率卡死的问题
- [ ] 修复多屏模式下，副屏幕无法截图的问题

  
 ## 特别鸣谢

[PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)  离线OCR基于此框架搭建

[QPT 打包工具](https://github.com/GT-ZhangAcer/QPT)  离线OCR基于此工具打包

[GT-Zhang](https://github.com/GT-ZhangAcer) 离线OCR开发过程给予了诸多帮助的大佬

  
## 软件预览

#### 使用效果

![](https://github.com/PantsuDango/ImageHub/blob/master/DangoTranslate/public/%E4%BD%BF%E7%94%A8%E6%95%88%E6%9E%9C.png)

#### 登录界面
<img src="https://github.com/PantsuDango/ImageHub/blob/master/DangoTranslate/public/%E7%99%BB%E5%BD%95.png" width="50%" height="50%">

#### 主界面

![](https://github.com/PantsuDango/ImageHub/blob/master/DangoTranslate/public/%E4%B8%BB%E7%95%8C%E9%9D%A2.png)

#### 设置界面
<img src="https://github.com/PantsuDango/ImageHub/blob/master/DangoTranslate/public/%E8%AE%BE%E7%BD%AE1.png" width="50%" height="50%">
<img src="https://github.com/PantsuDango/ImageHub/blob/master/DangoTranslate/public/%E8%AE%BE%E7%BD%AE2.png" width="50%" height="50%">
<img src="https://github.com/PantsuDango/ImageHub/blob/master/DangoTranslate/public/%E8%AE%BE%E7%BD%AE4.png" width="50%" height="50%">
<img src="https://github.com/PantsuDango/ImageHub/blob/master/DangoTranslate/public/%E8%AE%BE%E7%BD%AE5.png" width="50%" height="50%">

#### 支持作者
<img src="https://github.com/PantsuDango/ImageHub/blob/master/DangoTranslate/public/%E6%94%AF%E6%8C%81%E4%BD%9C%E8%80%85.png" width="50%" height="50%">
