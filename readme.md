## 说明书


> git的操作的具体步骤
    1、cd 路径 进入当前的项目文件夹

    2、配置git的基本操作

        git config --global user.name "GitHub的名字" 
        git config --global user.email "注册giehub的邮箱"

    3、git init 初始化  本地会出现一个文件夹 .git

    4、工作去 => 暂存区
        git add * 提交全部文件
        git add  文件名    提交单个指定的文件

        git commit -m "描述"

    5、查看当前的工作状态
        git status

    6、从暂存区恢复到工作区
        git checkout 文件名
    
    7、查看工作区和暂存区的版本号
        git diff
    
    8、clear 清屏

    9、查看已提交在暂存区的历史版本
        git log
    
    10、恢复文件到指定的某一个版本
        git reset --herd 版本号


暂存区提交github的操作
    11、生成ssh密钥
        ssh-keygen -t rsa -C "2636664891li.gmail.com"

    12、git remote add origin 厂库地址





