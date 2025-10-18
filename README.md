# 找一找，记一记，写一写，存一存 2025.10.8.0018
</p>----------------------------------------------------------------------------------------------------------------</p>
1.1.1.1 变身公共 DNS2018 年 4 月 1 日（注意日期，愚人节），Cloudflare 宣布正式推出公共 DNS 服务，并选择了 1.1.1.1 作为主地址，1.0.0.1 作为备用地址。很多人第一反应是：“愚人节玩笑吧？”但 Cloudflare 真的做到了——他们把一个“被滥用”的地址，打造成了号称“全球最快的公共 DNS”。
</p>----------------------------------------------------------------------------------------------------------------
</p>windows11安装无网情况下跳过必须联网:
</p>windows11安装跳过必须联网
</p>直接创建本地用户
1.shift+F10   cmd里输入 start ms-cxh:localonly
重启开启OOBE bypassNRO
</p>2.shift+F10   cmd里输入 reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\OOBE /v BypassNRO /t REG_DWORD /d 1 /f
</p>批处理BAT:
</p>@echo off
</p>reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\OOBE /v BypassNRO /t REG_DWORD /d 1 /f
</p>shutdown /r /t 0
</p>3.可以联网的情况下
输入1@1.com或no@thankyou.com 密码随便输入，下一步，就可以创建用户了。
</p>4.Shift + F10 组合键。在CMD窗口中输入
net user Administrator /active:yes
然后回车再输入以下命令，就什么都不用再设置了直接进桌面
oobe\msoobe && shutdown -r
</p>5.Shift + F10 组合键。在CMD窗口中输入taskmgr 任务管理器control.exe 控制面板
</p>6.Shift + F10 组合键。在CMD窗口中输入compmgmt.msc 帐户管理面板
oobe\msoobe && shutdown -r
</p>7.Shift + F10 组合键。在CMD窗口中输入 control userpasswords2  切换用户面板
</p>8.Shift + F10 组合键。在CMD窗口中输入 net user admin admin888 /add
net user Admin /active:yes
control userpasswords2
</p>9.Shift + F10 组合键。在CMD窗口中输入logoff 注销用户
</p>----------------------------------------------------------------------------------------------------------------</p>
</p>汽车电瓶充电步骤。踩刹车大的那个,注意旁边小的是油门。车辆档位在p档。屏幕显示p,说明手刹已打开。这个时候就可以一键启动车辆了。
</p>P是停止，R是倒，N是等，D是走，S是超
</p>
</p>
</p>
</p>
</p>
</p>
</p>
</p>----------------------------------------------------------------------------------------------------------------</p>
</p>Deployment Image Servicing and Management (DISM) 是一款命令行工具，用于修复您的 Windows 10 和 11 映像。
</p>它可以查找损坏或缺失的系统文件，并修复它们，以解决您的 PC 上的关键错误。
</p>系统文件检查器工具可以帮助您修复Windows功能中的故障。它将扫描系统中的问题，并在检测到时恢复必要的文件以解决问题。
</p>您可以同时运行DISM和系统文件检查器工具以获得最佳结果。以下是操作方法。
</p>要运行DISM和系统文件检查器工具：
</p>按下Win键，然后输入cmd。
</p>右键点击命令提示符，选择以管理员身份运行。
</p>在命令提示符窗口中，输入以下命令来运行DISM工具：DISM.exe /Online /Cleanup-image /Restorehealth
</p>运行系统文件检查器工具
</p>键入以下命令并按Enter键运行系统文件检查器工具：sfc /scannow
</p>验证可能需要几分钟时间。因此，请等待验证达到100%。返回结果将显示是否发现问题以及工具是否能够修复它。
</p>输入exit并按下Enter键以关闭命令提示符。
</p>----------------------------------------------------------------------------------------------------------------</p>
</p> Windows 
</p>curl http://assist-client-cn-beijing.tos-cn-beijing.ivolces.com/install.bat -o install.bat && install.bat


</p>
Logo
</p>----------------------------------------------------------------------------------------------------------------</p>
<p>系统自带工具Windows 系统：</p>
</p>sfc/sannow windows 磁盘扫描修复系统文件工具
<p>任务管理器：按下 “Ctrl + Shift + Esc” 组合键打开任务管理器，切换至 “性能” 选项卡，点击左侧的 “内存”，在右侧能够看到内存的详细信息，其中包括速度，这个速度就是内存条的频率。</p>

<p>系统信息：按下 “Windows + R” 键，输入 “msinfo32” 后回车，打开 “系统信息” 窗口，在 “内存” 部分，可以找到 “最大带宽” 或 “内存频率” 的数值，此数值即为内存频率。</p>

<p>命令提示符：按下 “Win+R” 键打开运行窗口，输入 “cmd” 并回车，打开命令提示符，输入 “wmic memorychip” 命令，系统会列出所有内存条的详细信息，包括频率、大小、型号等。</p>
        <img src="https://github.com/hzwenlen/Please-look-here-first/blob/main/63d0f703918fa0eca806a4c2b3645cfe3e6ddbc4.webp" alt="Logo" height="400">
<p>Windows Management Instrumentation Command-line（wmic）工具:wmic memorychip get Speed</p>
        <img src="https://github.com/hzwenlen/Please-look-here-first/blob/main/wmic-memorychip-get-speed.webp" alt="Logo" height="400">
<p>执行命令后，会显示出内存的频率，单位为MHz。通过这个频率信息，我们可以进一步判断出内存的代数：</p>

33-266 MHz：对应DDR1内存

400-800 MHz：对应DDR2内存

066-1600 MHz：对应DDR3内存

866-3200 MHz：对应DDR4内存
</p>----------------------------------------------------------------------------------------------------------------</p>
<h1 align="center">SAN</h1>

<p align="center">
一个快速、轻量、灵活的 JavaScript 组件框架
<br>
A fast, portable, flexible JavaScript component framework.
</p>
        <img src="https://baidu.github.io/san/img/logo-colorful.svg" alt="Logo" height="220">
<p align="center">
  <a href="https://www.npmjs.com/package/san"><img src="http://img.shields.io/npm/v/san.svg?style=flat-square" alt="NPM version"></a>
  <a href="https://www.npmjs.com/package/san"><img src="https://img.shields.io/github/license/baidu/san.svg?style=flat-square" alt="License"></a>
  <a href="https://github.com/baidu/san/actions"><img src="https://github.com/baidu/san/workflows/CI/badge.svg" alt="Build Status"></a>
  <a href="https://coveralls.io/github/baidu/san?branch=master"><img src="https://img.shields.io/coveralls/github/baidu/san.svg?style=flat-square" alt="Coverage Status"></a>
  <a href="https://github.com/baidu/san/issues"><img src="https://img.shields.io/github/issues/baidu/san.svg?style=flat-square" alt="Issues"></a>
</p>

<p align="center">
  <a href="https://baidu.github.io/san/en/index.html" target="_blank">HomePage</a>
  <a href="https://baidu.github.io/san/" target="_blank">网站</a>
</p>
</p>----------------------------------------------------------------------------------------------------------------</p>
</p>一，天马G 220GB精简版【轻度用户】
</p>夸克：https://pan.quark.cn/s/f678250b4f6f
</p>百度：https://pan.baidu.com/s/1dQhEpIIHYppFfPoGUajjVQ?pwd=8888 
</p>提取码：8888 
</p>二，天马G 2.8T完整版【典藏】
</p>迅雷：https://pan.xunlei.com/s/VO2p_bSzmR7wEFasDV4xsHWPA1
</p>提取码：veis
</p>百度：：https://pan.baidu.com/s/1D8WfWSU92Ydsx81R4DNnVw?pwd=8888
</p>提取码：8888 
</p>----------------------------------------------------------------------------------------------------------------</p>
</p>先确认一下电脑主板是否支持UEFI启动，需要支持UEFI才行。
</p>计划硬盘空间，系统1占用多少空间，系统2占用多少空间，系统3占用多少空间，等等等。
</p>系统1安装windows,剩余空间不要创建分区哦。
</p>准备refind软件，DiskGenius软件,bootice引导修改工具
</p>备份整个 EFI 文件夹（切记，不要忽略！以备万一失败时恢复ESP）
</p>BOOT目录中，除了 Bootx64.efi，把其它文件和文件夹都删除。把 Bootx64.efi 改成其它名字，然后把 rEFInd 那三个文件夹和三个文件拖到 DiskGenius 的 \EFI\BOOT 中。
</p>用记事本打开 refind.conf修改配置文件
</p>timeout 10                              //开机选择等待多少秒，倒计时结束如果未操作，则自动启动默认系统
</p>banner icons/logo.png                   //顶端标题图片，不需要的话可以用纯色图片替代
</p>                                        //注意：这个logo.png左上角像素的颜色将决定整个桌面的背景颜色
</p>small_icon_size 48                      //代表功能项的小图标的尺寸
</p>big_icon_size 128                       //代表操作系统的大图标的尺寸，无论你制作的图标尺寸多大，会被自动调整为这个大小
</p>scanfor manual                          //是否自动搜索机器中可用系统，这里设为不搜索
</p>showtools firmware, reboot, shutdown    //显示哪些功能项小图标，这里选择的是“进入BIOS、重启、关机”
</p>enable_mouse true                       //是否允许使用鼠标
</p>default_selection 1                     //默认启动哪个系统，这里选择第一个
</p>menuentry "Windows 10" {                    //设置第一个系统，我的是 Ubuntu
 </p>   icon \EFI\boot\icons\os_win10.png  //图标，选择想要的那个图标
 </p>   loader \EFI\Microsoft\Boot\bootmgfw.efi     //启动文件，这个文件一般位于“EFI”文件夹下的对应系统文件夹中
</p>}
</p>
</p>menuentry "Deepin" {                   //设置第二个系统，
</p>    icon \EFI\boot\icons\os_deepin.png      
</p>   loader \EFI\deepin\grubx64.efi 

</p>menuentry "NewStartOS" {                     //设置第三个系统
</p>   icon \EFI\boot\icons\os_newos.png
</p>  loader \EFI\newstartos\grubx64.efi 
</p>}
</p>把这个文件按你的需要修改好，保存，拖到 DiskGenius 的 \EFI\BOOT 中，替换原文件。
</p>使用bootice引导修改工具，新建refind，分区为ESP所在地，启动文件 \EFI\BOOT\BOOTX64.efi
</p>保存设置，然后把refind调整到第一启动顺序。
</p>
</p>
</p>
</p>----------------------------------------------------------------------------------------------------------------</p>

</p>CPU    英特尔 | i5-12490F                                           1029元
</p>显卡    七彩虹 | GTX 1650 | 4GB                                   1099元
</p>主板    华硕 | PRIME H610M-E DDR5                             669元
</p>内存    金士顿（Kingston） | 16GB | 5200MHz                415元
</p>硬盘    西部数据（WD）1TB SSD固态硬盘 M.2接口          619元
</p>显示器 小米 Redmi 27英寸  100Hz高刷新                        579元
</p>机箱    先马（SAMA） 电脑机箱台式机                             99元
</p>电源    航嘉（Huntkey）WD500K 金牌500W                  256元
                                                                            总计：4765
</p>----------------------------------------------------------------------------------------------------------------</p>  
</p>CPU    英特尔(Intel) i5-12600KF 10核16线程         1100元
</p>显卡    七彩虹 RTX 3050 灵动 6GB                        1400元
</p>主板    华硕（ASUS）B760M                                900元
</p>内存    阿斯加特（Asgard）32GB                          500元
</p>硬盘    京东京造 1TB SSD固态硬盘 M.2                  500元
</p>显示器 小米 Redmi 27英寸  100Hz高刷新               600元
</p>机箱    先马（SAMA） 电脑机箱台式机                   100元
</p>电源    航嘉（Huntkey）WD750K    750W              400元
                                                                            总计：5500
</p>----------------------------------------------------------------------------------------------------------------</p>  
</p>昨天不知道吃了什么东西了？晚上发烧了，又吐又拉的。给她吃释怀，一卫安。
</p>如本     调血糖
</p>徒然草  调肾
</p>一卫安  调胃
</p>释怀     调胃
</p>----------------------------------------------------------------------------------------------------------------</p>

</p>Oracle VirtualBox https://download.virtualbox.org/virtualbox/</p>
</p>----------------------------------------------------------------------------------------------------------------</p>
</p>itsk天空</p>
</p>系统封装（新系统）
</p>1.安装纯净系统
</p>2.设置Windows界面OOBE，Shift+F10
   lusrmgr.msc 启用administrator
   taskmgr.exe 结束msoobe进程
</p>3.激活系统
</p>4.设置系统、安装软件
</p>5.安装PE工具
</p>6.运行封装工具--当前配置用于创建的新用户-重点
</p>点击封装，按提示，第一阶段结束后必须立即进入PE系统
</p>注意！系统不会自动重启，只会提示封装完成
</p>7.自动运行 sysprep 等待进入封装程序自动退出，第一阶段完成
</p>8.重启系统立马进入PE
</p>9.在PE下运行封装工具，点击设置，进入第二阶段
</p>10.OEM-自已设置
</p>11.优化-不优化
</p>12.部署-关闭万能驱动-删除万能驱动
</p>13.系统-关闭变更、转移
</p>14.用户-关闭创建新用户-启用administrator
</p>15.网络-全部关闭
</p>16.任务-全部闭闭
</p>17其它-保存映像到其它盘
</p>18.备份镜像esd,wim PE下ITSK天空系统恢复备份工具</p>
</p>----------------------------------------------------------------------------------------------------------------</p>
</p>SC封装工具3.0_系统封装首席执行官</p>
</p>1.安装纯净系统
</p>2.配置帐户验证
</p>3.激活系统
</p>4.设置系统、安装软件
</p>5.安装PE工具
</p>6.开始封装，打开SC封装工具，点击【封装体验】，可以扫描出需要修复的项目，可进行选择性修复；
</p>7.目标系统-全部去掉
</p>8.计划任务-不设置
</p>9.部署过程-不设置
</p>10.系统封装-不设置
</p>11.进入PE系统备份映像。</p>
</p>----------------------------------------------------------------------------------------------------------------</p>
<p>网站地址列表：</p>
<p>浏览器:
华为浏览器下载地址  consumer.huawei.com/cn/mobileservices/browser/</p>
<p>解压缩软件:
winrar软件下载地址  www.gtxp2.com/plus/search.php?q=winrar
<p>输入法:
搜狗输入法下载地址  www.sogou.com/
QQ五笔输入法下地地址  qq.pinyin.cn/
<p>单机播放器:
QQ播放器下载地址  player.qq.com/
QQ播放器intel版下载地址  origin.player.qq.com/
<p>免费驱动程序安装:
360驱动大师下载地址  dm.weishi.360.cn/home.html
<p>免费杀毒软件:
360杀毒软件下载地址  sd.360.cn/
<p>免费办公软件:
金山wps办公软件下载地址  www.wps.cn/
<p>免费QQ聊天软件:
QQ聊天软件下载地址  im.qq.com/
<p>免费微信电脑版软件:
微信电脑版软件下载地址  weixin.qq.com/
微信内空搜索地址  weixin.sogou.com/
<p>音乐播放软件:
酷我音乐软件下载地址  </p>
<p>系统软件卸载工具：
Geek Uninstaller下载地址 https://geekuninstaller.com/
<p>网盘图标删除器：
Drive Icon Manager下载地址 https://github.com/Return-Log/Drive-Icon-Manager/tree/master?tab=readme-ov-file
<p>密钥检测工具：
simplepidx下载地址 </p>
<p>github加速访问工具：
</p>瓦特工具箱Watt Toolkit 下载地址 https://steampp.net/
https://github.com/qipa/SteamTools</p>
