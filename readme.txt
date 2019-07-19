git使用步骤
1、创建本地仓库（版本库）  （①mkdir  learngit（仓库名）     ②cd  learngit）
2、将文件上传到本地仓库（①git add readme.txt（文件名全称）  ②git commit -m "wrote a readme file"）
3、将本地仓库的东西添加到远程库 
git remote set-url origin git@github.com:huang-yueming/learnpython.git
git remote -v origin https://github.com/huang-yueming/learnpython.git
git remote add origin git@github.com:huang-yueming/learnpython.git
git push -u origin master
git push origin master
