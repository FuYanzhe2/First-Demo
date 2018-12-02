github First Demo : pull file up to the github

git命令使用——创建第一个项目

	- 1.创建github_demo目录，cd github_demo
	
	- 2.vim README.md 写入内容 :wq 退出保存
	
	- 3.git init 将目录初始化为git仓库
	
	- 4.然后，告诉 Git 程序您关心的文件并且想在此刻起跟踪它的任何改变，输入：
		git add README.md
		
	- 5.创建一次提交，请输入（此次提交是提交到本地git库中）
		git commit -m "注释信息"
		
	- 6.创建github连接
	
		git remote add origin https://github.com/FuYanzhe2/First-Demo.git
		输入github注册邮箱及密码
	或者
	
	在github上创建项目后，先使用git clone 克隆到本地，修改完REAADME.md后4,5步骤不变，然后使用git push命令即可
	
	上述使用过程中，使用git status 查看本地git仓库状态