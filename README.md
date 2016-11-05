### README
- 如果想到另一台机器上写博客，运行如下代码做准备工作：
	mkdir hexo 建立一个文件夹hexo
	cd hexo
	git init
	git remote add origin https://github.com/hashc/blog_hexo.git
	git fetch --all
	git reset --hard origin/master
- 搭建hexo平台，运行bash buildhexo.sh
- auto.sh是自动实现部署博客到github，同时把hexo所有的文件上传到远程的blog_hexo仓库，每次写博客就可以直接 bash auto.sh

