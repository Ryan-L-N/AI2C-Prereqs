# Hands-On: Git Remotes, Push/Pull, Forking, and Pull Requests

These exercises walk through working with Git remotes and contributing to shared repositories via forks and pull requests.

---

### Exercise 0: Setup Environment

**Goal**: Create a local and remote repository.  

---

### Exercise 1: Add a Remote Repository

**Goal**: Link your local project to a remote GitHub repository.

This step sets up your local repository to "track" the remote repository under the name `origin`.



✅ *Check*: Run `git remote -v` to verify the remote is added.

---

### Exercise 2: Push Your Code to GitHub

**Goal**: Push local commits to the remote repository.


✅ *Check*: Visit the GitHub repo and confirm your code appears.

🎯 What does the `-u` flag mean?

Note:  You may be prompted to login.  If you are, follow these steps to generate an access token for your device.

1. Go to User settings > Developer Settings > Personal Access Tokens > Fine-grained tokens > Generate new token
2. Name the token
3. Set an expiration date for the access token.  (Or set it to none if you are using a personal device)
4. Select All Repositories
5. Add Permissions > Contents. Change contents to Read and Write.  Generate the token

Before closing the screen, copy the token, and use it as your password!

---

### Exercise 3: Pull Changes from a Remote

**Goal**: Sync your local project with changes from the remote.

Two options:


✅ *Check*: Git should update your local files if there are changes on GitHub.

🎯 Make some new commits locally, and make some new commits on the remote, then pull.  What happens?

---

### Exercise 4: Fork a Repository

**Goal**: Create your own copy of someone else's GitHub repository.

1. Go to a public GitHub repository (e.g., https://github.com/shafe123/Spoon-Knife).
2. Click the **Fork** button on the top right.

✅ *Check*: You should now have a copy under your own GitHub account.

---

### Exercise 5: Clone a Forked Repository

**Goal**: Work on your forked copy locally.


✅ *Check*: You now have a local copy of the forked repo.

---

### Exercise 6: Make a Change and Push to Your Fork

**Goal**: Make a change and push it to your GitHub fork.


✅ *Check*: Confirm the change is visible in your GitHub fork.

---

### Exercise 7: Create a Pull Request

**Goal**: Submit your change back to the original repository.

✅ *Check*: Your pull request should now appear in the original repo’s list of PRs.

---

### Exercise 8: Add an Upstream Remote (Optional)

**Goal**: Keep your fork in sync with the original repository.


✅ *Check*: You can now pull updates from the original repo into your fork.

🎯 What command does fetch and merge in one?