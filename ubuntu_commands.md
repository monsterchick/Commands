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

## Compiling source code for installing software:
<details><summary>7 steps to compile</summary>
  
### 1. Download the source code:
#### curl source_code_link --output filename
  
```
e.g. curl https://www.nano-editor.org/dist/v7/nano-7.2.tar.gz --output nano-7.2.tar.gz
```
### 2. Extract the source code
#### tar -xzvf file
```
e.g. tar -xzvf nano-7.2.tar.gz
```
  
### 3. Go into the folder
#### cd folder_path
```
e.g. cd nano-7.2
```
  
### 4. Configure compilation
```
./configure    # generate a makefile
```
  
### 5. Compile
```
make
```
  
### 6. Install
```
sudo make install
```
  
### 7. Clear cache
```
make clean    
```
</details>

[⬆ ʀᴇᴛᴜʀɴ ᴛᴏ ᴛᴏᴩ](#top)
