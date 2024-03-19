# 1、删除旧的MySQL

# 2、下载MySQL

## 2.1打开Mysql官网，点击下载

![image-20240319211851810](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319211851810.png)

## 2.2点击最下面的MySQL community Downloads.

![image-20240319212019781](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319212019781.png)

## 2.3选择最下面的MySQL installer 

## for Windows

![image-20240319212112518](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319212112518.png)

## 2.4选择大的那个文件，下载

![image-20240319212341943](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319212341943.png)

# 3、安装MySQL

## 3.1第一步选full，（因为我不懂所以都选上）

![image-20240319213121300](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319213121300.png)

## 3.2第二步，安装路径可以改到D（尽量不要有中文），数据路径不要动！！！

![image-20240319213234191](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319213234191.png)

## 3.3等所选组件下载完成，点next

![image-20240319213600807](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319213600807.png)

## 3.4next

![image-20240319213638806](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319213638806.png)

## 3.5next

![image-20240319213657655](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319213657655.png)

## 3.6一直next，直到这里设置root密码，一定要记住，不然后面忘了很麻烦。（我为什么要重新装）

![image-20240319213905640](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319213905640.png)

## 3.7后续一直默认，然后finish

![image-20240319213957081](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319213957081.png)

## 3.8然后一直默认，直到这里。输入之前设置的密码，然后check，然后next

![image-20240319214131973](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319214131973.png)

## 3.9点击execute，然后finish

![image-20240319214408005](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319214408005.png)

## 3.10点击finish,安装完成

![image-20240319214517823](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319214517823.png)

# 4、启动Mysql服务

## 4.1	方法一：服务窗口启动或关闭

### 4.1.1运行窗口输入

```
services.msc
```

![image-20240319215831201](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319215831201.png)

### 4.1.2找到MySQL80,点击启动或停止。

![image-20240319215928316](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319215928316.png)

## 4.2方法二：命令行启动

### 4.2.1cmd输入命令

启动

```
net start mysql80
```

停止

```
net stop mysql80
```

![image-20240319220259441](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319220259441.png)

# 5、客户端连接

## 5.1MySQL命令行连接

![image-20240319220453541](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319220453541.png)

- 输入密码（如果闪退，检查MySQL服务是否开启，密码对不对）
- ![image-20240319220639436](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319220639436.png)









## 5.2使用系统自带的cmd执行指令连接(先配置环境变量)

输入

```
mysql -u root -p
```

![image-20240319221653261](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319221653261.png)

# 6、配置环境变量

## 6.1找到MySQL安装路径，打开bin文件夹，复制路径

![image-20240319221239820](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319221239820.png)

## 6.2打开环境变量编辑，找到path，新建一个路径，粘贴。（要重启命令行才生效）

![image-20240319221414549](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240319221414549.png)