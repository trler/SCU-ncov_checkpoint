SCU-ncov_checkpoint
====
四川大学微服务健康每日报 自动打卡
----

## 更新日志：
### 最近更新：2021年11月1日
* 修复了某些情况下报错 (DevToolsActivePort file doesn't exist)

### 2021年10月21日
* main-mysql分支已实现打卡后微信实时通知打卡情况。
* main-mysql分支请在config.ini中填写配置。

### 2021年9月23日
* 开放少量测试名额，详情请联系作者
* 新增main-mysql分支，支持链接mysql数据库
* 计划：实现cookie登录、等待时间优化、验证码识别优化

### 2021年9月13日
* 大量减少无用代码/文件
* 已经针对需要验证码功能做出更新
* 计划：实现cookie登录、等待时间优化、验证码识别优化


# 免责声明：
## 本项目仅供学习交流使用，请勿用于其他用途！
## 根据《教育部公安厅关于进一步做好新型冠状病毒感染的肺炎疫情“日报告、零报告”工作的通知》、《中华人民共和国传染病防疫法》、《中华人民共和国治安管理处罚法》等，请需要打卡的同学于每天中午12:00前通过“健康每日报”功能进行每日健康打卡，在填写过程中确认真实无误，若有任何问题，请及时与辅导员联系！

# 隐私声明：
## 您输入的所有数据（包括但不限于学号、密码、地理位置信息）均储存在您本人的计算机或服务器上，仅用于微服务身份认证，不会以任何形式泄露！

# 本项目可实现：
* 使用账号密码自动登录
  * 无需提供cookies，无需担心cookies失效问题
  * 可实现批量打卡
* 继承上次打卡数据，自动填报
  * 无需获取post表单中uid、id等信息
* 根据提供的经纬度信息虚拟获取位置
  * 解决部分设备或浏览器无定位功能的问题
  
# 使用方法：
[项目文档](http://docs.somenothing.top/web/#/6/24)


# 开发 & 更新：
author: somenothing <br>
e-mail: admin@somenothing.top <br>
使用python - selenium <br>
使用百度ocr <br>
#### 请留下star，谢谢！
