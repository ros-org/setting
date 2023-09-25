# arm_kuka.md

## 1 c4控制柜配置教程

### 1.1 接线

#### 1.1.1 电源盒

把电源盒接头处拧掉取出里面的铁块

![image-20230620170200088](assets/arm_kuka_img/image-20230620170200088.png)

![image-20230620170358509](assets/arm_kuka_img/image-20230620170358509.png)

铁块取出后再把接头处拧上

![image-20230620170612440](assets/arm_kuka_img/image-20230620170612440.png)

接头处左右两侧螺丝拧松

![image-20230620170734212](assets/arm_kuka_img/image-20230620170734212.png)

![image-20230620170030387](assets/arm_kuka_img/image-20230620170030387.png)

后端拧回电源盒上

![image-20230620170849236](assets/arm_kuka_img/image-20230620170849236.png)

把6平方多股线从外面穿进电源盒

![image-20230620171056828](assets/arm_kuka_img/image-20230620171056828.png)

![image-20230620171804272](assets/arm_kuka_img/image-20230620171804272.png)

三根线分别接入1 2 3 孔 （3个孔随便接 不用管线的颜色）

（注：正反两面孔位都有数字）

![image-20230620173923487](assets/arm_kuka_img/image-20230620173923487.png)

![image-20230620171701623](assets/arm_kuka_img/image-20230620171701623.png)

![image-20230620173127904](assets/arm_kuka_img/image-20230620173127904.png)

侧边拧螺丝加固

![image-20230620171531334](assets/arm_kuka_img/image-20230620171531334.png)

把接好的线收回电源盒中并拧紧螺丝固定

![image-20230620173427511](assets/arm_kuka_img/image-20230620173427511.png)

![image-20230620173547975](assets/arm_kuka_img/image-20230620173547975.png)

![image-20230620173800536](assets/arm_kuka_img/image-20230620173800536.png)

#### 1.1.2 安全回路接口

把安全阀盒打开

![image-20230620175158209](assets/arm_kuka_img/image-20230620175158209.png)

0.5平方单股线两头用冷压针固定（做14根），插入对应的孔内

![image-20230620175712921](assets/arm_kuka_img/image-20230620175712921.png)

（注：两面都有数字）

![image-20230620180041687](assets/arm_kuka_img/image-20230620180041687.png)

(一根线插两个孔)

第一排：1和2短接  3和4短接  5和6短接  7和8短接  9和10短接  11和12短接  13和14短接 

第二排：15和16短接  17和18短接  19和20短接  21和22短接  23和24短接  25和26短接 27和28短接

![image-20230620180501759](assets/arm_kuka_img/image-20230620180501759.png)

把有线的那面朝下，放回安全阀盒内并固定螺丝

![image-20230620181656850](assets/arm_kuka_img/image-20230620181656850.png)

![image-20230620181720354](assets/arm_kuka_img/image-20230620181720354.png)

找到X11位置并固定

![image-20230620184122435](assets/arm_kuka_img/image-20230620184122435.png)

![image-20230620182726856](assets/arm_kuka_img/image-20230620182726856.png)

![image-20230620184025374](assets/arm_kuka_img/image-20230620184025374.png)

#### 1.1.3 编码器线

![image-20230620184237952](assets/arm_kuka_img/image-20230620184237952.png)

一端固定在X21处

![image-20230620185733171](assets/arm_kuka_img/image-20230620185733171.png)另一端固定在X31处

![image-20230620185534394](assets/arm_kuka_img/image-20230620185534394.png)

#### 1.1.4 动力线

![image-20230620185941602](assets/arm_kuka_img/image-20230620185941602.png)

一端固定在X30处并拧好螺丝

![image-20230620190832050](assets/arm_kuka_img/image-20230620190832050.png)

另一端固定在X20处

![image-20230620191349588](assets/arm_kuka_img/image-20230620191349588.png)

#### 1.1.5 控制箱内开关

打开控制箱找到左侧开关按钮，向右上扭动

![image-20230621093159698](assets/arm_kuka_img/image-20230621093159698.png)

右侧找到A1-X305的线插到电路板上

![image-20230621093636008](assets/arm_kuka_img/image-20230621093636008.png)

#### 1.1.6 遥控器

插入X19位置

![image-20230621092210812](assets/arm_kuka_img/image-20230621092210812.png)

#### 1.1.7 机器人初次通电

机器人KSS系统里，会提示选择机器人信息的对话框，选择“机器人”按钮

![image-20230626150430680](assets/arm_kuka_img/image-20230626150430680.png)

点击① ——选择管理员——输入密码kuka

![image-20230626151043896](assets/arm_kuka_img/image-20230626151043896.png)

### 1.2 网络配置

第一步：点击①

![image-20230719164258273](assets/arm_kuka_img/image-20230719164258273.png)

第2步：点击安全维护人员，输入密码（密码是：kuka）

![image-20230719164331061](assets/arm_kuka_img/image-20230719164331061.png)

第3步：点击左上方图标①

![image-20230719164409317](assets/arm_kuka_img/image-20230719164409317.png)

第4步：点击投入运行→点击网络配置

![image-20230719164422549](assets/arm_kuka_img/image-20230719164422549.png)

第5步：设置参数，设置好后记得点保存！

![image-20230719164438261](assets/arm_kuka_img/image-20230719164438261.png)

第6步：点击① 选择操作人员（标准）

![image-20230719164500711](assets/arm_kuka_img/image-20230719164500711.png)

第7步：断电（开关在控制柜上）

![image-20230719164514338](assets/arm_kuka_img/image-20230719164514338.png)

第8步：连接网线

（一头插在控制柜里面 KLI 处）

![image-20230719164531684](assets/arm_kuka_img/image-20230719164531684.png)

![image-20230719164547730](assets/arm_kuka_img/image-20230719164547730.png)

（另一头插在路由器或者扩展坞上）

![image-20230719164559978](assets/arm_kuka_img/image-20230719164559978.png)

第9步：开电（开关在控制柜上）

![image-20230719164639881](assets/arm_kuka_img/image-20230719164639881.png)

第10步：vnc进去ping一下，能ping通就ok了！

![image-20230719164701078](assets/arm_kuka_img/image-20230719164701078.png)


## 2 c5控制柜配置教程

### 2.1 控制柜接线

#### 2.1.1 配置XG11.1安全接口

![Snipaste_2023-09-21_12-50-32](assets/arm_kuka_img/Snipaste_2023-09-21_12-50-32.png)

    短接11和16、15和14、5和1、3和7、8和2、4和10。

#### 2.1.2 配置XG58使能开关

![Snipaste_2023-09-21_12-52-33](assets/arm_kuka_img/Snipaste_2023-09-21_12-52-33.png)

    短接5和1、3和7、6和2、4和8。

#### 2.1.3 将配置好的线接入对应控制柜接口上

![Snipaste_2023-09-21_13-01-04](assets/arm_kuka_img/Snipaste_2023-09-21_13-01-04.png)

![Snipaste_2023-09-21_13-00-16](assets/arm_kuka_img/Snipaste_2023-09-21_13-00-16.png)

![Snipaste_2023-09-21_12-58-57](assets/arm_kuka_img/Snipaste_2023-09-21_12-58-57.png)

### 2.2 首次上电运行步骤

#### 2.2.1 进入机器人KSS系统后，会出现提示选择机器人信息的对话框，选择“机器人”按钮

#### 2.2.2 进行安全配置

①进入“主菜单”界面，单击“配置”，菜单，选择“用户组”，可进入“用户组”选择界面

![Snipaste_2023-09-21_13-03-59](assets/arm_kuka_img/Snipaste_2023-09-21_13-03-59.png)

![Snipaste_2023-09-21_13-05-31](assets/arm_kuka_img/Snipaste_2023-09-21_13-05-31.png)

②选择“安全调试员”用户组，输入登陆密码“kuka”完成登陆

③然后，再回到“配置”菜单，选择“安全配置”

④如果有弹出“刷新安全数据”的选择界面，单击“是”

![Snipaste_2023-09-21_13-06-28](assets/arm_kuka_img/Snipaste_2023-09-21_13-06-28.png)

之后，系统弹出“故障排除助手”对话框，选择“机器人或RDC存储器首次投入运行”一行，然后单击下面的“现在激活”。系统弹出一个确认对话框，选择“是”，以改变安全相关的配置部分。等待安全参数配置完成，返回到主界面，然后确认信息提示，即能够上电操作使机器人运动起来。

![Snipaste_2023-09-21_13-07-29](assets/arm_kuka_img/Snipaste_2023-09-21_13-07-29.png)

#### 2.2.3 网络配置

见1.2节C4控制柜网络配置

### 2.3 烧录KRL软件包

#### 2.3.1 下载相应软件（KRC版本为8.7.5）

1.workvisual6.0版本

2.KRL3.2（具体软件包可与我联系）

#### 2.3.2 将KRL3.2软件包导入到wov中

1.将电脑与库卡机械臂设置在同一网段（机械臂网段为192.168.147.147）

2.通过网线连接电脑和控制柜（F5口）

3.打开workvisual软件

    点击文件，查找项目，将找到的项目打开，打开后如下图所示

![Snipaste_2023-09-21_13-11-01](assets/arm_kuka_img/Snipaste_2023-09-21_13-11-01.png)

4.导入KRL3.2软件包

    点击extras，备选软件包管理

![Snipaste_2023-09-21_13-11-51](assets/arm_kuka_img/Snipaste_2023-09-21_13-11-51.png)

    点击+号按钮，找到KRL软件包所在的位置，加入到控制柜中

![Snipaste_2023-09-21_13-12-41](assets/arm_kuka_img/Snipaste_2023-09-21_13-12-41.png)

    添加完毕后，如下图所示

![Snipaste_2023-09-21_13-13-21](assets/arm_kuka_img/Snipaste_2023-09-21_13-13-21.png)

    选项中有其余软件包（KUKA.PROFINET S），删除掉，不然后续会出现错误，最终如下图所示，即可进行下一步

![Snipaste_2023-09-21_13-14-01](assets/arm_kuka_img/Snipaste_2023-09-21_13-14-01.png)

#### 2.3.3 更改示教器的时间

    在库卡示教器上将时间改为北京时间，与电脑一致，并将登录用户改为专家

#### 2.3.4 将KRL软件包导入到控制柜中

    点击安装，一直点击继续即可完成安装步骤

![Snipaste_2023-09-21_13-14-33](assets/arm_kuka_img/Snipaste_2023-09-21_13-14-33.png)
