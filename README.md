# yingshi-webcam

### Developing

Resources:

[萤石开放平台](https://open.ys7.com/)

视频嵌入式
    iframe可以直接嵌入到页面中，作为页面的一个元素，可以搭载自己页面的UI进行开发，适合需要视频融入页面的产品。

```html
<iframe
  src="https://open.ys7.com/ezopen/h5/iframe?url=ezopen://open.ys7.com/203751922/1.live&autoplay=1&accessToken=ra.23xamzw35p27yshy6ea2hvud3riulmqo-173c7qgql3-0lxt9kc-jkzzoodlk"
  width="600"
  height="400"
  id="ysOpenDevice"
  allowfullscreen
>
</iframe>
参数介绍
```
url=ezopen://open.ys7.com/203751922/1.live&autoplay=1&accessToken=ra.a7xvb48j8zg2q30m2u126bg52s0akn6o-6eymxh3w9q-0crijo7-f9fuekxen

    url：监控地址，包含验证码、设备序列号、通道号、清晰度、播放类型

    autoplay：1-开启自动播放，未显示字段-关闭自动播放

    audio：1-开启音频，未显示字段-关闭音频

    accessToken：访问令牌，播放监控地址的必要参数
