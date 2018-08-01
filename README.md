# 欢迎加我进微信群进行讨论

<div align=center><img width="337" height="448" src="https://github.com/jarjin/NewFramework/blob/master/wx.jpg"/></div>

项目开源免费，求上面点星支持(star ^o^)

本框架工程基于Unity 5.6.5构建，服务器端基于VS2015及其以上版本。
<br> 
使用方法：本框架有客户端工程、地图编辑器工程、服务器端工程、打表工程、SVN整合工具联合组成，需要一个SVN服务器，然后通过SVN脚本，将其所有的工程拼合在一起，实现编辑工程与代码工程的分离。当更新的时候，将策划的数据表、策划的编辑器的地图、素材资源、生成的View层代码全都一次性更新组合成一个完整的客户端工程。

在Tools目录下面有三个bat批处理脚本，client.bat是客户端批处理，server.bat是服务器批处理，redis是KV内存库启动脚本。主要的client.bat里面的内容简介：

``` 
set clientUrl="https://n6bdo6uf3kz4zy4/svn/FirClient"       //客户端SVN地址
set clientPath="E:\workspace\ProjectOne\FirClient"          //客户端目录
set dataUrl="https://n6bdo6uf3kz4zy4/svn/DataTable"         //数据表SVN地址
set editorUrl="https://n6bdo6uf3kz4zy4/svn/ClientEditor"    //编辑器SVN地址
set serverUrl="https://n6bdo6uf3kz4zy4/svn/FirServer"       //服务器SVN地址
set toolPath="E:\workspace\ProjectOne\Tools\Bin"            //工具目录


set user="admin"        //SVN账号
set passwd="admin888"   //SVN密码
``` 
//-------------2018-07-31-------------
<br> 
(1)首次提交框架工程。

