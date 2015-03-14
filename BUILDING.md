从源代码构建绿色版VirtuaBox如下步骤

### 必备软件 ###

获取并安装如下软件
* window系统
* AutoIt from http://www.autoitscript.com/site/autoit/downloads/ ( you need "AutoIt Full Installation" )
* 7zip from http://www.7-zip.org/
* Resource Hacker from http://www.angusj.com/resourcehacker/

AutoIt是一个脚本工具,在windows上写脚本,然后编译为exe,使用resourc hacker 可以更改.exe的图标


## 获取源代码 ##

从Github中检出源代码,可以参考[GitHub on Windows](http://windows.github.com/) 或者使用如下git命令

`git clone https://github.com/vboxme/Portable-VirtualBox.git`

将会创建一个新的目录Portable-VirtualBox.


## Making a new version with the build script ##
## 使用脚本创建一个新的版本Making a new version with the build script ##

运行脚本. 会在`build\release`目录下生成一个新的版本


## 手工做一个新的版本 ##

### 手工编译 ###

1. 开始 All ->programs->AutoIt v3->编译为 .exe (x86)
2. Use the brows function to set:
* Source(源代码): Portable-VirtualBox\source\Portable-VirtualBox.au3
* Destination(目标文件): Portable-VirtualBox\Portable-VirtualBox.exe
* Custom Icon(图标): Portable-VirtualBox\source\VirtualBox.ico
3. 点击 转化 

会创建一个.exe文件Portable-VirtualBox.exe . Portable-VirtualBox 可以直接在Portable-VirtualBox folder目录下运行.

### Releasing manually ###
To make a release you also need to do the following:

1. If you have run it in the Portable-VirtualBox folder delete the Portable-VirtualBox folder and do a new git clone and compile so its no junk in the data and app folders from previous runs
2. Go back to the Portable-VirtualBox folder
3. Right click on it and select 7zip->Add to archive
4. In the 7zip dialog select "Self extracting archive (SFX) and click "ok" 
5. This will make a new .exe file named Portable-VirtualBox.exe
6. Open the newly created Portable-VirtualBox.exe with Resource Hacker find the Icon Group->1->1033
7. Use the Replace resource function to replace it with the icon at Portable-VirtualBox\source\VirtualBox.ico
8. Save & exit
