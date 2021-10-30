# deepin-wine-for-ubuntu-on-21.04
提供了一个简单的解决方案来解决deepin-wine-for-ubuntu在ubuntu21.04上无法安装的问题……
# 使用方法：
1.先下载这个仓库里面的所有包以及sh脚本文件； 
2.去gitee上面下载deepin-wine-for-ubuntu（也可以上github，但是github有时候登不上。下载地址：https://gitee.com/wszqkzqk/deepin-wine-for-ubuntu?_from=gitee_search）； 
3.解压deepin-wine-for-ubuntu包，把install_2.8.22.sh里面的mirrors.aliyun.com全部改成packages.deepin.com； 
4.解压deepin-wine-for-ubuntu on 21.04包，给repair.sh赋予可执行权限（终端输入sudo chmod u+x repair.sh）； 
5.运行脚本（终端输入./repair.sh）；
6.返回deepin-wine-for-ubuntu运行install_2.8.22.sh（记得赋予可执行权限），就能成功安装了。
