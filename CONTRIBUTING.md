# 📃 Contribution Guide

## 🤔 How to contribute?

Here are the steps you can follow to start contributing:

**Step 1:** From the issues page, select an issue which you think you can solve.

**Step 2:** Tag one of the Contributors, or the owner to assign the issue you selected to you.

**Step 3:** Fork the repository using the `Fork` option on the top-right corner of the page.

**Step 4:** Clone forked version on your local machine:

```git
git clone https://github.com/<your_github_username>/creativity-doanythingyouwant.git
```

**Step 5:** Go inside cloned folder and add the original repository as `upstream`:

```git
git remote add upstream https://github.com/csellis/creativity-doanythingyouwant.git
```

**Step 6:** Open the project on your local machine

**Step 7:** Checkout to a new branch:

```git
git brach -b <branch_name>
```

(you can use the branch name as: 'mybranch')

**Step 8:** Make the desired changes to the code base. Also, before moving to the next step, make sure:

- [x] Code follows the style guidelines of this project
- [x] You have performed a self-review of my your own code
- [x] You have commented your code, particularly in hard-to-understand areas
- [x] You have made corresponding changes to the documentation
- [x] Your changes generate no new warnings

**Step 9:** Stage the changes, create a commit, and finally push the code to your forked repository:

```git
# stage all the changes
git add .

# commit the staged changes
git commit -m "<appropriate_commit_message>"

# push the code
git push origin <branch_name>
```

**Step 9:** Create a pull request:

1. Go to the `pull requests` page on the original repository.
2. Click on `compare & pull request` option visible on the top.
3. Follow the Pull Request template provided to add the details.
4. Now click on `Create pull request`.

Then Discuss with the mentors if any change is required on the pull request, before it gets merged!

That it 🎉