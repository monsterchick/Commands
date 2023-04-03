
<center>(#top)

| Ubuntu |  | 默认值 | 描述 |
| --- | --- | --- | --- |
| username | 字符串 | 无 | 用户名 |
| password | 字符串 | 无 | 密码 |
| remember | 布尔值 | --- | 是否记住用户登录状态 |

</center>

# ubuntu:
## File and directory commands:
<details><summary>ls</summary>
List the files and directories in the current directory.
  
```

```
</details>

<details><summary>cd</summary>
Change the current working directory.
  
```
 
```
</details>

<details><summary>pwd</summary>
Show the current working directory's path.
  
```

```
</details>
<details><summary>mkdir</summary>
Create a new directory.
  
```
  
```
</details>
<details><summary>rmdir</summary>
Remove an empty directory.
  
```
  
```
</details>
<details><summary>cp</summary>
Copy a file or directory.
  
```
  
```
</details>
<details><summary>mv</summary>
Move a file or directory.
  
```
  
```
</details>
<details><summary>rm</summary>
Remove a file or directory.
  
```
  
```
</details>

## 2.System information and status commands:
<details><summary>top</summary>
Show the currently running processes and system resource usage.
  
```
  
```
</details>
<details><summary>ps</summary>
List the processes running on the system.
  
```
  
```
</details>
<details><summary>df</summary>
Display disk space usage information.
  
```
  
```
</details>
<details><summary>free</summary>
Display memory usage information.
  
```
  
```
</details>
<details><summary>uname</summary>
Show the system information like kernel version, hostname etc.
  
```
  
```
</details>
<details><summary>ifconfig</summary>
Display network interface configuration information.
  
```
  
```
</details>

## 3.Package management commands:
<details><summary>apt-get</summary>
Install, update, or remove packages.
  
```
  
```
</details>
<details><summary>dpkg</summary>
Manage installed packages.
  
```
  
```
</details>
<details><summary>apt-cache</summary>
Search for packages and display package information.
  
```
  
```
</details>

## 4.Text manipulation commands:
<details><summary>cat</summary>
Display the contents of a file.
  
```
  
```
</details>
<details><summary>grep</summary>
Search for a pattern in a file.
  
```

```
</details>
<details><summary>sed</summary>
Stream editor to manipulate text.
  
```

```
</details>
<details><summary>awk</summary>
Pattern scanning and processing language.
  
```

```
</details>

## 5.User and permission management commands:
<details><summary>sudo</summary>
Execute a command with superuser privileges.
  
```

```
</details>
<details><summary>useradd</summary>
Add a new user to the system.
  
```
  
```
</details>
<details><summary>passwd</summary>
Change a user's password.
  
```
  
```
</details>
<details><summary>chown</summary>
Change the owner of a file or directory.
  
```

```
</details>
<details><summary>chmod</summary>
Change the permissions of a file or directory.
  
```

```
</details>

## 6.System information commands:
<details><summary>service</summary>
Used to start, stop, and manage system services.
  
```
  service --status-all    # lists the status of all running or stopped system services and daemons.
```
</details>

## 7.Advanced Package Tool commands:
<details><summary>apk</summary>
To install, remove, and manage software packages from repositories.
  
```
  sudo apt list installed    # lists all the packages that are currently installed on the system.
```
</details>
  
  
[⬆ ʀᴇᴛᴜʀɴ ᴛᴏ ᴛᴏᴩ](#)
# Git
  
```
git config --global user.name    # sets a username
git config --global user.email    # sets a user email
```
```
git init    # creates a new Git repository
```
```
git clone    # downloads all files from remote repository
```
```
git status    # check status
```
```
git add --add
```
```
git init
```
```
# creates a new Git repository
```
```
git clone
```
```
# downloads all files from remote repository
```
```
git status    # check status
```
```
git add --add
```
```
git add .
```
```
git add fileName
```
```
# stages file(s)
```
```
git commit -m "description"
```
```
# commits files
```
```
git branch    # check local branch(s)
```
```
git branch + newBranchName    # creates a new branch
```
```
git checkout + branchName    # switches to a specific branch
```
```
git push origin --delete github    # delete branch remotely
```
```
git checkout origin/branchName    # check remote branch(s)
```
```
echo .DS_Store >> ./.gitignore    # put .DS_Store into gitignore
```
```
git reset    # pull the files from old version to local repository and back to previous version. All current commit will be clean up
```

```
git log --oneline    # check all commit info in one line
```
```
git log    # check all commit info
```
[ʀᴇᴛᴜʀɴ ᴛᴏ ᴛᴏᴩ](#top)
