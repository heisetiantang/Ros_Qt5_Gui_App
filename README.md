## ROS Qt Deskotp GUI App(librviz分支 使用librviz的菜单栏实现图层管理功能)

- 升级时间：2023年12-20号


- Use qt5 to implement the ros robot human-machine interface
- 使用qt5实现ros机器人人机界面

- Welcome to submit bugs in issues
- 欢迎在issues提交bug
***
## 分支
**rviz menu tree branch rviz  菜单树分支**
- With the rviz menu interface, there is no need to encapsulate the menu yourself.
- 采用rviz菜单接口，无需自己封装菜单
- Through the menu interface, all the Display functions of rviz can be implemented.
- 通过菜单接口，可以实现rviz所有的Display功能
- Supports the import and export of configured Display items for quick and easy.
- 支持导入导出已配置好的Display项，方便快速

[Go back master 回到主分支](https://github.com/chengyangkj/Ros_Qt5_Gui_App)

**警告：此页面上的所有图片都较大，加载较慢**
![rviz_tree-image](http://qghk8ygxs.hn-bkt.clouddn.com/rviz_tree-image.png)

***

### 一，Features
### 一，功能介绍
#### 1，Add Display
#### 1，新增显示
- The new display can provide a series of functions such as drawing, sweeping, etc.
- 新增显示后可以提供建图、扫图等一系列功能。
#### 2，Displays import or derive
#### 2,  显示列表的导入导出
***

### 二，安装教程
### 二，Installation tutorial
#### 1，首先安装ros对qt pkg的支持
#### 1，first install ros support for qt pkg
``` bash
sudo apt-get install ros-melodic-qt-create
```
``` bash
sudo apt-get install ros-melodic-qt-build
```
``` bash
sudo apt-get install qtmultimedia5-dev
```
#### 2，Git code
#### 2，获取源码
Git code
获取源码
``` bash
git clone https://github.com/chengyangkj/Ros_Qt5_Gui_App
```
Go to the branch
转到分支
``` bash
cd Ros_Qt5_Gui_App
git checkout rviz_tree
```

#### 3，Compile
#### 3，编译
Put the package in the ros src package directory：
将软件包放入ros src软件包目录下：
``` bash
catkin_make
```
#### 4，run
#### 5，运行
``` bash
rosrun cyrobot_rviz_tree cyrobot_rviz_tree
```
***
### LIENSE
### 开源协议
**GNU GPL（GNU General Public License，GNU通用公共许可证）**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200408135643929.png)

- As long as the software contains products or code that follow this Agreement, the software must also comply with the GPL License Agreement, i.e. it must be open source free, not charged from a closed source, and not commercial software.
- 只要软件中包含了遵循本协议的产品或代码，该软件就必须也遵循 GPL 许可协议，也就是必须开源免费，不能闭源收费，不能作为商用软件。

