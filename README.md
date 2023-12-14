Setting up Email and username globally
--------------------------------------------
	-git config --global user.name "username"
	-git config --global user.email "user@email.com"

To see the list of configuration on git
---------------------------------------
	-git config --list
		or
	-git config --global --list

git uses three components when working on local machine
	1.working directory/untracked section
	2.staging Area
	3.Local Repository

To intialize the current folder as a git repo
	-git init
	it will create an hidden folder called as ".git" which stores all the configuration related files for git to run

To send files from working directory to staging area
	-git add filename
To send multiple files
	-git add file1 file2 file3
To send all the files present in working directory to staging area
	- git add .
	"." represents present working directory
To Remove files from staging area and bring back them to untracked section
	- git rm --cached filename
		or
	- git reset filename
