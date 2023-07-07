# TRASH

<img alt="trash icon" src="resources/icon/playstore.png" height="150px"> 

Trash is a program created using a shell language to move files to the trash folder, so they are not immediately deleted.

Note : I created this program so that I can delete files in Termux, which doesn't have a desktop environment, without deleting them directly.

## The Technology Used Is
- Shell
- LunarVim

## How to install
```
// Run this command in your terminal

curl -o trash_installer.sh https://raw.githubusercontent.com/AerellDev/Trash/main/trash_installer.sh | bash
```

## How to use
```
// help or more command
trash -h

// delete file/dir to trash folder
trash del <file/dir>

// cleaning trash folder
trash empty
```

## How to uninstall
```
// Run this command in your terminal

curl -o trash_uninstaller.sh https://raw.githubusercontent.com/AerellDev/Trash/main/trash_uninstaller.sh | bash
```

Thanks for reading...!
