第一步，下载LordPE和蓝灯4.4.0安装程序，直接解压蓝灯的安装程序：

![LordPE下载](https://github.com/ntkernel/file/blob/master/LoadPe.7z)

![查看图片](https://raw.githubusercontent.com/ntkernel/lantern/master/lantern_wiki/image/2.PNG)

第二步，打开lordpe，点击PE编辑器,选择lantern.exe：

![查看图片](https://raw.githubusercontent.com/ntkernel/lantern/master/lantern_wiki/image/3.PNG)

![查看图片](https://raw.githubusercontent.com/ntkernel/lantern/master/lantern_wiki/image/4.PNG)

第三步，点击目录：

![查看图片](https://raw.githubusercontent.com/ntkernel/lantern/master/lantern_wiki/image/5.PNG)

第四步，点导入表右边的两个点：

![查看图片](https://raw.githubusercontent.com/ntkernel/lantern/master/lantern_wiki/image/6.PNG)

第五步，右键kernel32.dll,添加导入表，DLL输入lantern.dll，API输入patch，取消掉“检查导入函数是否存在”，点+然后马上点“确定”，不然卡住了就不能保存了：

![查看图片](https://raw.githubusercontent.com/ntkernel/lantern/master/lantern_wiki/image/7.PNG)

第六步，关掉lordpe，把lantern.dll和lantern.ini （下载：https://github.com/JuncoJet/unlimited-landeng-for-win/blob/master/Release/lantern1.20.zip ） 复制到蓝灯目录：

![查看图片](https://raw.githubusercontent.com/ntkernel/lantern/master/lantern_wiki/image/8.PNG)

第七步，新建一个叫“.lantern.exe.new”的文件，右键文件->属性->安全->编辑->添加->高级->立即查找->找到everyone->拒绝“完全控制”

![查看图片](https://raw.githubusercontent.com/ntkernel/lantern/master/lantern_wiki/image/1.PNG)
