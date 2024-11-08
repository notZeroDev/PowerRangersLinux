# NO NAME
## Whoami command
This command is used to print the name of the current user.
<pre>
  <code>
    whoami
  </code>
</pre>
>format of command


## man command
It is used to print the manual of the command that can be helpful in understanding the command , it print a lot of information but sometimes you want to know quick overview of a command so use [this site](https://tldr.sh/).
<pre>
  <code>
    man <command>
    man -k <keywrod> 
  </code>
</pre>
>The second line is used to list all commands related to a keyword.
## pwd command
This command prints the current working directory, displaying your location within the file system. 
<pre>
  <code>
    pwd
  </code>
</pre>


## ls command
This command lists all contents of a directory. 
<pre>
  <code>
    ls
  </code>
</pre>
>The default
<pre>
  <code>
    ls -l
  </code>
</pre>
>This command lists detailed information about the directory's contents, including permissions, number of links, owner, group, size in bytes, and modification date.
<pre>
  <code>
    ls -a
  </code>
</pre>
>This command lists all files, including hidden files that start with a dot.


## cd command
This command changes the current directory.
<pre>
  <code>
    cd one
  </code>
</pre>
>This command navigates you to a directory called "one" that is inside the folder you are currently in.
<pre>
  <code>
    cd
  </code>
</pre>
>This command navigates you to the home directory.
<pre>
  <code>
    cd ..
  </code>
</pre>
>This command moves up one level in the directory hierarchy.


## mkdir command
This command makes new directory.
<pre>
  <code>
    mkdir one
    mkdir one two three
  </code>
</pre>
>You can make single directory as first line or multiple directories as second line.
<pre>
  <code>
    mkdir -p one/two/three/four
  </code>
</pre>
>You can make nested directory structure.
## touch command
This command creats an empty file.
<pre>
  <code>
    touch 1.txt 
    touch 1.txt 2 3 4
  </code>
</pre>
>You can create single file as first line or multiple files as second line.


## rm command
This command removes a file.
<pre>
  <code>
    rm 1.txt
    rm 1.txt 2 3 4 5
  </code>
</pre>
>You can remove single file as first line or multiple files as second line.
<pre>
  <code>
    rm -r one
    rmdir one
  </code>
</pre>
>This commands remove a directory.
<pre>
  <code>
    rm -rf one
  </code>
</pre>
>This command removes a directory and its contents.
## open command
This command didn’t work with me but we can use xdg-open instead it , this command opens a file.
<pre>
  <code>
    xdg-open 1.txt
  </code>
</pre>
>This command opens a file by default program.


## mv command
This command moves files.
<pre>
  <code>
    mv one two
  </code>
</pre>
>This file ‘one’ had been renamed as ‘two’.
<pre>
  <code>
    mv 1.txt /home/user/three/one/two/three/10.txt
  </code>
</pre>
>This command moves file ‘1,txt’ to the folder ‘three’ and rename it ‘10.txt’ , you should write all path after the file to move it to specific directory.


## cp command
This command copies a file.
<pre>
  <code>
    cd 1 2
  </code>
</pre>
>I think the outcome is the same outcome of mv 1 2
<pre>
  <code>
    cp 1.txt /home/killua/three/one/two/three/four
  </code>
</pre>
>This command copies file ‘1.txt’ to this path , I think the difference between.
