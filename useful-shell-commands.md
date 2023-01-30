# **Other useful shell commands**

**Note**: whenever you see a <>, replace it with your own value, **do NOT include the <>**

For example:

```
<your_username>
```

should be replaced with 

```
winnieywl
```

<br>

    ```bat

    ```

1. show present working directory (where you are)
    ```bat
    pwd
    ```

2. list what is under the current working directory
    ```bat
    ls
    ```

    list what is under the current working directory, including the hidden files:

    ```bat
    ls -la
    ```

3. change working directory
    ```bat
    cd <your_working_directory>
    ```
4. auto-populate the rest of a long command/file name
    ```
    type the first unique few letters + tab key
    ```
5. move up one level from your current working directory
    ```bat
    cd ..
    ```
6. remove a file **Dangerous! CANNOT be UNDO**
    ```bat
    rm <filename>.<extension>
    ```
7. show a list of previous command
    ```bat
    history
    ```
8. Don't want to type out the same command again? 
    ```
    hit up arrow key to call out the previous command
    ```
9. Create a new blank file under the current working directory

    Mac users:
    ```bat
    touch <newfilename>.<extention>
    ```

    Windows Users
    ```bat
    New-Item <newfilename>.<extention> -type file
    ```
10. Rename a file
    ```bat
    mv <oldfilename>.<extension> <newfilename>.<extension>
    ```