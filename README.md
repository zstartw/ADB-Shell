# ADB-Shell
常用的adb命令


### 配制流程


1. 将adb_shell文件夹移到home目录下
2. 修改.bashrc,添加环境变量
   - vim .bashrc
   - 
   ```
   #adb shell
   export PATH=${PATH}:/home/betterzw/adb_shell
   ```
3. 生效

 ``` source .bashrc```
  
4. 使用
   
  ``` adbd android-app://packagename/host/product/?goods_id=1149340&wid=21&source=pc&medium=details```
