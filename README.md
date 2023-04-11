## 所用git方法

1. 首先在github创建仓库

2. 在本地文件夹中第一次：

   ```c++
   git init //把这个目录变成Git可以管理的仓库
   
   git add README.md //文件添加到仓库
   
   git add . //当前目录下所有未追踪的文件全部add了 
   
   git commit -m "first commit" //把文件提交到仓库
   
   git remote add origin https://github.com/h-yii/NKU-Digital-Signal-Processing //关联远程仓库
   
   git push -u origin master //把本地库的所有内容推送到远程库上
   ```

3. 之后的正常修改

   ```c++
   git add .
   
   git commit -m "first commit" //把文件提交到仓库
       
   git push
   ```

4. 如果只修改一个文件

   ```
   git add "README.md"
   ```

   可以只修改README.md一个文件

