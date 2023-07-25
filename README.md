# radixClubDao
## Steps to Setup Your Project Locally 

1. Create the folder where you want to store the project locally.
2. Navigate to that folder using the command line:
    ```bash
    cd path_to_your_project_folder
    ```
3. Once you are in that folder, initialize it as a git repository:
    ```bash
    git init
    ```
    You should see a response like: 
    ```
    Initialized empty Git repository in C:/Users/matth/radixClubDao/.git/
    ```

4. Add the remote repository to your local repository:
    ```bash
    git remote add origin git@github.com:mrussotti/radixClubDao.git
    ```

5. Verify the remote repository:
    ```bash
    git remote -v
    ```
    You should get a response like:
    ```
    origin  git@github.com:mrussotti/radixClubDao.git (fetch)
    origin  git@github.com:mrussotti/radixClubDao.git (push)
    ```
    If you see this, it means you are set up correctly.

6. Pull the latest changes from the remote to the local repository:
    ```bash
    git pull
    ```

7. Create a new branch so you can start programming:
    ```bash
    git checkout -b <replace_with_feature_branch_name>
    ```

Happy Coding!

