# drive_curtis

第1步：.连接好调试线，确认驱动正常

（一端插在车上一端插在电脑上）

![image-20230627150520607](assets/drive_curtis_img/image-20230627150520607-16878533596711.png)

![image-20230627150536656](assets/drive_curtis_img/image-20230627150536656.png)

第2步：拷贝底盘电机驱动器数据

打开1314-4402 PC Programming Station (OEM)软件 点击页面左边第一个按钮

![image-20230627150554864](assets/drive_curtis_img/image-20230627150554864.png)

然后点击File 选择Save As另存为

![image-20230627150627209](assets/drive_curtis_img/image-20230627150627209.png)

拷贝时记得备注左右电机以免搞混

![image-20230627150645907](assets/drive_curtis_img/image-20230627150645907.png)

第3步：打开调试软件，选择端口Comms->Set COM Port->COM xx；

查看电脑端口：找到此电脑➡右击管理➡设备管理器➡端口

![image-20230627150706545](assets/drive_curtis_img/image-20230627150706545.png)

设置COM端口

![image-20230627150728100](assets/drive_curtis_img/image-20230627150728100.png)

4.点击刷写Flash，进度条走完后，根据提示操作；

![image-20230627150755116](assets/drive_curtis_img/image-20230627150755116-16878533828522.png)

![image-20230627150813629](assets/drive_curtis_img/image-20230627150813629.png)

下载操作完成后，车辆断电5s重启

5.重启后，用1314-4402 PC Programming Station (OEM)软件刷入参数。

点击连接系统

![image-20230627150843242](assets/drive_curtis_img/image-20230627150843242.png)

打开自己需要烧录的文件

![image-20230627150907998](assets/drive_curtis_img/image-20230627150907998.png)

点击烧录

![image-20230627150931123](assets/drive_curtis_img/image-20230627150931123.png)

车辆断电5s

![image-20230627151002036](assets/drive_curtis_img/image-20230627151002036.png)

看到提示后打开电源

![image-20230627151022383](assets/drive_curtis_img/image-20230627151022383.png)

烧录完成！