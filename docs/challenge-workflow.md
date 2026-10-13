# Web-Challenges Workflow

From now on, please try to follow this workflow when working on challenges. 

It helps you practicing the git branches commands every day. Practice makes perfect!

1. In the `web-challenges` repository, make sure you are on the `main` branch.
2. Create a folder with the name of the session. For example, `css-basic`.
3. Navigate to the folder created in step 2, e.g., `css-basics`.
4. Once you are inside the folder, download **all** the challenges.
5. Navigate back to the main folder of the repository, `web-challenges`.
6. Add the files and create a commit:
   ```bash
   git add .
   git commit -m "Add a comment"
   ```
7. Push to the `main` branch:
   ```bash
   git push origin main
   ```
8. Decide on which challenge you want to work.
9. Create a **new** branch dedicated to that challenge **only**.

   ```bash
	 git switch -c challenge-name
   ```
10. Focus solely on that challenge. While working, remember to make multiple `commits`.
   ```bash
git add . 
git commit -m "Add ..."
   ```
11. When you are finished, push your branch to GitHub:
   ```bash
git push origin challenge-name
   ```
12. Create a pull request (PR) on the GitHub page.
13. **Merge the PR yourself without waiting for or requesting a review.** These PRs are only for practice purposes, so no one needs to review them before you merge them.
14. Once the PR has been merged, go back to your computer and switch back to main:
   ```bash
git switch main
   ```
15. Pull the newly merged changes from GitHub:
   ```bash
git pull origin main
   ```
16. You are now ready to start the next challenge/session. Repeat the workflow from step 2.
