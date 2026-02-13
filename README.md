---

<p align="center">
  <img src="images/banner.png" alt="Linux Masterclass Banner" />
</p>

# 🎓 Linux Masterclass – 30 Days to Become a Linux Pro 🚀

> Command Line | Shell | Scripting | System Administration

---

## 📌 Banner Design Idea

* **Size:** 1280 x 640 px
* **Text Example:**

```
LINUX MASTERCLASS
30 Days to Become a Linux Pro 🚀
Command Line | Shell | Scripting | SysAdmin
```

* **Visual Elements:**

  * 🐧 Tux penguin
  * Terminal background (dark theme)
  * Green command prompt style text
  * Subtle code overlay
  * Clean tech font (Montserrat / Poppins / JetBrains Mono)

* **Suggested Layout:**

```
-----------------------------------------------------
|  🐧  LINUX MASTERCLASS                            |
|                                                    |
|  30 Days to Become a Linux Pro 🚀                 |
|                                                    |
|  Command Line • Shell • Scripting • SysAdmin      |
|                                                    |
|  github.com/yourname/linux-masterclass            |
-----------------------------------------------------
```

* **Save Banner:** `images/banner.png`
* Add to README top:

```markdown
<p align="center">
  <img src="images/banner.png" alt="Linux Masterclass Banner" />
</p>
```

---

## 📚 Complete 30-Day Linux Learning Repository Structure

```
linux-masterclass/
│
├── README.md
├── images/
│   └── banner.png
│
├── Day-01-Introduction/
│   ├── README.md
│   └── labs.md
│
├── Day-02-Basic-Commands/
├── Day-03-File-Management/
├── Day-04-File-Permissions/
├── Day-05-Process-Management/
├── Day-06-User-Management/
├── Day-07-Package-Management/
├── Day-08-Text-Editors/
├── Day-09-Redirection-Pipes/
├── Day-10-Grep-Sed-Awk/
│
├── Day-11-Environment-Variables/
├── Day-12-Shell-Scripting-Basics/
├── Day-13-Conditional-Statements/
├── Day-14-Loops/
├── Day-15-Functions/
│
├── Day-16-Crontab/
├── Day-17-System-Monitoring/
├── Day-18-Networking-Basics/
├── Day-19-SSH/
├── Day-20-Firewall/
│
├── Day-21-Log-Management/
├── Day-22-Storage-Management/
├── Day-23-LVM/
├── Day-24-Systemd/
├── Day-25-Advanced-Scripting/
├── Day-26-Project-1/
├── Day-27-Project-2/
└── Day-28-Final-Assessment/
```

---

## 🧪 Day 1 Lab Exercises – Linux Introduction & File System

### Exercise 1 – Create Folder Structure

Create the following:

```
linux-lab/
 ├── project/
 │   ├── file1.txt
 │   └── file2.txt
 └── backup/
```

**Solution:**

```bash
mkdir linux-lab
cd linux-lab
mkdir project backup
touch project/file1.txt project/file2.txt
```

---

### Exercise 2 – List Files

List all files including hidden files:

```bash
ls -la
```

---

### Exercise 3 – Check File Permissions

Check permissions of files:

```bash
ls -l
```

* `r` → Read
* `w` → Write
* `x` → Execute

Example output:

```
-rw-r--r-- 1 user user 0 Feb 14 12:00 file1.txt
```

---

### Exercise 4 – Create and Execute Script

Create `welcome.sh`:

```bash
nano welcome.sh
```

Add:

```bash
#!/bin/bash
echo "Welcome to Linux Masterclass"
```

Run:

```bash
chmod +x welcome.sh
./welcome.sh
```

---

## 🖼 Screenshots to Upload

Create an `images/` folder:

| Screenshot                 | Save As                               | Description                            |
| -------------------------- | ------------------------------------- | -------------------------------------- |
| Linux Architecture Diagram | `images/linux-architecture.png`       | Shows User → Shell → Kernel → Hardware |
| File System Tree Example   | `images/linux-filesystem-tree.png`    | Output of `tree /`                     |
| ls -l Command Example      | `images/ls-command-example.png`       | Shows file types & permissions         |
| File Permissions Example   | `images/file-permissions-example.png` | chmod demonstration                    |

Add screenshots in README like:

```markdown
## Linux Architecture Diagram
![Linux Architecture](images/linux-architecture.png)
```

---



Do you want me to do that next?
