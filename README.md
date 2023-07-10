# linuxcommands
The document is about linux command and description
## Essential Linux commands 100 ##
1. File Operations
   ls - list all files and directories in present working directory
   ls -R - lists filed in sub directories as well
   ls -a - show all hidden files
   ls -al : list files and directories with detailed info like permission size owner,etc..
   cd directoryname - changes the directory
   cd .. : Moves one level up
   pwd : displays the present working directory
   cat > filename : Create a new file
   cate filename : Displays the file content
   cat file1 file2 > file3 : Join two files f1 and f2 and stores new file in f3
   touch filename : Creates or modifies a flie
   rm filename : delete a file
   cp source destination : Copies file from source path to destination path
   mv source destination : move file from source path to destination path
   find / -name filename : finds a file or directory by its name starting from root
   file filename : Determines file type
   less filename : views the content page by page
   head filename : views first ten line of file
   tail filename : views last ten lines of file
   lsof : shows which file are opened by which process
   du -h --max-depth=1 : shows size of each directory.Use --max-depth=1 to limit the output to the current directory and its immediate children
   fdisk : disk partition manipulation command
   
3. Directory Operations   
   mkdir directoryname : creates new directory in present working directory
   rmdir directory name : Deletes a directory
   cp -r source destination : copies directories recrussively
   mv olddir newdir : Renames directories
   find / -type d -name directoryname : Finds a directory starting from root

   

   
   
