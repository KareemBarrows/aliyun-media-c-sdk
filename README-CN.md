# Aliyun OSS Media C SDK 

[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE)
[![GitHub version](https://badge.fury.io/gh/aliyun%2Faliyun-media-c-sdk.svg)](https://badge.fury.io/gh/aliyun%2Faliyun-media-c-sdk)

## [README of English](https://github.com/aliyun/aliyun-media-c-sdk/blob/master/README.md)

## 关于
不少情况下，我们都需要将摄像头拍摄的视频快速存储到云端（OSS），但是我们也有一些因素要考虑：

- 设备上不能存储永久access key id和access key secret，因为可能泄露
- 设备上只允许上传或者下载，不允许删除、修改配置等管理权限
- 可以提供网页让用户去管理自己的视频
- 对设备的权限精准控制
- 对设备的权限存在有效期，不能让设备永久持有某种权限`
- 希望摄像机输出的音视频可以通过HLS协议直接被用户观看

针对以上考虑，我们推出了OSS MEDIA C SDK，构建于OSS C SDK版本之上，可以方便的解决上述问题，为音视频行业提供更完善易用的解决方案。

## 版本
 - 当前版本：V2.0.2

### 兼容性
- 由于底层C SDK相对于前一版本不兼容导致Media SDK不兼容1.x.x系列SDK，不兼容接口主要涉及list相关

## 依赖
 - [OSS C SDK 3.4.0](https://github.com/aliyun/aliyun-oss-c-sdk)

## 使用
 - 示例程序：[参考sample部分](sample/)
 - SDK文档：[阿里云OSS MEDIA SDK文档](https://help.aliyun.com/document_detail/oss/sdk/media-c-sdk/preface.html)

## 联系我们
- [阿里云OSS官方网站](http://oss.aliyun.com)  
- [阿里云OSS官方论坛](http://bbs.aliyun.com)
- [阿里云OSS官方文档中心](http://www.aliyun.com/product/oss#Docs)
- 阿里云官方技术支持：[提交工单](https://workorder.console.aliyun.com/#/ticket/createIndex)   
