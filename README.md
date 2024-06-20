<p align="center">
	<img alt="logo" src="https://assets-1256020106.cos.ap-beijing.myqcloud.com/zebra-swiper/logo.png" width="220" style="margin-bottom: 10px;">
</p>

<h1 align="center">mz-swiper</h1>

<p align="center">基于ZebraSwiper, 魔改了下解决uni-app报错问题。</p>

<p align="center">
	🔥 <a href="https://swiper.zebraui.com/">文档网站</a>
	&nbsp;
	&nbsp;
	🚀 <a href="https://zebraui.com/" target="_blank">zebraUI组件库</a>
</p>

## 介绍

## 特性

- 全面对标 swiper，并实现全端兼容
- 兼容多端，小程序也可实现 3D 轮播效果
- 可自定义 3D 效果
- 多种示例可供参考

## 安装

### npm 方式

```bash
npm i mz-swiper
```

```js
// pages.json

{
  "easycom": {
    "autoscan": true,
    "custom": {
      "^z-(.*)": "mz-swiper/src/zebra-swiper/components/z-$1/z-$1.vue"
    }
  },
	"pages": [...],
	"globalStyle": {...}
}
```

## 手机预览

<div>
	<img alt="wx" src="https://assets-1256020106.cos.ap-beijing.myqcloud.com/zebra-swiper/wx.jpg" width="200" />
	<img alt="ali" src="https://assets-1256020106.cos.ap-beijing.myqcloud.com/zebra-swiper/ali.jpg" width="200" />
	<img alt="h5" src="https://assets-1256020106.cos.ap-beijing.myqcloud.com/zebra-swiper/h5.png" width="200" />
</div>

## 预览

<div style="display:flex;flex-wrap:wrap;margin-top:30px;">
 <img alt="gif" src="https://assets-1256020106.file.myqcloud.com/zebra-swiper/show/total1.gif" width="300" style="margin:20px;" />
 <img alt="gif" src="https://assets-1256020106.file.myqcloud.com/zebra-swiper/show/total2.gif" width="300" style="margin:20px;" />
 <img alt="gif" src="https://assets-1256020106.file.myqcloud.com/zebra-swiper/show/total3.gif" width="300" style="margin:20px;" />
</div>
