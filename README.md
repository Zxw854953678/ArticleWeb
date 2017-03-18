## Article Web ##
---------------------------------------
### prerequisite ###
默认安装好 Java、Eclipse、Tomcat环境
<br />
### run ###
1. 打开 Eclipse ，点击选项卡中的 windows -> Preferences -> server runtime environments -> add -> Apache Tomcat v7.0(本项目用的是7.0) -> Next -> 选择 Tomcat 的安装路径 -> finish -> ok;
2. 项目右键 -> build path -> configure Build Path -> Add Library -> Server Runtime -> Next -> 选择第1步建的 Apache Tomcat v7.0 -> finish -> Ok;
3. 点击选项卡中的 windows -> Show view -> other -> server -> servers -> Ok；
4. server选项卡（一般在Eclipse的下方）-> 点击蓝色字体（No servers are available.Click this link to create a new server ...） -> Server  runtime environments （一般为Apache Tomcat v7.0） -> Next -> 将左边要运行的项目添加到右边 -> finish;
5. 启动 Tomcat 服务（在 Eclipse 下）；
6. 打开浏览器，输入网址：http://localhost:8080/article/index.jsp
