# Timestamped directory backup
Create a backup of a directory and save it to another location.  The current timestamp is appended to the new folder name.

```
./backup-directory.sh <directory-to-copy> <copy-into-directory>
```

## Notes
I have verified that a copy and paste with KDE plasma dolphin produces exactly the same result as
```
cp -a <dir to copy>/. <copy to dir>
```