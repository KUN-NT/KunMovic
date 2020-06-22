# 知识检索

## wx:if

- <view wx:if="{{test}}"></view>

## wx:for

- 每项默认名为item 使用 wx:for-item 自定义名称
- 使用wx:key-item 修改key的默认值

> <view wx:for="{{tests}}" wx:for-item="test" wx:key="index">
> {{index+1}}:{{test}}
> </view>

## 样式文件导入

> 在样式文件中使用@import 导入

> @import "test.wxss";

## view

- 类似div

hover-class 设置按下去的样式类






## 备注
- bilibili接口地址
> https://easy-mock.com/mock/5c1dfd98e8bfa547414a5278/bili

| 接口名称 | 接口路径 | 备注 |
| - | -: | :-: |
| 首页导航 | /navList |       |
| 首页轮播图 | /swiperList |       |
| 视频列表 | /videosList |       |
| 视频详情 | /videoDetail?id |   需要带上视频id    |
| 推荐视频 | /othersList?id      |   需要带上视频id    |
| 评论视频 | /commentsList?id |    需要带上视频id   |