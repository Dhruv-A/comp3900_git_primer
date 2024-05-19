# comp3900_git_primer

```
repository/
├── app.py
├── templates/
│   ├── index.html
│   └── calculator.html
```

To run this application use `python3 main.py`. You will need to first install `Python` which can be done online at https://www.python.org/downloads/ and you will need to install any necessary dependencies such as Flask using `pip install Flask` on the commandline after installing Python.

## Exercises

There are some bugs in this code and features we need to add. To make sure you have correctly installed Flask and cloned this repo, when you run the application and open the link in your browser (http://127.0.0.1:5000/) you should see a welcome page that says "Welcome to COMP3900".

1. We need to make a small modification as this page should include COMP9900 as well. Add COMP9900 to the greeting message in a new branch. To create a new branch and switch to it you can use `git checkout -b welcome_message_renaming`. Then make the necessary changes and add them using `git add <filename>` and commit them with a meaningful commit message using `git commit -m <write your commit message here>`.
2. You will need to show your tutor you made this change so **DO NOT merge this branch into `main` or delete it.** However, you should push it to the remote branch using `git push`.
3. We are going to create a new branch based off the one we are currently on to fix some other issues. Use `git checkout -b welcome_and_calculator_fix` to switch to a new branch where we will debug the calculator. If you try using the calculator right now, you will see that it does not add the numbers but instead multiplies them.
4. Fix this issue and then commit your change to git. This time, we want to merge it into a branch called `incorrect_branch_name` using `git merge incorrect_branch_name`. However, when you try to merge it in, you will encounter a merge conflict as there are already changes in the other branch. Remove the other branch's changes and replace them with your fix to the COMP[39]900 welcome message.
5. Once the code has been merged, push it to Github (the remote version of your branch) using `git push`. If it tells you your branch does not have a remote version, then use the suggested command it gives you.
6. Now, on Github it will give you a message saying there were recent changes to a branch and ask you if you want to submit a pull request. Create the pull request but **DO NOT** accept it. You will need to show your tutor the unapproved pull request.
