# Lab 1 Report  
1. no arguments
   1. cd
      * ![Image]()
      * The working directory was /home
      * I got this output because there was no argument so the workings directory did not change
      * This is not an error
   2. ls
      * ![Image]()
      * The working directory was /home
      * I got this output because the working directory was /home so ls only shows lecture1 as that is the only file on /home
      * This is not an error
   3. cat
      * ![Image]()
      * The working directory was /home
      * I got this output because there is no argument so there is nothing for cat to show since there is no file that it can output
      * This is an error
  
2. directory as an argument
   1. cd
      * ![Image]()
      * The working directory when the command was run was /home
      * I got this output because the argument was a directory which means that the working directory will change to whatever the argument is if it exists
      * This is not an error
   2. ls
      * ![Image]()
      * The working directory when the command was run was /home/lecture1
      * I got this output because ls was trying to find lecture1 within lecture1 and that doesn't exist. However, if the working directory was /home, then it would work since lecture1 would exist within /home
      * This is not an error
   3. cat
      * ![Image]()
      * The working directory when the command was run was /home
      * I got this output because cat concatenates files and since the argument is a directory, there are no contents to print
      * This is not an error
3. file as an argument
   1. cd
      * ![Image]()
      * The working directory is /home/lecture1
      * I got this output because cd looks to change working directories, but since the argument is a file there is nothing for it to change to
      * This is not an error
   2. ls
      * ![Image]()
      * The working directory is .home/lecture1
      * I got this output because ls lists out the files and directories in the path, but since the file is not a directory and the output is only itself
      * This is not an error
   3. cat
      * ![Image]()
      * The working directory is /home/lecture1
      * I got this output because cat looks to concatenate files and Hello.java is a file, so it prints out all its contents
      * This is not an error
