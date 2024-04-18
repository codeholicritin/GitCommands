# <center>Git Stash Commands<center>

- ### Stash Changes: 
    > Stash changes in the working directory:

    ```
    git stash
    ```
- ### Stash with a Message: 
    > Stash changes with a custom message:

    ```
    git stash save "Your message here"
    ```
- ### Stash Untracked Files: 
    >  Stash untracked files along with tracked files:

    ```
    git stash -u
    ```

- ### List Stashes: 
    > List all stashes:

    ```
    git stash list
    ```
- ### Apply Stash: 
    > Apply the most recent stash

    ```
    git stash apply
    ```
- ### Apply Specific Stash: 
    > Apply a specific stash:

    ```
    git stash apply stash@{n}
    ```

- ### Apply Stash and Remove: 
    > Apply the most recent stash and remove it from the stash list:
    ```
    git stash pop
    ```

- ### Apply and Drop Stash
    > Apply a specific stash and remove it from the stash list:
    ```
    git stash pop stash@{n}
    ```

- ### Apply Stash to a Different Branch: 
     > Apply a stash to a different branch:

    ```
    git stash branch <branch_name>
    ```

- ### Drop Stash: 
    > Remove the most recent stash from the stash list:
    ```
    git stash drop
    ```

- ### Drop Specific Stash: 
    > Remove a specific stash from the stash list:

    ```
    git stash drop stash@{n}
    ```

- ### Clear Stash: 
    > Remove all stashes:

    ```
    git stash clear
    ```
