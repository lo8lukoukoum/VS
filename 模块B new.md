## 服务器IspSrv上的工作任务

### 1.   互联网访问检测服务器

#### 为了模拟Internet访问测试，请搭建网卡互联网检测服务。

##### DNS

![image-20220921105852845](E:\笔记\typora\赛\模块B.assets\image-20220921105852845.png)

![image-20220921110941162](E:\笔记\typora\赛\模块B new.assets\image-20220921110941162.png)

![image-20220921111129900](E:\笔记\typora\赛\模块B new.assets\image-20220921111129900.png)

![image-20220921111300877](E:\笔记\typora\赛\模块B new.assets\image-20220921111300877.png)

![image-20220921111329000](E:\笔记\typora\赛\模块B new.assets\image-20220921111329000.png)

![image-20220921111440094](E:\笔记\typora\赛\模块B new.assets\image-20220921111440094.png)

![image-20220921111508043](E:\笔记\typora\赛\模块B new.assets\image-20220921111508043.png)

![image-20220921111537062](E:\笔记\typora\赛\模块B new.assets\image-20220921111537062.png)

![image-20220921111815347](E:\笔记\typora\赛\模块B new.assets\image-20220921111815347.png)

![image-20220921111701806](E:\笔记\typora\赛\模块B new.assets\image-20220921111701806.png)

![image-20220921111849695](E:\笔记\typora\赛\模块B new.assets\image-20220921111849695.png)

![image-20220921112012407](E:\笔记\typora\赛\模块B new.assets\image-20220921112012407.png)

![image-20220921112042007](E:\笔记\typora\赛\模块B new.assets\image-20220921112042007.png)

##### IIS

![image-20220921112433304](E:\笔记\typora\赛\模块B new.assets\image-20220921112433304.png)

![image-20220921121407661](E:\笔记\typora\赛\模块B new.assets\image-20220921121407661.png)

![image-20220921121752738](E:\笔记\typora\赛\模块B new.assets\image-20220921121752738.png)

 ![image-20220921121848338](E:\笔记\typora\赛\模块B new.assets\image-20220921121848338.png)

![image-20220921121942643](E:\笔记\typora\赛\模块B new.assets\image-20220921121942643.png)

![image-20220921122023205](E:\笔记\typora\赛\模块B new.assets\image-20220921122023205.png)

![image-20220921122207751](E:\笔记\typora\赛\模块B new.assets\image-20220921122207751.png)

![image-20220921122526056](E:\笔记\typora\赛\模块B new.assets\image-20220921122526056.png)





### 2.Web Print

  添加一台虚拟打印机，名称为“CS-Print”，发布到AD域。

  客户端们都能够通过访问“https://print.worldskills2018.cn/”查看打印机，证书由WORLDSKILLS2018-ROOTCA进行签署颁发。

![image-20220924154200584](模块B new.assets/image-20220924154200584.png)

![image-20220924154232347](模块B new.assets/image-20220924154232347.png)

![image-20220924174027987](模块B new.assets/image-20220924174027987.png)

![image-20220924174131079](模块B new.assets/image-20220924174131079.png)

![image-20220924174224880](模块B new.assets/image-20220924174224880.png)



#### 添加一台虚拟打印机，名称为“CS-Print”，发布到AD域。

![image-20220924174558251](模块B new.assets/image-20220924174558251.png)

![image-20220924174855379](模块B new.assets/image-20220924174855379.png)

![image-20220924211201389](模块B new.assets/image-20220924211201389.png)

![image-20220924211227504](模块B new.assets/image-20220924211227504.png)

![image-20220924211321315](模块B new.assets/image-20220924211321315.png)

![image-20220924211409530](模块B new.assets/image-20220924211409530.png)

![image-20220924211510021](模块B new.assets/image-20220924211510021.png)

![image-20220924211559256](模块B new.assets/image-20220924211559256.png)



#### 客户端们都能够通过访问“https://print.worldskills2018.cn/”查看打印机，证书由WORLDSKILLS2018-ROOTCA进行签署颁发。

![image-20220924212028129](模块B new.assets/image-20220924212028129.png)

![image-20220924212132191](模块B new.assets/image-20220924212132191.png)

![image-20220924212150019](模块B new.assets/image-20220924212150019.png)

![image-20220924214441550](模块B new.assets/image-20220924214441550.png)

![image-20220924212333955](模块B new.assets/image-20220924212333955.png)

![image-20220924212359780](模块B new.assets/image-20220924212359780.png)

![image-20220924212430971](模块B new.assets/image-20220924212430971.png)

![image-20220924214519241](模块B new.assets/image-20220924214519241.png)

![image-20220924214559363](模块B new.assets/image-20220924214559363.png)









## 服务器RouterSrv1上的工作任务

### **1.**   路由功能

#### 安装Remote Access 服务开启路由转发，为当前实验环境提供路由功能。

启用网络地址转换功能，实现内部客户端访问互联网资源。

配置网络地址转换，允许互联网区域客户端访问AppSrv上的HTTP资源。

![image-20220921084947511](E:\笔记\typora\赛\模块B.assets\image-20220921084947511.png)

![image-20220921085027734](E:\笔记\typora\赛\模块B.assets\image-20220921085027734.png)

![image-20220921085222221](E:\笔记\typora\赛\模块B.assets\image-20220921085222221.png)

![image-20220921103110492](E:\笔记\typora\赛\模块B.assets\image-20220921103110492.png)

![image-20220921103217737](E:\笔记\typora\赛\模块B.assets\image-20220921103217737.png)

![image-20220925142520993](模块B new.assets/image-20220925142520993.png)

![image-20220921103414700](E:\笔记\typora\赛\模块B.assets\image-20220921103414700.png)



#### IspSrv地址解析

![image-20220924215813429](模块B new.assets/image-20220924215813429.png)

![image-20220924215855347](模块B new.assets/image-20220924215855347.png)

![image-20220924215925767](模块B new.assets/image-20220924215925767.png)

![image-20220924220021050](模块B new.assets/image-20220924220021050.png)

![image-20220924220049222](模块B new.assets/image-20220924220049222.png)

![image-20220924220123594](模块B new.assets/image-20220924220123594.png)

![image-20220924215306861](模块B new.assets/image-20220924215306861.png)

![image-20220924222629660](模块B new.assets/image-20220924222629660.png)

![image-20220924222653395](模块B new.assets/image-20220924222653395.png)

![image-20220924222712738](模块B new.assets/image-20220924222712738.png)

![image-20220924222536318](模块B new.assets/image-20220924222536318.png)

![image-20220924222730894](模块B new.assets/image-20220924222730894.png)





#### 登录转发

![image-20220924223622970](模块B new.assets/image-20220924223622970.png)

![image-20220924223735344](模块B new.assets/image-20220924223735344.png)

![image-20220924223123127](模块B new.assets/image-20220924223123127.png)

 ![image-20220924224056004](模块B new.assets/image-20220924224056004.png)







### **2.**   **动态地址分配中继服务**

  安装和配置dhcp relay服务，为办公区域网络提供地址上网。

  DHCP服务器位于AppSrv服务器上。

#### 2.1 指定代理网卡

![image-20220918154329235](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220918154329235.png)

![image-20220918154433290](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220918154433290.png)

![image-20220918154454416](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220918154454416.png)

#### 2.2 指定谁提供服务

![image-20220918154719024](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220918154719024.png)

![image-20220918154803727](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220918154803727.png)



### **3.**   **虚拟专用网络**

  设置L2TP/IPSec，IKE通道采用证书进行验证。

  L2TP通道使用chinaskills.com域内用户进行身份验证，仅允许manager组内用户通过身份证验证。

  对于 vpn 客户端，请使用范围 192.168.1.200-192.168.1.220/24。

![image-20220923211408218](模块B new.assets/image-20220923211408218.png)

![image-20220923211453466](模块B new.assets/image-20220923211453466.png)

![image-20220923211716208](模块B new.assets/image-20220923211716208.png)

![image-20220923211859771](模块B new.assets/image-20220923211859771.png)

![image-20220923212122885](模块B new.assets/image-20220923212122885.png)

![image-20220923212541548](模块B new.assets/image-20220923212541548.png)

![image-20220923212747333](模块B new.assets/image-20220923212747333.png)

![image-20220923212818748](模块B new.assets/image-20220923212818748.png)



## 服务器AppSrv上的工作任务

### 加入域

![image-20220919144950386](E:\笔记\typora\赛\模块B.assets\image-20220919144950386.png)



### **1.**   万维网服务

  在RouterSrv1上搭建网站服务器。

  将访问http://www.chinaskills.com的http的请求重定向到https://www.chinaskills.com站点。

  网站内容设置为“该页面为www.chinaskills.com测试页！”。

  将当前web根目录的设置为d:\wwwroot目录。

  启用windows身份验证，只有通过身份验证的用户才能访问到该站点，manager用户组成员使用IE浏览器打开不提示认证，直接访问。

  设置“http://www.chinaskills.com/”网站的最大连接数为1000，网站连接超时为60sl；

  使用W3C记录日志；每天创建一个新的日志文件，文件名格式:

  日志只允许记录日期、时间、客户端IP地址、用户名、服务器IP地址、服务器端口号；

  日志文件存储到“C:\WWWLogFile”目录中；

  IIS（FTP）：

  匿名用户上传的文件都将映射为ftp2用户

  ftp在登录前显示Banner消息：

  “Hello, unauthorized login is prohibited!”

![image-20220919112329797](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220919112329797.png)

![image-20220919112544961](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220919112544961.png)

#### IIS（FTP）

![image-20220921155534658](E:\笔记\typora\赛\模块B new.assets\image-20220921155534658.png)

![image-20220921155604639](E:\笔记\typora\赛\模块B new.assets\image-20220921155604639.png)



#### 将当前web根目录的设置为d:\wwwroot目录。

![image-20220922161258287](模块B new.assets/image-20220922161258287.png)

![image-20220922161344151](模块B new.assets/image-20220922161344151.png)

![image-20220922161425297](模块B new.assets/image-20220922161425297.png)

![image-20220922161445143](模块B new.assets/image-20220922161445143.png)

![image-20220922161738622](模块B new.assets/image-20220922161738622.png)

![image-20220922161837175](模块B new.assets/image-20220922161837175.png)

![image-20220922161852962](模块B new.assets/image-20220922161852962.png)

![image-20220922161908653](模块B new.assets/image-20220922161908653.png)

![image-20220922161932293](模块B new.assets/image-20220922161932293.png)

![image-20220922161947866](模块B new.assets/image-20220922161947866.png)

![image-20220922162119988](模块B new.assets/image-20220922162119988.png)

![image-20220922162204058](模块B new.assets/image-20220922162204058.png)

![image-20220922162226694](模块B new.assets/image-20220922162226694.png)

![image-20220922162313576](模块B new.assets/image-20220922162313576.png)



#### 网站内容设置为“该页面为www.chinaskills.com测试页！”。

![image-20220922162521453](模块B new.assets/image-20220922162521453.png)

![image-20220922162610302](模块B new.assets/image-20220922162610302.png)

![image-20220922162723659](模块B new.assets/image-20220922162723659.png)

![image-20220922162803647](模块B new.assets/image-20220922162803647.png)

![image-20220922162829691](模块B new.assets/image-20220922162829691.png)

![image-20220922162912229](模块B new.assets/image-20220922162912229.png)

![image-20220922163032747](模块B new.assets/image-20220922163032747.png)

![image-20220922163143316](模块B new.assets/image-20220922163143316.png)

![image-20220922163236472](模块B new.assets/image-20220922163236472.png)



#### 

#### 将访问http://www.chinaskills.com的http的请求重定向到https://www.chinaskills.com站点。

![image-20220922163435469](模块B new.assets/image-20220922163435469.png)

![image-20220922163542298](模块B new.assets/image-20220922163542298.png)

![image-20220922164632916](模块B new.assets/image-20220922164632916.png)

![image-20220922164935063](模块B new.assets/image-20220922164935063.png)

![image-20220922164956247](模块B new.assets/image-20220922164956247.png)

![image-20220922165051704](模块B new.assets/image-20220922165051704.png)

![image-20220922165202848](模块B new.assets/image-20220922165202848.png)

![image-20220922165233385](模块B new.assets/image-20220922165233385.png)

![image-20220922165418899](模块B new.assets/image-20220922165418899.png)

![image-20220922165442472](模块B new.assets/image-20220922165442472.png)

![image-20220922165548601](模块B new.assets/image-20220922165548601.png)

![image-20220922165836086](模块B new.assets/image-20220922165836086.png)



#### 启用windows身份验证，只有通过身份验证的用户才能访问到该站点，manager用户组成员使用IE浏览器打开不提示认证，直接访问。

![image-20220922170342266](模块B new.assets/image-20220922170342266.png)

![image-20220922170442740](模块B new.assets/image-20220922170442740.png)

![image-20220922170603061](模块B new.assets/image-20220922170603061.png)

![image-20220922170720819](模块B new.assets/image-20220922170720819.png)

![image-20220922170754813](模块B new.assets/image-20220922170754813.png)

![image-20220922170831786](模块B new.assets/image-20220922170831786.png)

![image-20220922171002206](模块B new.assets/image-20220922171002206.png)

![image-20220922171024957](模块B new.assets/image-20220922171024957.png)

![image-20220922171200913](模块B new.assets/image-20220922171200913.png)



#### 设置“http://www.chinaskills.com/”网站的最大连接数为1000，网站连接超时为60sl；

![image-20220922171423615](模块B new.assets/image-20220922171423615.png)



#### 使用W3C记录日志；每天创建一个新的日志文件，文件名格式:

日志只允许记录日期、时间、客户端IP地址、用户名、服务器IP地址、服务器端口号；

日志文件存储到“C:\WWWLogFile”目录中；

![image-20220922171551581](模块B new.assets/image-20220922171551581.png)

![image-20220922171638604](模块B new.assets/image-20220922171638604.png)

![image-20220922171749164](模块B new.assets/image-20220922171749164.png)

![image-20220922171917942](模块B new.assets/image-20220922171917942.png)

![image-20220922171955531](模块B new.assets/image-20220922171955531.png)



#### IIS（FTP）



![image-20220922172310909](模块B new.assets/image-20220922172310909.png)

![image-20220922172434597](模块B new.assets/image-20220922172434597.png)

![image-20220922172534172](模块B new.assets/image-20220922172534172.png)



#### 匿名用户上传的文件都将映射为ftp2用户

![image-20220922172600427](模块B new.assets/image-20220922172600427.png)

![image-20220922172716442](模块B new.assets/image-20220922172716442.png)

![image-20220922172739785](模块B new.assets/image-20220922172739785.png)



#### ftp在登录前显示Banner消息

ftp在登录前显示Banner消息：

“Hello, unauthorized login is prohibited!”

![image-20220922172814845](模块B new.assets/image-20220922172814845.png)

![image-20220922172931159](模块B new.assets/image-20220922172931159.png)



#### 验证

![image-20220922173053847](模块B new.assets/image-20220922173053847.png)

![image-20220922173220159](模块B new.assets/image-20220922173220159.png)

![image-20220922173248067](模块B new.assets/image-20220922173248067.png)

![image-20220922173308833](模块B new.assets/image-20220922173308833.png)

![image-20220922215809792](模块B new.assets/image-20220922215809792.png)

![image-20220922215932985](模块B new.assets/image-20220922215932985.png)

![image-20220922215942645](模块B new.assets/image-20220922215942645.png)

![image-20220922220108240](模块B new.assets/image-20220922220108240.png)

![image-20220922220308833](模块B new.assets/image-20220922220308833.png)

![image-20220922220202553](模块B new.assets/image-20220922220202553.png)

![image-20220922220419489](模块B new.assets/image-20220922220419489.png)

![image-20220922220541985](模块B new.assets/image-20220922220541985.png)

![image-20220922220553609](模块B new.assets/image-20220922220553609.png)

![image-20220922220730853](模块B new.assets/image-20220922220730853.png)

![image-20220922220944372](模块B new.assets/image-20220922220944372.png)

![image-20220922221015197](模块B new.assets/image-20220922221015197.png)

![image-20220922221024910](模块B new.assets/image-20220922221024910.png)

![image-20220922221112832](模块B new.assets/image-20220922221112832.png)

![image-20220922221502930](模块B new.assets/image-20220922221502930.png)



### **2.**   动态地址分配服务

  安装和配置dhcp服务，为办公区域网络提供地址上网。

  地址池范围：192.168.0.100-192.168.0.200。

![image-20220921150724733](E:\笔记\typora\赛\模块B new.assets\image-20220921150724733.png)

![image-20220921150824967](E:\笔记\typora\赛\模块B new.assets\image-20220921150824967.png)

![image-20220921150914272](E:\笔记\typora\赛\模块B new.assets\image-20220921150914272.png)

![image-20220918155801683](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220918155801683.png)

![image-20220921151027429](E:\笔记\typora\赛\模块B new.assets\image-20220921151027429.png)

![image-20220918160055194](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220918160055194.png)

![image-20220921151137102](E:\笔记\typora\赛\模块B new.assets\image-20220921151137102.png)



### **3.**   DFS

  在AppSrv上安装及配置 DFS 服务。

  目录设置在F：\DFSsharedir。

  配置DFS复制，使用Server03作为次要服务器，复制方式配置为交错拓扑。

  在F：\DFSsharedir 文件夹内新建所有部门的文件夹。

  所有部门的用户之可以访问部门内的文件，不可以跨部门访问别的部门文件夹内容。

  Management用户组用户可以访问全局的文件夹。

![image-20220924141107638](模块B new.assets/image-20220924141107638.png)

![image-20220924141342440](模块B new.assets/image-20220924141342440.png)

![image-20220924141514169](模块B new.assets/image-20220924141514169.png)

![image-20220924141625173](模块B new.assets/image-20220924141625173.png)

![image-20220924141653145](模块B new.assets/image-20220924141653145.png)

![image-20220924141822160](模块B new.assets/image-20220924141822160.png)

![image-20220924141838892](模块B new.assets/image-20220924141838892.png)

![image-20220924141931863](模块B new.assets/image-20220924141931863.png)

![image-20220924142034721](模块B new.assets/image-20220924142034721.png)

![image-20220924142104221](模块B new.assets/image-20220924142104221.png)

![image-20220924142134676](模块B new.assets/image-20220924142134676.png)

![image-20220924142238539](模块B new.assets/image-20220924142238539.png)

![image-20220924142256208](模块B new.assets/image-20220924142256208.png)

![image-20220924142325285](模块B new.assets/image-20220924142325285.png)

![image-20220924142410458](模块B new.assets/image-20220924142410458.png)

![image-20220924142432266](模块B new.assets/image-20220924142432266.png)

![image-20220924142507378](模块B new.assets/image-20220924142507378.png)

![image-20220924142551239](模块B new.assets/image-20220924142551239.png)

![image-20220924142633472](模块B new.assets/image-20220924142633472.png)



  在F：\DFSsharedir 文件夹内新建所有部门的文件夹。

  所有部门的用户之可以访问部门内的文件，不可以跨部门访问别的部门文件夹内容。

  Management用户组用户可以访问全局的文件夹。

![image-20220924142825319](模块B new.assets/image-20220924142825319.png)

![image-20220924143015142](模块B new.assets/image-20220924143015142.png)

![image-20220924143111646](模块B new.assets/image-20220924143111646.png)

![image-20220924143236333](模块B new.assets/image-20220924143236333.png)

![image-20220924143338659](模块B new.assets/image-20220924143338659.png)

![image-20220924143417676](模块B new.assets/image-20220924143417676.png)

![image-20220924143508563](模块B new.assets/image-20220924143508563.png)

![image-20220924143540248](模块B new.assets/image-20220924143540248.png)

![image-20220924143605753](模块B new.assets/image-20220924143605753.png)

![image-20220924143646486](模块B new.assets/image-20220924143646486.png)

![image-20220924143726505](模块B new.assets/image-20220924143726505.png)

![image-20220924143821011](模块B new.assets/image-20220924143821011.png)

![image-20220924143841019](模块B new.assets/image-20220924143841019.png)

![image-20220924144032767](模块B new.assets/image-20220924144032767.png)

![image-20220924144138953](模块B new.assets/image-20220924144138953.png)

![image-20220924144335153](模块B new.assets/image-20220924144335153.png)

![image-20220924144932553](模块B new.assets/image-20220924144932553.png)

![image-20220924145136831](模块B new.assets/image-20220924145136831.png)

![image-20220924152050024](模块B new.assets/image-20220924152050024.png)

![image-20220924152244647](模块B new.assets/image-20220924152244647.png)

 s



### **4.**   磁盘管理

  在安装好的**AppSrv**虚拟机中添加三块10G虚拟磁盘。

  组成RAID5，磁盘分区命名为卷标F盘：Raid5。

  手动测试破坏一块磁盘，做RAID磁盘修复；确认RAID5配置完毕。

![image-20220921190523199](E:\笔记\typora\赛\模块B new.assets\image-20220921190523199.png)

![image-20220920083906941](E:\笔记\typora\赛\模块B.assets\image-20220920083906941.png)

![image-20220921190903458](E:\笔记\typora\赛\模块B new.assets\image-20220921190903458.png)

![image-20220921190947521](E:\笔记\typora\赛\模块B new.assets\image-20220921190947521.png)

![image-20220921191006711](E:\笔记\typora\赛\模块B new.assets\image-20220921191006711.png)





![image-20220921191050655](E:\笔记\typora\赛\模块B new.assets\image-20220921191050655.png)

![image-20220921191113082](E:\笔记\typora\赛\模块B new.assets\image-20220921191113082.png)

![image-20220921191153260](E:\笔记\typora\赛\模块B new.assets\image-20220921191153260.png)

![image-20220921191321753](E:\笔记\typora\赛\模块B new.assets\image-20220921191321753.png)

![image-20220921191433272](E:\笔记\typora\赛\模块B new.assets\image-20220921191433272.png)

![image-20220921191458334](E:\笔记\typora\赛\模块B new.assets\image-20220921191458334.png)

![image-20220921191602125](E:\笔记\typora\赛\模块B new.assets\image-20220921191602125.png)





### **5.**   DNS

  安装DNS服务器，根据题目创建必要的DNS解析。

  把当前机器作为互联网根域服务器。

![image-20220924214921758](模块B new.assets/image-20220924214921758.png)

![image-20220924215154503](模块B new.assets/image-20220924215154503.png)



## 服务器DC1&DC2上的工作任务

### **1.**   活动目录域服务

  在DC1和DC2服务器上安装活动目录域服务，DC1作为主域控，DC2作为备份域控，活动目录域名为：chinaskills.com。

  域用户能够使用[username]@csk.cn进行登录。

  创建一个名为“CSK”的OU，并新建以下域用户和组：

 sa01-sa20，请将该用户添加到sales用户组。

 it01-it20，请将该用户添加到IT用户组。

 ma01-ma10，请将该用户添加到manager用户组。

​		  许除manager 组和IT组，所有用户隐藏C盘。

​		  除manager 组和IT组，所有普通给用户禁止使用cmd。

  禁止客户端电脑显示用户首次登录动画。

  所有用户的IE浏览器首页设置为“https://www.chinaskills.com”。

  所有用户都应该收到登录提示信息：标题“登录安全提示：”，内容“禁止非法用户登录使用本计算机。”。

  设置所有主机的登录Banner：

 标题为“CHINASKILLS-DOMAIN”；

 内容为“Hello, unauthorized login is prohibited!”。

  域内的所有计算机（除dc外），当dc服务器不可用时，禁止使用缓存登录。

  启用AD回收站功能。

#### 一定要先加域，后装CA

#### 将DC1做成主域

![image-20220921110726443](E:\笔记\typora\赛\模块B new.assets\image-20220921110726443.png)

![image-20220921152150057](E:\笔记\typora\赛\模块B new.assets\image-20220921152150057.png)

![image-20220921152224245](E:\笔记\typora\赛\模块B new.assets\image-20220921152224245.png)

![image-20220921152912425](E:\笔记\typora\赛\模块B new.assets\image-20220921152912425.png)

![image-20220921160102789](E:\笔记\typora\赛\模块B new.assets\image-20220921160102789.png)

![image-20220921160153813](E:\笔记\typora\赛\模块B new.assets\image-20220921160153813.png)

![image-20220921160443531](E:\笔记\typora\赛\模块B new.assets\image-20220921160443531.png)

![image-20220921160624250](E:\笔记\typora\赛\模块B new.assets\image-20220921160624250.png)

#### 各主机加入域内

![image-20220921165533723](E:\笔记\typora\赛\模块B new.assets\image-20220921165533723.png)

![image-20220921165700673](E:\笔记\typora\赛\模块B new.assets\image-20220921165700673.png)

![image-20220921165943031](E:\笔记\typora\赛\模块B new.assets\image-20220921165943031.png)

![image-20220921170110095](E:\笔记\typora\赛\模块B new.assets\image-20220921170110095.png)



AppSrv、RouterSrv、InsideCli 截图略

#### 将DC2做成副域

![image-20220921181706618](E:\笔记\typora\赛\模块B new.assets\image-20220921181706618.png)

![image-20220921183646694](E:\笔记\typora\赛\模块B new.assets\image-20220921183646694.png)

![image-20220921183801898](E:\笔记\typora\赛\模块B new.assets\image-20220921183801898.png)

![image-20220921184122642](E:\笔记\typora\赛\模块B new.assets\image-20220921184122642.png)

![image-20220925174241474](模块B new.assets/image-20220925174241474.png)



####   域用户能够使用[username]@csk.cn进行登录。

##### 添加UPN

![image-20220921195334480](模块B new.assets/image-20220921195334480-16637612152531.png)

![image-20220921195437491](模块B new.assets/image-20220921195437491.png)

![image-20220921195523097](模块B new.assets/image-20220921195523097.png)



##### 添加用户

![image-20220921195615540](模块B new.assets/image-20220921195615540.png)

![image-20220921195939473](模块B new.assets/image-20220921195939473.png)



#### CMD脚本添加到用户

```shell
for /L %a in (1,1,9) do net user sa0%a ChinaSkill22! /add /domain

for /L %a in (1,1,9) do net user it0%a ChinaSkill22! /add /domain

for /L %a in (1,1,10) do net user ma0%a ChinaSkill22! /add /domain

for /L %a in (10,1,20) do net user sa%a ChinaSkill22! /add /domain

for /L %a in (10,1,20) do net user it%a ChinaSkill22! /add /domain

```



![image-20220921201037178](模块B new.assets/image-20220921201037178.png)

![image-20220921201103947](模块B new.assets/image-20220921201103947.png)

![image-20220921201257268](模块B new.assets/image-20220921201257268.png)

![image-20220921201514534](模块B new.assets/image-20220921201514534.png)

![image-20220921201604022](模块B new.assets/image-20220921201604022.png)

![image-20220921201619971](模块B new.assets/image-20220921201619971.png)

![image-20220921201651425](模块B new.assets/image-20220921201651425.png)

![image-20220921201729308](模块B new.assets/image-20220921201729308.png)



![image-20220921202021599](模块B new.assets/image-20220921202021599.png)

![image-20220921202053471](模块B new.assets/image-20220921202053471.png)

![image-20220921202812996](模块B new.assets/image-20220921202812996.png)



![image-20220921211837549](模块B new.assets/image-20220921211837549.png)![image-20220921211948777](模块B new.assets/image-20220921211948777.png)

![image-20220921212040683](模块B new.assets/image-20220921212040683.png)

![image-20220921212136471](模块B new.assets/image-20220921212136471.png)

![image-20220921212208174](模块B new.assets/image-20220921212208174.png)

![image-20220921212303861](模块B new.assets/image-20220921212303861.png)

![image-20220921212351034](模块B new.assets/image-20220921212351034.png)

![image-20220921212421878](模块B new.assets/image-20220921212421878.png)

![image-20220921212509569](模块B new.assets/image-20220921212509569.png)

![image-20220921212709292](模块B new.assets/image-20220921212709292.png)

##### 许除manager 组和IT组，所有用户隐藏C盘。

![image-20220921212732799](模块B new.assets/image-20220921212732799.png)

##### 除manager 组和IT组，所有普通给用户禁止使用cmd。

![image-20220921213034026](模块B new.assets/image-20220921213034026.png)

![image-20220921213130335](模块B new.assets/image-20220921213130335.png)

![image-20220921213316598](模块B new.assets/image-20220921213316598.png)

![image-20220921213253699](模块B new.assets/image-20220921213253699-16637671750164.png)

![image-20220921213422456](模块B new.assets/image-20220921213422456.png)

![image-20220921213501644](模块B new.assets/image-20220921213501644.png)

##### 禁止客户端电脑显示用户首次登录动画。

![image-20220921213654800](模块B new.assets/image-20220921213654800.png)

![image-20220921213725253](模块B new.assets/image-20220921213725253.png)

![image-20220921213806536](模块B new.assets/image-20220921213806536.png)

![image-20220921213835378](模块B new.assets/image-20220921213835378.png)

![image-20220921213902470](模块B new.assets/image-20220921213902470.png)

![image-20220921213939519](模块B new.assets/image-20220921213939519.png)

![image-20220921214138863](模块B new.assets/image-20220921214138863.png)

![image-20220921214844471](模块B new.assets/image-20220921214844471.png)

![image-20220921214716151](模块B new.assets/image-20220921214716151.png)

![image-20220921214740049](模块B new.assets/image-20220921214740049.png)

![image-20220921214801336](模块B new.assets/image-20220921214801336.png)

![image-20220921214813784](模块B new.assets/image-20220921214813784.png)

##### 所有用户的IE浏览器首页设置为“https://www.chinaskills.com”。

![image-20220921215048286](模块B new.assets/image-20220921215048286.png)

![image-20220921215241380](模块B new.assets/image-20220921215241380.png)

![image-20220921215334723](模块B new.assets/image-20220921215334723.png)

![image-20220921215403285](模块B new.assets/image-20220921215403285.png)

##### 所有用户都应该收到登录提示信息：标题“登录安全提示：”，内容“禁止非法用户登录使用本计算机。”。

  设置所有主机的登录Banner：

 标题为“CHINASKILLS-DOMAIN”；

 内容为“Hello, unauthorized login is prohibited!”。

![image-20220921215805020](模块B new.assets/image-20220921215805020.png)

![image-20220921215919238](模块B new.assets/image-20220921215919238.png)

![image-20220921220102320](模块B new.assets/image-20220921220102320.png)



##### 域内的所有计算机（除dc外），当dc服务器不可用时，禁止使用缓存登录。

![image-20220921220220768](模块B new.assets/image-20220921220220768.png)



##### 启用AD回收站功能。

![image-20220921220306816](模块B new.assets/image-20220921220306816.png)

![image-20220921220353465](模块B new.assets/image-20220921220353465.png)

![image-20220921220420785](模块B new.assets/image-20220921220420785.png)

![image-20220921220429850](模块B new.assets/image-20220921220429850.png)

![image-20220921220448175](模块B new.assets/image-20220921220448175.png)

![image-20220921220516243](模块B new.assets/image-20220921220516243.png)





### 2.   NPS（网络策略服务）

  在DC1上安装网络策略服务作为VPN用户登录验证。

  仅允许L2TP/IPSEC VPN进行VPN连接访问验证。

  认证、授权日志将存储到DC1上的“C:\NPS\”目录下。

![image-20220923213123992](模块B new.assets/image-20220923213123992.png)

![image-20220923213231680](模块B new.assets/image-20220923213231680.png)

![image-20220923213326615](模块B new.assets/image-20220923213326615.png)

![image-20220923213418967](模块B new.assets/image-20220923213418967.png)

![image-20220923213509450](模块B new.assets/image-20220923213509450.png)

![image-20220923213607245](模块B new.assets/image-20220923213607245.png)

![image-20220923213651175](模块B new.assets/image-20220923213651175.png)

![image-20220923214040694](模块B new.assets/image-20220923214040694.png)

![image-20220923214121345](模块B new.assets/image-20220923214121345.png)

![image-20220923214154022](模块B new.assets/image-20220923214154022.png)

![image-20220923214239959](模块B new.assets/image-20220923214239959.png)

![image-20220923214321522](模块B new.assets/image-20220923214321522.png)

![image-20220923214348956](模块B new.assets/image-20220923214348956.png)

![image-20220923214423010](模块B new.assets/image-20220923214423010.png)

![image-20220923214722700](模块B new.assets/image-20220923214722700.png)

![image-20220923214750843](模块B new.assets/image-20220923214750843.png)

![image-20220923214858239](模块B new.assets/image-20220923214858239.png)

![image-20220923214938326](模块B new.assets/image-20220923214938326.png)

![image-20220923215001235](模块B new.assets/image-20220923215001235.png)

![image-20220923215049788](模块B new.assets/image-20220923215049788.png)

![image-20220923215113290](模块B new.assets/image-20220923215113290.png)



  仅允许L2TP/IPSEC VPN进行VPN连接访问验证。

#### 认证、授权日志将存储到DC1上的“C:\NPS\”目录下。

![image-20220923215414548](模块B new.assets/image-20220923215414548.png)

![image-20220923215434924](模块B new.assets/image-20220923215434924.png)

![image-20220923215655399](模块B new.assets/image-20220923215655399.png)

![image-20220923215750161](模块B new.assets/image-20220923215750161.png)

![image-20220923215840246](模块B new.assets/image-20220923215840246.png)

![image-20220923215952278](模块B new.assets/image-20220923215952278.png)

![image-20220923220011096](模块B new.assets/image-20220923220011096.png)

![image-20220923220100051](模块B new.assets/image-20220923220100051.png)

![image-20220923220140795](模块B new.assets/image-20220923220140795.png)

![image-20220923220153880](模块B new.assets/image-20220923220153880.png)



#### OutsideCli 设备流程

![image-20220923220315253](模块B new.assets/image-20220923220315253.png)

![image-20220923220516665](模块B new.assets/image-20220923220516665.png)

![image-20220923220744997](模块B new.assets/image-20220923220744997.png)

![image-20220923220842466](模块B new.assets/image-20220923220842466.png)

![image-20220923220936698](模块B new.assets/image-20220923220936698.png)

![image-20220923221007945](模块B new.assets/image-20220923221007945.png)

![image-20220923221022418](模块B new.assets/image-20220923221022418.png)

![image-20220923221055547](模块B new.assets/image-20220923221055547.png)

![image-20220923221125763](模块B new.assets/image-20220923221125763.png)

![image-20220923221225601](模块B new.assets/image-20220923221225601.png)

![image-20220923221416789](模块B new.assets/image-20220923221416789.png)

![image-20220923221429713](模块B new.assets/image-20220923221429713.png)

![image-20220923221456684](模块B new.assets/image-20220923221456684.png)

![image-20220923221537748](模块B new.assets/image-20220923221537748.png)

![image-20220923221557881](模块B new.assets/image-20220923221557881.png)



### 3.DNS（域名解析服务）

  拓扑中所有主机的DNS查询请求都应由IspSrv进行解析。

![image-20220921135144495](E:\笔记\typora\赛\模块B new.assets\image-20220921135144495.png)

![image-20220921135209574](E:\笔记\typora\赛\模块B new.assets\image-20220921135209574.png)

![image-20220921140114875](E:\笔记\typora\赛\模块B new.assets\image-20220921140114875.png)

![image-20220919104026463](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220919104026463.png)



### **4.**   证书颁发机构

  在DC1服务器上安装证书办法机构。

  定义名称：CSK2021-ROOTCA。

  证书颁发机构有效期：3 years。

  为chinaskills.com域内的web站点颁发web证书。

  当前拓扑内所有机器必须信任该证书颁发机构。（域自动广播，自动做好了）

  所域内所有计算机自动颁发一张计算机证书。（做完这步，才能弄VPN、打印机）

![image-20220921193641343](E:\笔记\typora\赛\模块B new.assets\image-20220921193641343.png)

![image-20220921193736474](E:\笔记\typora\赛\模块B new.assets\image-20220921193736474.png)

![image-20220921194249848](E:\笔记\typora\赛\模块B new.assets\image-20220921194249848.png)

![image-20220921194340616](E:\笔记\typora\赛\模块B new.assets\image-20220921194340616.png)

![image-20220921194431643](E:\笔记\typora\赛\模块B new.assets\image-20220921194431643.png)

![image-20220921194559621](模块B new.assets/image-20220921194559621.png)

![image-20220921194819969](模块B new.assets/image-20220921194819969.png)



#### 所域内所有计算机自动颁发一张计算机证书。（做完这步，才能弄VPN、打印机）

![image-20220921203020537](模块B new.assets/image-20220921203020537.png)

![image-20220921203148650](模块B new.assets/image-20220921203148650.png)

![image-20220921203306443](模块B new.assets/image-20220921203306443.png)

![image-20220921203357426](模块B new.assets/image-20220921203357426.png)

![image-20220921203444253](模块B new.assets/image-20220921203444253.png)

![image-20220921203650557](模块B new.assets/image-20220921203650557.png)

![image-20220921203721475](模块B new.assets/image-20220921203721475.png)

![image-20220921203755192](模块B new.assets/image-20220921203755192.png)

![image-20220921203840535](模块B new.assets/image-20220921203840535.png)



##### 制作模板

![image-20220921204027692](模块B new.assets/image-20220921204027692.png)

![image-20220921204129239](模块B new.assets/image-20220921204129239.png)

![image-20220921204216567](模块B new.assets/image-20220921204216567.png)

![image-20220921204403894](模块B new.assets/image-20220921204403894.png)

![image-20220921204506363](模块B new.assets/image-20220921204506363.png)

![image-20220921204640879](模块B new.assets/image-20220921204640879.png)

![image-20220921204755517](模块B new.assets/image-20220921204755517.png)

![image-20220921204813129](模块B new.assets/image-20220921204813129.png)



##### 发行模板

![image-20220921205027320](模块B new.assets/image-20220921205027320.png)

![image-20220921205112342](模块B new.assets/image-20220921205112342.png)

![image-20220921205329972](模块B new.assets/image-20220921205329972.png)

![image-20220921205540534](模块B new.assets/image-20220921205540534.png)

![image-20220921205825788](模块B new.assets/image-20220921205825788.png)

![image-20220921205729910](模块B new.assets/image-20220921205729910.png)

![image-20220921205903492](模块B new.assets/image-20220921205903492.png)

![image-20220921205937900](模块B new.assets/image-20220921205937900.png)

![image-20220921210035565](模块B new.assets/image-20220921210035565-16637652361892.png)

![image-20220921210133421](模块B new.assets/image-20220921210133421.png)

![image-20220921211329866](模块B new.assets/image-20220921211329866.png)

![image-20220921211459502](模块B new.assets/image-20220921211459502.png)

![image-20220921211631277](模块B new.assets/image-20220921211631277.png)





### **5.**   文件共享

  创建用户主目录共享文件夹：

  本地目录为F:\share\users\，允许所有域用户可读可写。在本目录下为所有用户添加一个以名称命名的文件夹，该文件夹将设置为所有域用户的home目录，用户登录计算机成功后，自动映射挂载到H卷。

  禁止用户在该共享文件中创建“*.exe, *.bat, *.sh”文件。

  创建manager组共享文件夹：

  本地目录为F:\ share\managers，仅允许manager用户组成员拥有写入权限，该共享文件对其他组成员不可见。

  创建public-share公共共享文件夹：

  本地目录为F:\ share\public-share，仅允许manager用户组成员拥有写入权限，其他认证用户只读权限。

![image-20220923100604542](模块B new.assets/image-20220923100604542.png)

![image-20220923100740932](模块B new.assets/image-20220923100740932.png)



#### 本地目录为F:\share\users\，允许所有域用户可读可写。

![image-20220923101124007](模块B new.assets/image-20220923101124007.png)

![image-20220923103951212](模块B new.assets/image-20220923103951212.png)

![image-20220923104117416](模块B new.assets/image-20220923104117416.png) 

![image-20220923104221048](模块B new.assets/image-20220923104221048.png)

![image-20220923104334792](模块B new.assets/image-20220923104334792.png)

![image-20220923104448823](模块B new.assets/image-20220923104448823.png)

![image-20220923104526730](模块B new.assets/image-20220923104526730.png)

![image-20220923134737873](模块B new.assets/image-20220923134737873.png)

![image-20220923134756126](模块B new.assets/image-20220923134756126.png)

![image-20220923134811053](模块B new.assets/image-20220923134811053.png)

![image-20220923135937576](模块B new.assets/image-20220923135937576.png)



#### 在本目录下为所有用户添加一个以名称命名的文件夹，该文件夹将设置为所有域用户的home目录，用户登录计算机成功后，自动映射挂载到H卷。

![image-20220923140735136](模块B new.assets/image-20220923140735136.png)

![image-20220923140807539](模块B new.assets/image-20220923140807539.png)

![image-20220923141242725](模块B new.assets/image-20220923141242725.png)

![image-20220923193505738](模块B new.assets/image-20220923193505738.png)

![image-20220923193633420](模块B new.assets/image-20220923193633420.png)



#### 禁止用户在该共享文件中创建“*.exe, *.bat, *.sh”文件。

![image-20220923194234453](模块B new.assets/image-20220923194234453.png)

![image-20220923194350599](模块B new.assets/image-20220923194350599.png)

![image-20220923200136428](模块B new.assets/image-20220923200136428.png)

![image-20220923200205560](模块B new.assets/image-20220923200205560.png)

![image-20220923200337550](模块B new.assets/image-20220923200337550.png)

![image-20220923200419212](模块B new.assets/image-20220923200419212.png)

![image-20220923200448995](模块B new.assets/image-20220923200448995.png)

![image-20220923200604578](模块B new.assets/image-20220923200604578.png)

![image-20220923200702430](模块B new.assets/image-20220923200702430.png)

![image-20220923200724632](模块B new.assets/image-20220923200724632.png)

![image-20220923201048896](模块B new.assets/image-20220923201203492.png)

![image-20220923201225673](模块B new.assets/image-20220923201225673.png)

![image-20220923201248492](模块B new.assets/image-20220923201248492.png)

![image-20220923201338096](模块B new.assets/image-20220923201338096.png)

![](模块B new.assets/image-20220923201534045.png)

![image-20220923201645580](模块B new.assets/image-20220923201645580.png)

![image-20220923201734979](模块B new.assets/image-20220923201734979.png)



#### 本地目录为F:\ share\managers，仅允许manager用户组成员拥有写入权限，该共享文件对其他组成员不可见。

![image-20220923203049023](模块B new.assets/image-20220923203049023.png)

![image-20220923203117811](模块B new.assets/image-20220923203117811.png)

![image-20220923203138325](模块B new.assets/image-20220923203138325.png)

![image-20220923203202921](模块B new.assets/image-20220923203202921.png)

![image-20220923203217910](模块B new.assets/image-20220923203217910.png)

![image-20220923203314751](模块B new.assets/image-20220923203314751.png)

![image-20220923203343606](模块B new.assets/image-20220923203343606.png)

![image-20220923203520463](模块B new.assets/image-20220923203520463.png)



#### 创建public-share公共共享文件夹

本地目录为F:\ share\public-share，仅允许manager用户组成员拥有写入权限，其他认证用户只读权限。

![image-20220923203620116](模块B new.assets/image-20220923203620116.png)

![image-20220923204442477](模块B new.assets/image-20220923204442477.png)

![image-20220923204711939](模块B new.assets/image-20220923204711939.png)

![image-20220923204834159](模块B new.assets/image-20220923204834159.png)

![image-20220923204847733](模块B new.assets/image-20220923204847733.png)

![image-20220923204944208](模块B new.assets/image-20220923204944208.png)

![image-20220923205103457](模块B new.assets/image-20220923205103457.png)

![image-20220923205143000](模块B new.assets/image-20220923205143000.png)

![image-20220923205240120](模块B new.assets/image-20220923205240120.png)









## 客户端InsideCli上的工作任务

  按照要求将该主机加入到对应区域的域。

  设置电源配置，以便客户端在通电的情况下，永不进入睡眠。

  该客户端用于测试用户登录，Profiles，文件共享，安全策略和RDS等功能。



### 设置电源配置，以便客户端在通电的情况下，永不进入睡眠。

![image-20220924224213565](模块B new.assets/image-20220924224213565.png)

![image-20220924224251305](模块B new.assets/image-20220924224251305.png)

![image-20220924224306443](模块B new.assets/image-20220924224306443.png)

![image-20220924224550100](模块B new.assets/image-20220924224550100.png)

![image-20220924224958021](模块B new.assets/image-20220924224958021.png)





## 客户端OutsideCli上的工作任务

  该主机不允许加入域。

  添加一个名为Connect-CSK 的VPN拨号器，用于连接到chinaskills.com域网络，不记录用户名称密码信息。

  设置电源配置，以便客户端在通电的情况下，永不进入睡眠。

  该客户端用于测试用户登录，Profiles，文件共享，安全策略和RDS等功能。



### 添加一个名为Connect-CSK 的VPN拨号器，用于连接到chinaskills.com域网络，不记录用户名称密码信息。

![image-20220923221709786](模块B new.assets/image-20220923221709786.png)

![image-20220923221733236](模块B new.assets/image-20220923221733236.png)

![image-20220923222010732](模块B new.assets/image-20220923222010732.png)

![image-20220923222139148](模块B new.assets/image-20220923222139148.png)

![image-20220923222234289](模块B new.assets/image-20220923222234289.png)

![image-20220923222255534](模块B new.assets/image-20220923222255534.png)

![image-20220923222336064](模块B new.assets/image-20220923222336064.png)

![image-20220923222436658](模块B new.assets/image-20220923222436658.png)

![image-20220923222508423](模块B new.assets/image-20220923222508423.png)

![image-20220923222525301](模块B new.assets/image-20220923222525301.png)

![image-20220923222544954](模块B new.assets/image-20220923222544954.png)

![image-20220923222620986](模块B new.assets/image-20220923222620986.png)

![image-20220923222705080](模块B new.assets/image-20220923222705080.png)

![image-20220923222815125](模块B new.assets/image-20220923222815125.png)













 

## 开着防火墙，启用ping功能

#### 启用/禁用的A位置

![image-20220918160730412](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220918160730412.png)

![image-20220918160814381](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220918160814381.png)

![image-20220918160827266](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220918160827266.png)



#### 启用/禁用的B位置

![image-20220918161057998](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220918161057998.png)

![image-20220918161124682](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220918161124682.png)

![image-20220918161134725](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220918161134725.png)

![image-20220918161155055](C:\Users\26325\AppData\Roaming\Typora\typora-user-images\image-20220918161155055.png)

