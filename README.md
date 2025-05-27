## 🎉 Welcome to the Git Workshop!

Welcome to your hands-on journey with Git and GitHub! This workshop will walk you through the essential open-source workflow: **forking a repository**, **making changes**, and **submitting a pull request (PR)**.

### 🧠 What You’ll Learn

* How to fork a repository on GitHub
* How to clone the forked repository to your local machine
* How to create a new branch, make a change, and push it
* How to submit a PR to the original repository

---

### 📌 Your Task:

1. **Fork this repository**

   * Click the **Fork** button at the top-right of this page.

2. **Clone your fork to your local machine**

   ```bash
   git clone https://github.com/your-username/git-workshop
   cd git-workshop
   ```

3. **Create a new branch (recommended)**

   ```bash
   git checkout -b add-your-name
   ```

4. **Add your name and one fun fact to the `contributors.md` file**

   * Open `contributors.md` in a code editor and add a line like:

     ```md
     - Manee - Loves coding while sipping coffee ☕
     ```

5. **Commit your change**

   ```bash
   git add contributors.md
   git commit -m "Add Manee to contributors list"
   ```

6. **Push your branch to GitHub**

   ```bash
   git push origin add-your-name
   ```

7. **Create a Pull Request**

   * Go to your fork on GitHub.
   * Click "Compare & pull request."
   * Add a title and description, then click **Create pull request**.

---

### ✅ Done? Great!

Once your PR is merged, you’ll see your name on the Wall of Contributors. 🎉

Feel free to explore others’ contributions and ask questions. Happy Git-ing! 🚀
