# 💌 站点站内信与公告 - 微信推送
MR插件，定时获取站点最新站内信与公告
- 每天两次定时获取
- 推送通知时调用各个站点独立的封面图（一站一图），若没有对应的图，调用默认封面。
- 点击消息封面可进入详情页，查看完整消息内容
- 点击阅读原文跳转到站内信详情页或未读列表

目前自测有问题的站点：馒头，不可说，瓷器，不可说后来打了个补丁也算正常了，馒头和瓷器不知道是不是我网络问题，获取失败了。基于NaNaKo_大佬的插件二次开发的微信通知专用版，感谢大佬！

本人能力有限，各位可帮助一起完善提PR即可！


## 使用方法
- 将 `sites_message_wx` 文件夹放到 `Plugins` 文件夹，重启MR。
- 因 MR 主干没有 mpnews 消息类型的微信通道，需要独立填写配置，需要配置的企业微信参数可参见 [企业微信参数获取方法](https://alanoo.notion.site/thumb_media_id-64f170f7dcd14202ac5abd6d0e5031fb)



## 效果预览
![git封面](https://user-images.githubusercontent.com/68833595/210979260-1c22820b-6d3c-4e78-be53-c85f22dbae4c.png)


