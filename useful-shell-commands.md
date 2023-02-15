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



1. show present working directory (where you are)
    ```bat
    pwd
    ```

0. list what is under the current working directory
    ```bat
    ls
    ```

    list what is under the current working directory, including the hidden files:

    ```bat
    ls -la
    ```

0. change working directory
    ```bat
    cd <your_working_directory>
    ```

0. auto-populate the rest of a long command/file name
    ```
    type the first unique few letters + tab key
    ```



0. **Don't want to type out the same command again? hit the `⬆` key to call out the previous command**



0. add a line of text to a file that you want to write

    ```bat
    echo Hello! My name is Winnie >> <filename>.<extension>
    ```
    
    Example:

    ```bat
    echo Hello! My name is Winnie >> winnietext.txt
    echo This is the second line in winnietext! >> winnietext.txt
    ```

0. display the text in a file

    ```bat
    cat winnietext.txt
    ```

0. replace all the text in a file with what you want to write
    ```bat
    echo I want to write this sentence instead of all texts that were here! > <filename>.<extension>
    ```


0. move up one level from your current working directory
    ```bat
    cd ..
    ```
0. remove a file **Dangerous! CANNOT be UNDO**
    ```bat
    rm <filename>.<extension>
    ```
0. show a list of previous command
    ```bat
    history
    ```

0. Create a new blank file under the current working directory

    Mac users:
    ```bat
    touch <newfilename>.<extention>
    ```

    Windows Users
    ```bat
    New-Item <newfilename>.<extention> -type file
    ```
0. Rename a file
    ```bat
    mv <oldfilename>.<extension> <newfilename>.<extension>
    ```