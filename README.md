# wyc-api

智能AI文章写作伪原创接口API 更新时间: 2022/4/1

### 接口介绍

支持6种伪原创算法

不是单单关键词替换,而是语句组合替换，并在不断更新数据。

支持火车头插件使用

### 在线体验效果
http://cj.lycecho.com/api_form.php?key=test123

### 案例
## 原文
# 红尘中，枝叶袅袅，花瓣飘飘，我的灵魂飞出世俗之外，在流年里做文字的舞蹈。为了与你相会，漂泊不远千里，只为了这个夏日奇缘。华南作证，温度高，水不弃。我喜欢这种感情，热情似火，考验着身体的耐力，考验着爱的能力。我想告诉你，你的血液也流过了我的心，我想告诉风，它的柔美，我也领略过，我想告诉夏天，我愿回到东北去避暑，与你缠绵。我漂泊南方，离开了家乡，离开你。就像花瓣落下，就像蝶儿优雅，我很想弯下腰拾起这份余香，放在手心。依旧可以品味着这种芬芳，让很多的回忆，在婉转落下很多思念，还有爱。华南阳光的热情，总是让那些足迹成为记忆。你我相见在现实里，是否能实现？你是否能来到我身边？

## 伪原创
# 红尘中，枝叶袅袅，花瓣飘动，我的灵魂飞出世俗，与文字共舞于流年。为了遇见你，我漂泊千里，只为这夏日的浪漫。华南证明气温高，水不会弃。我喜欢这种感觉，充满激情，考验身体的耐力和爱的能力。我想告诉你，你的血也流过我的心。我想告诉风，我经历过它的柔软。我想告诉你，夏天，我想回东北和你一起度过夏天。 我向南漂泊，离开了我的家乡，离开了你。喜欢花瓣飘落，喜欢蝴蝶飘逸，真想弯腰拾起这余香，放在手中。还能尝到这种香味，让很多回忆，在婉转中落下很多思念，和爱意。华南阳光的热情总是让那些脚印成为回忆。我在现实中看到你，能实现吗？你能来我身边吗？


### 接口地址

| URL                            | POST传递参数                    |
| ------------------------------ | --------------------------- |
| http://cj.lycecho.com/api.php?json=0&v=1&key=申请的token | {wenzhang:'文章内容'}    |
| http://cj.lycecho.com/api.php?json=0&v=2&key=申请的token | {wenzhang:'文章内容'}   | 
| 测试用TOKEN：test123           | 测试token每日免费伪原创查询10w次 | |



### 收费模式

由于服务器每个月费用高昂，因此开放接口分为付费+免费模式，两种模式均提供HTML+JSON版本接口

两种接口均不含广告，付费版本可拥有自己的token次数请求，测试版本则共享每天次数没了就没了

| 功能说明             | 付费版本 | 免费版本 |
| -------------------- | -------- | -------- |
| 价格                 | 100元/月  | 免费     |
| JSON接口             | √        | √        |
| QPS并发              | 不限     | 1并发    |
| 日请求次数           | 不限    | 共享10W      |
| IP白名单             | √        | ×        |
| 技术支持(简单)       | √        | ×        |
| QQ咨询(599858092) | √        | √        |
