SB HW什么外网都被墙   没办法自己把代码上传到Github  然后再down下来

一句话    我也不想这样  都是被逼的!!

=======================================================================
…or create a new repository on the command line


touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/WuKongAndroid/android-15-framework-src.git
git push -u origin master

=======================================================================
…or push an existing repository from the command line


git remote add origin https://github.com/WuKongAndroid/android-15-framework-src.git
git push -u origin master
…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
