We重邮
===
官网：https://we.cqu.pt \ http://we.cqupt.edu.cn

> **We重邮** 是一个**微信小程序**，是有别于订阅号/服务号的一种全新的连接用户与服务的方式，可以在微信内被便捷地获取和传播，同时具有出色的使用体验。
> 
> **We重邮** 是**碎片式信息一体化校园移动门户**，适用于学生和教师，集课表、成绩、考试、空教室、学生、一卡通、借阅、学费、电费、报修、公告等各功能于一身。
>
> **We重邮** 更是/更有... （搜人利器、点名神器、一卡通消费、学费信息、最好用的课表...） 

---

<img src="https://cloud.githubusercontent.com/assets/11243798/21165504/c4c85a02-c1da-11e6-8937-36e9a8f5de59.png" alt="首页" style="max-width:50%;">

更多截图见：https://github.com/lanshan-studio/wecqupt/issues/196

---

## 开源许可证 License AGPLv3

> 开源是一种精神，We重邮微信小程序的开源更是蓝山工作室的一种进步
> 
> 开源是自由的，而不是免费的；Free(自由) is not free(免费)。 

请认真阅读并遵守以下开源协议

`AGPLv3` [GNU Affero General Public License v3.0](https://github.com/lanshan-studio/wecqupt/blob/master/LICENSE)

---

## 版本日志

> 版本号命名规则 vX.Y.Z
> 
> X: 主版本号, Y: 次版本号, Z: 修订号
> 
> 修饰后缀词(可选) - alpha: 内部版本, beta: 测试版, 无(默认): 正式版

### v1.0.0 正式版 【待发布】

### v0.1.0 beta 公测版 【待发布】

### v0.0.8 alpha 内测体验版 【当前版本】
* 2016.12.12 发布
* 修复BUG
  * 修复当用户为教师时的一些使用体验
  * 修复课表详情课程名有两行时会被遮住一部分的问题
  * 修复一卡通有时错位的问题
  * 修复了无法报修及报修列表无法即时更新的问题
  * 修复了学生查询的一些问题
* 优化完善
  * 绑定及完善信息页面新增动画特效
  * 优化课表等页面各动画，使其更快更流畅
  * 一卡通新增横纵坐标提醒
  * 一卡通新增两个折线图切换：消费金额和余额 视图
  * 现可以通过左右滑动来切换同时有两次课时的课表详情
  * 现可以通过左右滑动来切换资讯新闻类别
  * 兼容性优化，优化了ios的细节差异
  * 完善关于、反馈页面

### v0.0.7 alpha 内测体验版 
* 2016.12.5 发布
* 修复BUG
  * 修复绑定过后没有自动刷新首页
  * 修复空教室列表不能正常换行的问题
  * 修复报修申请有时无法提交的问题
  * 修复课表查询三节连上时的课次显示
  * 修复课表查询第20周无日期的问题
  * 修复电费查询描述不当的问题
* 优化完善
  * 用户不用再需要完善身份证后6位信息
  * 资讯类别筛选将一直固定在顶部
  * 学生查询输入框新增清空按钮，改善搜索按钮样式
  * 降低课表查询的黑色笼罩层透明度
  * 寝室号禁止输入字母，并且需选择寝室楼栋才能提交
  * 一些位置偏底的按钮离底部的距离得到了提升
  * 点击历史借阅将会出现无法查询的提醒
  * 某些位数固定的输入框，输入至指定位数后将自动收起键盘
  * 去掉了登录帮助文字里的句号

### v0.0.6 alpha 内测体验版
* 2016.12.1 发布
* 开启内测

---

## 分支管理

```
wecqupt
  ├─ master       // 默认分支（开发测试版本所用分支；保护分支，只允许由[other]分支-Pull Requests-其他人review而来，故无法push）
  ├─ stable       // 稳定分支（正式版本所用分支；高级保护分支，只允许管理员操作，通常由master分支-Pull Requests而来）
  └─ [other]      // 其他开发分支（只允许该项目Collaborators创建及push分支）
```

---

更多详见wiki：[开发记录/开发须知](https://github.com/lanshan-studio/wecqupt/wiki)

> @ 重庆邮电大学 - 蓝山工作室 https://lanshan.studio