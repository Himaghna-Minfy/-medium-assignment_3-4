Screenshot of conflict
<img width="522" alt="conflict" src="https://github.com/user-attachments/assets/170fd767-6179-4e10-b5d0-3c684a058a45" />


screenshot of resolved conflict
<img width="367" alt="solved conflict" src="https://github.com/user-attachments/assets/404b62bd-f9e3-4c57-a9ec-18a1b541b511" />


screenshot of successfull merge pull requests
<img width="643" alt="successfull merge pull" src="https://github.com/user-attachments/assets/da2d45fe-7b9a-40f3-8192-8e50fc856623" />

Both the feature/update-styling and feature/add-content branches made changes to the same section of the index.html file, which caused a merge conflict when attempting to merge the second branch.
GitHub flagged the conflict during the pull request. I clicked “Resolve conflicts”, which showed both versions of the conflicting code. I manually edited the file to keep the necessary parts from both branches, removed the conflict markers (<<<<<<<, =======, >>>>>>>), and then committed the resolved version.
After resolving, I completed the pull request merge successfully.
