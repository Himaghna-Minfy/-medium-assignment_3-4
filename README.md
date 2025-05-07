Screenshot of conflict
<img width="522" alt="conflict" src="https://github.com/user-attachments/assets/170fd767-6179-4e10-b5d0-3c684a058a45" />


screenshot of resolved conflict
<img width="367" alt="solved conflict" src="https://github.com/user-attachments/assets/404b62bd-f9e3-4c57-a9ec-18a1b541b511" />


screenshot of successfull merge pull requests
<img width="643" alt="successfull merge pull" src="https://github.com/user-attachments/assets/da2d45fe-7b9a-40f3-8192-8e50fc856623" />

Both the feature/update-styling and feature/add-content branches made changes to the same section of the index.html file, which caused a merge conflict when attempting to merge the second branch.
GitHub flagged the conflict during the pull request. I clicked “Resolve conflicts”, which showed both versions of the conflicting code. I manually edited the file to keep the necessary parts from both branches, removed the conflict markers (<<<<<<<, =======, >>>>>>>), and then committed the resolved version.
After resolving, I completed the pull request merge successfully.



ASSIGNMENT 4

since to run npm admin permissions were required so couldnt do that, learnt about the tools asked in the assignment


Husky is a Git hook manager that helps automate scripts before or after Git actions like commit, push, etc.
It ensures consistent workflows by enforcing checks (like linting or tests) before code is committed.
It integrates easily with tools like ESLint, Prettier, or custom scripts.
Husky works by configuring hooks in your project’s .husky directory.
It helps teams catch issues early and maintain code quality across contributors.

lint-staged allows us to only lint files that are staged for commit, making it faster and more efficient.

ESLint checks for syntax errors and code quality in JavaScript.

Prettier automatically formats code to maintain consistency.

commitlint checks that commit messages follow a specific convention (like Conventional Commits).

GitHub Actions allows you to automate tasks such as running tests or linters every time code is pushed to the repository.
