# 🐧 Linux Learning

> I learn Linux commands, practice them hands-on, and upload everything I explore here.

---

## 📖 Command Reference

| Command | Purpose | Example |
|---------|---------|---------|
| `pwd` | Shows current directory | `pwd` |
| `ls` | Shows current folder's files or folder | `ls` |
| `cd` | Used to switch the folder | `cd foldername` |
| `mkdir` | Used to create folder | `mkdir myfolder` |
| `rm -rf` | Used to delete the folder | `rm -rf myfolder` |
| `ps -ef` | Shows all running process details | `ps -ef` |
| `top` | Shows CPU usage and running processes | `top` |
| `df -h` | Check the disk storage usage of the server | `df -h` |
| `history` | Shows history | `history` |
| `uptime` | Shows duration of system using | `uptime` |

---

## 🛠️ Tasks

**1. Create a directory called project-files**
```bash
mkdir project-files
```

**2. Navigate into the project-files directory**
```bash
cd project-files
```

**3. Create a file called notes.txt using vi**
```bash
vi notes.txt
```

**4. Display the contents of notes.txt**
```bash
cat notes.txt
```

**5. Copy notes.txt to backup.txt**
```bash
cat notes.txt backup.txt
```

**6. Show the first 100 lines of a file called logs.txt**
```bash
head -n 100 logs.txt
```

**7. Show the last 100 lines of logs.txt**
```bash
tail -n 100 logs.txt
```

**8. Check the disk storage usage of the server**
```bash
df -h
```

**9. Check the running processes in the system**
```bash
ps -ef
```

**10. Delete a file called temp.txt**
```bash
rm temp.txt
```

---

## 💡 Concepts

**1. What is the difference between `>` and `>>`?**
`>` overrides the old content and copies the given content and `>>` is used to append the content to old content.

**2. What is the purpose of `kill -9`?**
It is used to terminate the given process ID immediately.

**3. What is the difference between `rm` and `rmdir`?**
`rm` is used to delete the files and `rmdir` is used to delete the empty folder.

**4. What information does `netstat -tulpn` provide?**
It shows running services and their port numbers in the system.

**5. What is the purpose of `ping`?**
That used to check the connectivity between system and server.

---

## 🔍 Scenarios

**1. Check the current working directory**
```bash
pwd
```

**2. Create a directory called devops inside the home directory**
```bash
mkdir devops
```

**3. Check which process is using high CPU**
```bash
top
```

**4. Check whether your server can connect to google.com**
```bash
ping google.com
```

**5. View the last 50 lines of application.log**
```bash
tail -n 50 application.log
```
