#三、界面原型

## 3.1 登录注册界面

注册时需输入姓名、学号/教职工号及学校等，进行身份验证。
 <img src="http://img.blog.csdn.net/20171020211827935?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvbTBfMzc4NzY5NTQ=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" width="90%" alt=""/>
## 3.2 学生端

###课程界面

（以高数为例）通过未提交作业（无讲解，不能编辑作业）与已经提交作业（有讲解，能编辑作业）来展示。

可以实现的功能如下：

 - 从课表中点击查看作业与通知，显示提交状态，方便直观。
 - 每一个作业里面都能查看老师讲解（老师上传讲解以后（在教师端有详细上传图解）），提出问题，提交作业。
 - 除了可以提出问题，也可以查看其他同学的问题，避免重复问问题。
 - 提出的问题可以由老师解答，也可以由同学解答，使得老师的负担减轻，同学提出的问题被解答迅速。
 - 提交作业可以上传附件，也可以通过上传照片的方式提交作业。

以下是未提交作业。

<img src="http://img.blog.csdn.net/20171020221523509?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvbTBfMzc4NzY5NTQ=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" width="150%" alt=""/>

以下是已提交作业。

<img src="http://img.blog.csdn.net/20171020221600840?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvbTBfMzc4NzY5NTQ=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" width="150%" alt=""/>

###资料界面

* 根据学生课表自动生成各门课程的资料文件夹
* 每门课程内含有自己整理的学习资料（可自行上传）以及老师共享的文件资料（可自行选择下载）
* 在课程内部可以自己创建文件夹管理复杂繁多的学习资料
* 学生也可自己创建自学的课程文件夹，进行学习资料管理

<img src="http://img.blog.csdn.net/20171020212742943?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvbTBfMzc4NzY5NTQ=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" width="120%" alt=""/>

## 3.3 教师端

###课程界面

可实现的功能如下：

 - 从课表中点击查看作业与通知，显示提交状态，方便直观。
 - 每一个作业都能添加讲解、查看同学提出的问题、查看提交情况。
 - 添加讲解可以通过图片，上传附件，语音等方式，快速讲解作业，以免占用课堂时间讲解作业。
 - 同学提出的问题，红点表示未解决，绿点表示已解决，方便直观。
 - 提交情况分为已提交和未提交两部分，已提交作业可以迅速评阅，添加评语，优秀作业可以加星。绿色勾代表已评阅，未打绿色勾表示还未评阅，黄色五角星代表优秀作业。
 
 <img src="http://img.blog.csdn.net/20171020221723072?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvbTBfMzc4NzY5NTQ=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" width="150%" alt=""/>
 
###资料界面

* 根据教师任课表自动生成课程文件夹
* 教师自行上传课堂教学资料，选择是否共享到课堂，若共享，学生将会接收到这份资料
* 课堂文件夹内教师可根据需要创建文件夹，对学习资料进行分类管理
* 教师根据自己的需求创建课堂文件夹

<img src="http://img.blog.csdn.net/20171020214606868?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvbTBfMzc4NzY5NTQ=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" width="90%" alt=""/>


###我的界面

* 包含个人信息、设置、意见反馈及退出登录功能
* *个人信息* 里可以查看学生or教师的学籍or教职工信息
* *设置* 里包含推送开关、分享、清理缓存功能
* *意见反馈* 用户可以直接在此反馈对此app的建议

学生端界面
<img src="http://img.blog.csdn.net/20171020213815084?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvbTBfMzc4NzY5NTQ=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" width="120%" alt=""/>
教师端界面
<img src="http://img.blog.csdn.net/20171020213915397?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvbTBfMzc4NzY5NTQ=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" width="120%" alt=""/>


