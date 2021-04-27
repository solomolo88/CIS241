
**rm** - A command used to remove a file from the file system. Use the '-r' flag to remove recursively. Use the '-f' flag to force the operation without checking with the user.
```
rm -rf folderOne
```
#To remove an empty directory, use the '-d' flag
#The following would remove the folder 'hello', provided it's has no content.
```
rm -d hello
```

**permissions** - NOT A COMMAND. Permissions are shown on the console in the following format
```
lrwxrwxrwx
```
#The first character indicates the type of object, directory or file
#The second, third, and fourth characters indicate the permissions granted to a particular group
#R-read, W-write,X-eXecute.
#The first grouping of 'rwx' is user permissions, second is group, and third is all others.
#A '-' in the slot of a given character indicates that action not being permitted to the group.

**chmod** - A command used to change the permissions of an indicated file
#Rescind read permissions for the user on the file 'hello.sh
```
chmod u-r hello.sh
```

**mkdir** - A command to create a directory of the passed in value
#Create an empty directory (folder) with the name 'hello'.
```
mkdir hello
```

**touch** -A command which may be used to create a file. It also updates the timestamp of that file
#create a file named 'stoptouchingme'
```
touch stoptouchingme
```

**cp** - A command which copies a given file to a specificed destination
#copy the file 'happy' to the directory 'new'
```
cp happy/ newDir/
```

**mv** - A command which moves a given file to a specified destination
#move 'myDir' to 'myDownloads'
```
mv myDir/ myDownloads/
```

**chown** - A command which changes the ownership of a given file
#EXAMPLE HERE
```
TODO
```


