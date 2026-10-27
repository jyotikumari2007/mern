# Assignment 3 – Terminal Navigation Practice Sheet

## Objective
To learn basic terminal commands for navigating folders, creating files, copying, renaming, deleting files, and opening folders in VS Code.

## 1. Common Terminal Commands

| No. | Task | macOS / Linux / Git Bash | Windows PowerShell |
|---|---|---|---|
| 1 | Show current folder | `pwd` | `pwd` |
| 2 | List files | `ls` | `ls` |
| 3 | Show hidden files and details | `ls -la` | `ls -Force` |
| 4 | Create a folder | `mkdir practice` | `mkdir practice` |
| 5 | Enter a folder | `cd practice` | `cd practice` |
| 6 | Create an empty file | `touch index.html` | `New-Item index.html -ItemType File` |
| 7 | Create nested folders | `mkdir -p css/images` | `mkdir css/images` |
| 8 | Go up one level | `cd ..` | `cd ..` |
| 9 | Go to home directory | `cd ~` | `cd ~` |
| 10 | Copy a file | `cp index.html backup.html` | `Copy-Item index.html backup.html` |
| 11 | Rename a file | `mv backup.html old.html` | `Rename-Item backup.html old.html` |
| 12 | Delete a file | `rm old.html` | `Remove-Item old.html` |
| 13 | Delete a folder | `rm -r css` | `Remove-Item css -Recurse` |
| 14 | Display file contents | `cat index.html` | `Get-Content index.html` |
| 15 | Clear the screen | `clear` | `cls` |
| 16 | Open folder in VS Code | `code .` | `code .` |

## 2. Practice Exercise

Starting from the home directory, create a website folder with the following structure:

```text
website/
├── index.html
├── css/
│   └── style.css
└── images/
```

### Commands Used in Windows PowerShell

**Step 1: Go to the home directory**

```powershell
cd ~
```

**Step 2: Create the folders**

```powershell
mkdir website
mkdir website/css
mkdir website/images
```

**Step 3: Create the files**

```powershell
New-Item website/index.html -ItemType File
New-Item website/css/style.css -ItemType File
```

**Step 4: Enter the CSS folder and return to website**

```powershell
cd website/css
cd ..
```

**Step 5: List all files and folders recursively**

```powershell
Get-ChildItem -Recurse
```

**Step 6: Rename index.html to home.html and back**

```powershell
Rename-Item index.html home.html
Rename-Item home.html index.html
```

**Step 7: Open the website folder in VS Code**

```powershell
code .
```

## Conclusion

This practice sheet explains basic terminal navigation and file management commands. These commands help developers create project folders, manage files, and work efficiently with Visual Studio Code.