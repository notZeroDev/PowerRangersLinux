# LINUX Commands
- whoami
    - this command is used to print the user name of the currently logged in to the terminal.
    
    ```jsx
    whoami 
    ```
    
- man
    - this command will help you to understand the other commands just **man<command>**
    
    ```jsx
    man
    ```
    
- clear
    - this command is used to clear all the previous commands.
    
    ```jsx
    clear
    ```
    
- pwd
    - print working directory is used to print the current folder path.
    
    ```jsx
    pwd
    ```
    
- ls
    - this command is used to list all the files that the folder contains.
    
    ```jsx
    ls
    ```
    
- cd
    - change directory is used to move into a specific folder.
    
    ```jsx
    cd
    cd ..  //to move back
    ```
- mkdir
    - this command is used to create a folder.
    
    ```jsx
    mkdir folder1
    ```
    
    - you can create multiple folders with one command
    
    ```jsx
    mkdir folder1 folder2 folder3
    ```
    
    - you can also create multiplied nested folders by adding -p
    
    ```jsx
    mkdir -p folders/folder1
    ```
    
- touch
    - this command is used to create an empty file.
    
    ```jsx
    touch newfile
    ```
- rmdir
    - this command is used to delete a folder, that must be empty.
    
    ```jsx
    rmdir folder1
    ```
    
- rm
    - this command is used to delete files or folders.
    
    ```jsx
    rm file or folder name
    ```
    
- open
    - this command is used to open a file.
    
    ```jsx
    open filename
    ```
    
- mv
    - this command is used to move a file. you specify the current path and the new path.
    
    ```jsx
    toch file
    mv file newfile
    ```
    
    - also you can move a file to a folder.
    
    ```jsx
    mv file folder/
    ```
    
- cp
    - this command is used to copy a file .
    
    ```jsx
    touch file1
    cp file1 newfile
    ```
    
    > **output**: file1 copied to newfile
    > 
    - to copy folder you need to add -r.

    ```jsx
    mkdir folder
    cp -r folder newfolder
    ```
    
    > **output**: file1 copied to newfile
    >
