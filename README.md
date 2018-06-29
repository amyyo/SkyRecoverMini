# QuietWeather
一款天气应用的微信小程序

## 数据来源
地理编码、天气数据均来自[百度地图开放平台](https://lbsyun.baidu.com/)。个人开发完全免费，有对应的小程序 sdk，加入即可，但是返回的天气数据较少。

## 运行前准备
> * [注册微信小程序](https://mp.weixin.qq.com/wxopen/waregister?action=step1)，获取 appid
> * 注册[百度地图开放平台](https://lbsyun.baidu.com/)开发者，创建应用，获取 ak（其他配置自行查看）
> * 在 app.js 中替换 globalData 中的 ak 为自己的 ak
> * Run