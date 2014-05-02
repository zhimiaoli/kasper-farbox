---
layout: post
title:  "Welcome to Farbox"
date:   2014-5-2 10:18:00
tags: farbox
feature: http://24.media.tumblr.com/c78ebb9243f15f52d3689c5a91e721c3/tumblr_n381qgQRTS1st5lhmo1_1280.jpg

---

[TOC]

你好，这个是Farbox主题Kasper的演示页面。Kasper最初是Ghost.org为他们的博客系统Ghost设计的，然后由[http://github.com/rosario/kasper](http://github.com/rosario/kasper)移植到Jekyll的，而你现在看到的是我在他的基础上，将这个主题移植到Farbox上了。

## 特点

1. 响应式设计，在电脑上和手机都会有很好的效果
2. 极简
3. 特色图片

## Todo

添加自定义的404页面

## 不会修正

不会支持IE


## 代码高亮测试

现在还没有去看Farbox的代码高亮要怎么用pygments

	def print_hi(name)
	  puts "Hi, #{name}"
	end
	print_hi('Tom')

## 安装使用

### 安装

1. 在[kasperdemo.farbox.com](http://kasperdemo.farbox.com/template) Clone到自己的博客，然后在`_image`文件夹里面放入`home_feature.jpg`图片作为首页特色图片。
2. 修改`post.html` 中的作者信息。
3. 在Farbox的后台中设置你的头像
4. 在Farbox设置Disqus你的网站

### 使用

特色图像的设置就是在标题的设置一个feature属性，可以是你的farbox站里面的图片，也可以是完整的URL
	
	feature: /_image/home_feature.jpg

或者
	
	feature: http://24.media.tumblr.com/c78ebb9243f15f52d3689c5a91e721c3/tumblr_n381qgQRTS1st5lhmo1_1280.jpg



