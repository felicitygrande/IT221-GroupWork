**Instructions**

_**The plan**_:
Illustrate how git workflows work with multiple people. For this assignment we will be accessing each other's files and editing them while everyone works in the same Git Branch.

_**The complication**_:
Occasionaly, this workflow can lead to merge conflicts. In order to finish a commit and push your work you must resolve any conflicts that arise.

_**The Instructions (commands below)**_:
1. **Clone the repository**
    ```
    git clone <repository address>
    ```
2. **Navigate to your repository and open code**
    
    ```
    cd IT221-GroupWork
    ```
    
    ```
    code .
    ```
3. **Checkout the development branch (specify what branch you are working in __VERY IMPORTANT__)**
    ```
    git checkout development
    ```
4. **Add a new text file with your name as the filename**
    ```
    Example: jesse.harlan.txt
    ```
5. **Add a message inside your file (School appropriate please)**
    ```
    Jesse was here
    ```
6. **Make a change in someone else's file**
    ```
    Use code to drop a change in someone elses file
    ```
7. **__Make sure you save all changes!__**
8. **Track your changes with git (stage the files)**
    ```
    git add .
    ```
9. **Commit your changes (take a snapshot)**
    ```
    git commit -m "your commit message here"
    ```
11. **Check to make sure you have the latest copy of the code before pushing**
    ```
    git pull origin development
    ```
10. **Push your changes up to github**
    ```
    git push origin development
    ```

**Side note: If you encounter a conflict**
    ```
    You must resolve any merge conflicts that occur before progressing further. Read the conflict carefully (you can display it again with git status). The basic process is like so:

    1. Open the conflicting files
    2. Choose which section to keep (or modify both sections to satisy both changes).
    3. Check to make sure your code __WORKS__
    4. Track your changes again
    5. Commit your changes again.
    6. Finish the push or merge.
    ```

