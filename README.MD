### TunSafe VPN 一款基于WireGuard 协议的VPN------2018-12-11  TunSafe 测试已挂，估计被封了--

#### 目前很多反馈安装过程也需要科学的。我给大家一个临时解决方案，在目录chromeExtensions 下上传了一个1.0.4_0.crx chrome扩展程序，安装后可实现科学。(2020-02-26)

~~首先贴上TunSafe在TestFlight上的地址：  https://testflight.apple.com/join/9gbYAJLB~~

 在Installer目录下有TunSafe-1.4.exe 安装包，大家可以下载安装。    

下面写一下TunSafe VPN 在Windows 下的安装步骤，轻松实现科学上网：    
TunSafe 官网：https://tunsafe.com    WireGuard官网： https://www.wireguard.com    

1、首先从TunSafe 官网下载安装文件，如下图：    
![Image 下载文件](https://github.com/liweiDiao/WireGuard/blob/master/image/0.png)    

2、打开安装文件，选择I Agree ,如下图：    
 ![Image 步骤1](https://github.com/liweiDiao/WireGuard/blob/master/image/1.png)    

3、选择Next    
![Image 步骤2](https://github.com/liweiDiao/WireGuard/blob/master/image/2.png)    

4、选择安装路径：    
![Image 步骤3](https://github.com/liweiDiao/WireGuard/blob/master/image/3.png)    

5、等待安装完成，选Close：    
![Image 步骤4](https://github.com/liweiDiao/WireGuard/blob/master/image/4.png)    

6、安装成功的界面如图所示：    
![Image 步骤5](https://github.com/liweiDiao/WireGuard/blob/master/image/5.png)    

7、TunSafe提供了免费VPN服务器方便我们使用，所以接下来我们生成VPN服务器的配置文件。将下图中的第一个选项（First Server/第一台服务器）下面的7个选项依次选中然后选择按钮（Generate and Download/生成和下载）    
![Image 步骤6](https://github.com/liweiDiao/WireGuard/blob/master/image/6.png)    
![Image 步骤7](https://github.com/liweiDiao/WireGuard/blob/master/image/7.png)    

8、将下载好的7个文件，复制到TunSafe的安装目录下的Config文件夹下，同时将Config目录下默认的文件TunSafe.conf文件删除掉，如图：    
![Image 步骤8](https://github.com/liweiDiao/WireGuard/blob/master/image/8.png)    
![Image 步骤9](https://github.com/liweiDiao/WireGuard/blob/master/image/10.png)    

9、然后切换到TunSafe 软件的界面上，选项下拉会出现刚才7个配置文件的选项，然后我们选择其中一个，然后Reconnect。如图：    
![Image 步骤10](https://github.com/liweiDiao/WireGuard/blob/master/image/11.png)    
![Image 步骤11](https://github.com/liweiDiao/WireGuard/blob/master/image/12.png)    

10、到这里科学上网已经实现了，我们测试一下，打开浏览器访问www.youtube.com，查看视频速度还是挺快的。如图：
![Image 步骤12](https://github.com/liweiDiao/WireGuard/blob/master/image/13.png)    
![Image 步骤13](https://github.com/liweiDiao/WireGuard/blob/master/image/14.png)    


### 二、ipad使用示例，美区appid直接搜索tunsafe    
![Image 步骤14](https://github.com/liweiDiao/WireGuard/blob/master/image/IMG_1498.PNG)    
 
 1、正常打开是下面这样    
 ![Image 步骤14](https://github.com/liweiDiao/WireGuard/blob/master/image/IMG_1499.PNG)    
 
 2、查看设置，设置里面可以选择节点文件（如果自己有文件，这里设置后能直接选择自己的节点科学上网）      
 ![Image 步骤15](https://github.com/liweiDiao/WireGuard/blob/master/image/IMG_1500.PNG)    
 
 ![Image 步骤16](https://github.com/liweiDiao/WireGuard/blob/master/image/IMG_1501.PNG)    

 3、可惜的是，不科学上网，当前没有节点可以选择。如下图（正常国内网络）    
 ![Image 步骤17](https://github.com/liweiDiao/WireGuard/blob/master/image/IMG_1504.PNG)    
 
 4、在进行科学上网后，再重新打开app如下图，出现很多节点。    
 ![Image 步骤18](https://github.com/liweiDiao/WireGuard/blob/master/image/IMG_1508.PNG)   
 
 
 ![Image 步骤19](https://github.com/liweiDiao/WireGuard/blob/master/image/IMG_1505.png)   
 
 5、选择美国节点后，选择连接，连接成功。     
 ![Image 步骤20](https://github.com/liweiDiao/WireGuard/blob/master/image/IMG_1507.png)   
 
 
