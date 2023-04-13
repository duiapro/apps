
[//]: # (### 🔗友情链接 （所有软件免费下载,可自行签名可签网盘所有IOS软件）)

### 🎦脚本说明

- 
- 🚀把 NewReinstall.sh 上传到/root目录 ，执行 chmod a+x NewReinstall.sh && bash NewReinstall.sh
 安装重装系统的前提组件:

 ### Debian/Ubuntu:
 apt-get install -y xz-utils openssl gawk file wget screen && screen -S os

### RedHat/CentOS:
yum install -y xz openssl gawk file glibc-common wget screen && screen -S os
如果出现异常，请刷新Mirrors缓存或更换镜像源。

### RedHat/CentOS:
yum makecache && yum update -y

- 🚀 Debian/Ubuntu:
apt update -y && apt dist-upgrade -y
DD脚本使用:
wget --no-check-certificate -O NewReinstall.sh https://git.io/newbetags && chmod a+x NewReinstall.sh && bash NewReinstall.sh

## 如为CN主机(部分主机商已不能使用)，可能出现报错或不能下载脚本的问题，可执行以下命令开始安装.
wget --no-check-certificate -O NewReinstall.sh https://cdn.jsdelivr.net/gh/fcurrk/reinstall@master/NewReinstall.sh && chmod a+x NewReinstall.sh && bash NewReinstall.sh

41合1的系统一键DD选择界面，输入99则使用自定义镜像。 以上系统密码不为默认密码的均为网络收集，如有疑虑使用自己的自定义镜像。
41合一系统密码：
1、CentOS 7.7 (已关闭防火墙及SELinux，默认密码Pwd@CentOS)
2、CentOS 7 (默认密码cxthhhhh.com)
3、CentOS 7 (支持ARM64、UEFI，默认密码cxthhhhh.com)
4、CentOS 8 (默认密码cxthhhhh.com)
5、Rocky 8 (默认密码cxthhhhh.com)
6、Rocky 8 (支持UEFI，默认密码cxthhhhh.com)
7、Rocky 8 (支持ARM64、UEFI，默认密码cxthhhhh.com)
8、CentOS 9 (默认密码cxthhhhh.com)
9、CentOS 6 (官方源原版，默认密码Minijer.com)
10、Debian 11 (官方源原版，默认密码Minijer.com)
11、Debian 10 (官方源原版，默认密码Minijer.com)
12、Debian 9 (官方源原版，默认密码Minijer.com)
13、Debian 8 (官方源原版，默认密码Minijer.com)
14、Ubuntu 20.04 (官方源原版，默认密码Minijer.com)
15、Ubuntu 18.04 (官方源原版，默认密码Minijer.com)
16、Ubuntu 16.04 (官方源原版，默认密码Minijer.com)
17、Windows Server 2022 (默认密码cxthhhhh.com)
18、Windows Server 2022 (支持UEFI，默认密码cxthhhhh.com)
19、Windows Server 2019 (默认密码cxthhhhh.com)
20、Windows Server 2016 (默认密码cxthhhhh.com)
21、Windows Server 2012 (默认密码cxthhhhh.com)
22、Windows Server 2008 (默认密码cxthhhhh.com)
23、Windows Server 2003 (默认密码cxthhhhh.com)
24、Windows 10 LTSC (默认密码Teddysun.com)
25、Windows 10 LTSC (支持UEFI，默认密码Teddysun.com)
26、Windows 7 x86 Lite (默认密码nat.ee)
27、Windows 7 x86 Lite (阿里云专用，默认密码nat.ee)
28、Windows 7 x64 Lite (默认密码nat.ee)
29、Windows 7 x64 Lite (支持UEFI，默认密码nat.ee)
30、Windows 10 LTSC Lite (默认密码nat.ee)
31、Windows 10 LTSC Lite (阿里云专用，默认密码nat.ee)
32、Windows 10 LTSC Lite (支持UEFI，默认密码nat.ee)
33、Windows Server 2003 Lite (C盘默认10G，默认密码WinSrv2003x86-Chinese)
34、Windows Server 2008 Lite (默认密码nat.ee)
35、Windows Server 2008 Lite (支持UEFI，默认密码nat.ee)
36、Windows Server 2012 Lite (默认密码nat.ee)
37、Windows Server 2012 Lite (支持UEFI，默认密码nat.ee)
38、Windows Server 2016 Lite (默认密码nat.ee)
39、Windows Server 2016 Lite (支持UEFI，默认密码nat.ee)
40、Windows Server 2022 Lite (默认密码nat.ee)
41、Windows Server 2022 Lite (支持UEFI，默认密码nat.ee)
99、自定义镜像

注意：
系统名称后带Lite的均为精简版，没有的是完整版.
[X64-Legacy-cxthhhhh]代表系统为AMD64位，支持传统BIOS启动，cxthhhhh定制的系统镜像.
ARM64代表系统支持ARM64位
UEFI代表系统支持最新的UEFI启动，如甲骨文全部都是这种
aliyun代表阿里云专用系统镜像
cxthhhhh、teddysun、nat.ee均为三位制作系统镜像的大佬代称
系统密码会在选择相应序号后提示，请注意记录。
经测试在谷歌云原版系统基础上DD会出现自动获取的子网掩码为255.255.255.255,如出现这种情况需要手工输入改正为正确的如255.255.255.0,否则会安装完成主机可能会离线。
阿里云因使用了特殊的驱动，DD安装Windows系统选择阿里云专用版。

Oracle Cloud（甲骨文云）可选择支持UEFI的镜像，注意基础系统最好选择Ubuntu，如原系统是CentOS可能无法成功，注意如是ARM机器注意选择同时支持ARM64和UEFI的镜像。

9-16项安装原版系统，可自定义密码，密码要求8-16位，以英文字母或数字开头，可以是大小写英文字母、数字及7个特殊字符.!$@#&%的任意组合。


### ☁️DUIA™网盘 - 更全更快速的资源分享站

- 🚀 超高速下载，不限速下载
- ❤ 本站资源来自互联网收集,仅供用于学习和交流,请勿用于商业用途。
- 🌻 如有侵权、不妥之处,请联系站长并出示版权证明以便删除。敬请谅解! 
- 🌶️ 仅苹果、电脑资源
- 💰 整合资源不易，请多多支持



[//]: # (### 🍊加入QQ群-[点击跳转]&#40;https://qm.qq.com/cgi-bin/qm/qr?k=bbEv_sez5-j5YmSPaWRAZjPcBqqWIncm&jump_from=webapi/&#41;)