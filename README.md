记录一下git上传的流程
1、如果需要创建远程厂库则需要在github上创建，然后复制http，到本地bash下利用命令 git remote add origin https://git... 连接到本地
然后 add ./  commit / git push -u origin master 。三步完成上传。
2、如果只是更新 只需要在创建本地连接的目录下 bash界面中 直接add. /commit /git push