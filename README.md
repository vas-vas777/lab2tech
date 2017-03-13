pca17@debian-xrdp:~$ git clone https://github.com/vas-vas777/lab2-tech
Cloning into 'lab2-tech'...
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Checking connectivity... done.
pca17@debian-xrdp:~$ git status
On branch test
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.CLion2016.2/
	.ICEauthority
	.Xauthority
	.bash_history
	.bash_logout
	.bashrc
	.cache/
	.config/
	.dbus/
	.designer/
	.dosbox/
	.gitconfig
	.gnome/
	.java/
	.local/
	.mozilla/
	.profile
	.remmina/
	.wine/
	.xsession-errors
	ClionProjects/
	Graphs/
	a.out
	build-Graphs-unknown-Debug/
	file2.c
	file3.c
	iu8.odb
	lab2-tech/
	practice/
	"\320\224\320\276\320\272\321\203\320\274\320\265\320\275\321\202\321\213/"
	"\320\232\320\260\321\204\320\265\320\264\321\200\320\260.odb"
	"\320\235\320\276\320\262\320\260\321\217 \320\261\320\260\320\267\320\260 \320\264\320\260\320\275\320\275\321\213\320\235.odb"
	"\320\240\320\260\320\261\320\276\321\207\320\270\320\271 \321\201\321\202\320\276\320\273/"

nothing added to commit but untracked files present (use "git add" to track)
pca17@debian-xrdp:~$ git baranch
git: 'baranch' is not a git command. See 'git --help'.

Did you mean this?
	branch
pca17@debian-xrdp:~$ git branch
  dev
* test
pca17@debian-xrdp:~$ git clone https://github.com/vas-vas777/lab2-tech2
Cloning into 'lab2-tech2'...
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Checking connectivity... done.
pca17@debian-xrdp:~$ git clone https://github.com/vas-vas777/lab2tech
Cloning into 'lab2tech'...
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Checking connectivity... done.
pca17@debian-xrdp:~$ git branch
  dev
* test
pca17@debian-xrdp:~$ git status
On branch test
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.CLion2016.2/
	.ICEauthority
	.Xauthority
	.bash_history
	.bash_logout
	.bashrc
	.cache/
	.config/
	.dbus/
	.designer/
	.dosbox/
	.gitconfig
	.gnome/
	.java/
	.local/
	.mozilla/
	.profile
	.remmina/
	.wine/
	.xsession-errors
	ClionProjects/
	Graphs/
	a.out
	build-Graphs-unknown-Debug/
	file2.c
	file3.c
	iu8.odb
	lab2tech/
	practice/
	"\320\224\320\276\320\272\321\203\320\274\320\265\320\275\321\202\321\213/"
	"\320\232\320\260\321\204\320\265\320\264\321\200\320\260.odb"
	"\320\235\320\276\320\262\320\260\321\217 \320\261\320\260\320\267\320\260 \320\264\320\260\320\275\320\275\321\213\320\235.odb"
	"\320\240\320\260\320\261\320\276\321\207\320\270\320\271 \321\201\321\202\320\276\320\273/"

nothing added to commit but untracked files present (use "git add" to track)
pca17@debian-xrdp:~$ git branch -r
pca17@debian-xrdp:~$ git branch
  dev
* test
pca17@debian-xrdp:~$ git branch
  dev
* test
pca17@debian-xrdp:~$ mkdir repo
pca17@debian-xrdp:~$ cd repo/
pca17@debian-xrdp:~/repo$ git clone https://github.com/vas-vas777/lab2tech
Cloning into 'lab2tech'...
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Checking connectivity... done.
pca17@debian-xrdp:~/repo$ git branch
  dev
* test
pca17@debian-xrdp:~/repo$ rm -rf .git
pca17@debian-xrdp:~/repo$ cd ../
pca17@debian-xrdp:~$ rm -rf .git
pca17@debian-xrdp:~$ ls
123                         file3.c   repo         Музыка
a.out                       file.c    Видео        Новая база данныН.odb
build-Graphs-unknown-Debug  Graphs    Документы    Общедоступные
ClionProjects               iu8.odb   Загрузки     Рабочий стол
file1.c                     lab2tech  Изображения  Шаблоны
file2.c                     practice  Кафедра.odb
pca17@debian-xrdp:~$ cd repo/
pca17@debian-xrdp:~/repo$ git branch
fatal: Not a git repository (or any parent up to mount point /home)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
pca17@debian-xrdp:~/repo$ git clone https://github.com/vas-vas777/lab2tech
fatal: destination path 'lab2tech' already exists and is not an empty directory.
pca17@debian-xrdp:~/repo$ ls
lab2tech
pca17@debian-xrdp:~/repo$ cd lab2tech/
pca17@debian-xrdp:~/repo/lab2tech$ git branch -r
  origin/HEAD -> origin/master
  origin/master
pca17@debian-xrdp:~/repo/lab2tech$ git branch
* master
pca17@debian-xrdp:~/repo/lab2tech$ git checkout -b dev
Switched to a new branch 'dev'
pca17@debian-xrdp:~/repo/lab2tech$ git branch
* dev
  master
pca17@debian-xrdp:~/repo/lab2tech$ git checkout -b test
Switched to a new branch 'test'
pca17@debian-xrdp:~/repo/lab2tech$ git branch
  dev
  master
* test
pca17@debian-xrdp:~/repo/lab2tech$ git status
On branch test
nothing to commit, working directory clean
pca17@debian-xrdp:~/repo/lab2tech$ git checkout master
Switched to branch 'master'
Your branch is up-to-date with 'origin/master'.
pca17@debian-xrdp:~/repo/lab2tech$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean
pca17@debian-xrdp:~/repo/lab2tech$ git log
commit 589de58157bf20a8c8b5479b7aa8fb333b19a7fe
Author: vas-vas777 <vasya1998@list.ru>
Date:   Mon Mar 13 14:04:15 2017 +0400

    Create README.md
pca17@debian-xrdp:~/repo/lab2tech$ git checkout dev
Switched to branch 'dev'
pca17@debian-xrdp:~/repo/lab2tech$ git status
On branch dev
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	jjj

nothing added to commit but untracked files present (use "git add" to track)
pca17@debian-xrdp:~/repo/lab2tech$ git add .
pca17@debian-xrdp:~/repo/lab2tech$ git status
On branch dev
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   jjj

pca17@debian-xrdp:~/repo/lab2tech$ git commit'init'
git: 'commitinit' is not a git command. See 'git --help'.
pca17@debian-xrdp:~/repo/lab2tech$ git commit -m'init'
[dev 0c9e86f] init
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 jjj
pca17@debian-xrdp:~/repo/lab2tech$ git status
On branch dev
nothing to commit, working directory clean
pca17@debian-xrdp:~/repo/lab2tech$ git branch test
fatal: A branch named 'test' already exists.
pca17@debian-xrdp:~/repo/lab2tech$ git checkout test
Switched to branch 'test'
pca17@debian-xrdp:~/repo/lab2tech$ git status
On branch test
nothing to commit, working directory clean
pca17@debian-xrdp:~/repo/lab2tech$ git status
On branch test
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	ggg

nothing added to commit but untracked files present (use "git add" to track)
pca17@debian-xrdp:~/repo/lab2tech$ git add .
pca17@debian-xrdp:~/repo/lab2tech$ git status
On branch test
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   ggg

pca17@debian-xrdp:~/repo/lab2tech$ git commit -m'init'
[test 691790e] init
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ggg
pca17@debian-xrdp:~/repo/lab2tech$ git log
commit 691790e1dab774dba98d34af1f58fb32c3e3572b
Author: Your Name <you@example.com>
Date:   Mon Mar 13 13:15:14 2017 +0300

    init

commit 589de58157bf20a8c8b5479b7aa8fb333b19a7fe
Author: vas-vas777 <vasya1998@list.ru>
Date:   Mon Mar 13 14:04:15 2017 +0400

    Create README.md
pca17@debian-xrdp:~/repo/lab2tech$ git branch
  dev
  master
* test
pca17@debian-xrdp:~/repo/lab2tech$ git merge master
Already up-to-date.
pca17@debian-xrdp:~/repo/lab2tech$ git checkout dev
Switched to branch 'dev'
pca17@debian-xrdp:~/repo/lab2tech$ git merge master
Already up-to-date.
pca17@debian-xrdp:~/repo/lab2tech$ git checkout test
Switched to branch 'test'
pca17@debian-xrdp:~/repo/lab2tech$ git merge master
Already up-to-date.
pca17@debian-xrdp:~/repo/lab2tech$ git checkout test
Already on 'test'
pca17@debian-xrdp:~/repo/lab2tech$ git status
On branch test
nothing to commit, working directory clean
pca17@debian-xrdp:~/repo/lab2tech$ git log --graph
* commit 691790e1dab774dba98d34af1f58fb32c3e3572b
| Author: Your Name <you@example.com>
| Date:   Mon Mar 13 13:15:14 2017 +0300
| 
|     init
|  
* commit 589de58157bf20a8c8b5479b7aa8fb333b19a7fe
  Author: vas-vas777 <vasya1998@list.ru>
  Date:   Mon Mar 13 14:04:15 2017 +0400
  
      Create README.md
pca17@debian-xrdp:~/repo/lab2tech$ git branch
  dev
  master
* test
pca17@debian-xrdp:~/repo/lab2tech$ git checkout master
Switched to branch 'master'
Your branch is up-to-date with 'origin/master'.
pca17@debian-xrdp:~/repo/lab2tech$ git log --graph
* commit 589de58157bf20a8c8b5479b7aa8fb333b19a7fe
  Author: vas-vas777 <vasya1998@list.ru>
  Date:   Mon Mar 13 14:04:15 2017 +0400
  
      Create README.md
pca17@debian-xrdp:~/repo/lab2tech$ git checkout dev
Switched to branch 'dev'
pca17@debian-xrdp:~/repo/lab2tech$ git merge test
Merge made by the 'recursive' strategy.
 ggg | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ggg
pca17@debian-xrdp:~/repo/lab2tech$ git log --graph
*   commit 524434f183eb9ee0ccdd52b7127a785cada03279
|\  Merge: 0c9e86f 691790e
| | Author: Your Name <you@example.com>
| | Date:   Mon Mar 13 13:22:47 2017 +0300
| | 
| |     Merge branch 'test' into dev
| |   
| * commit 691790e1dab774dba98d34af1f58fb32c3e3572b
| | Author: Your Name <you@example.com>
| | Date:   Mon Mar 13 13:15:14 2017 +0300
| | 
| |     init
| |   
* | commit 0c9e86f81fe3164d22964f74859bdbaf9377a49f
|/  Author: Your Name <you@example.com>
|   Date:   Mon Mar 13 13:13:50 2017 +0300
|   
|       init
|  
* commit 589de58157bf20a8c8b5479b7aa8fb333b19a7fe
  Author: vas-vas777 <vasya1998@list.ru>
  Date:   Mon Mar 13 14:04:15 2017 +0400
  
:
