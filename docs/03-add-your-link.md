<!-- MAINTAINER: screenshots in docs/images/. -->

# Guide 4 - Add Yourself to the Directory *(your first real PR)*

Time to put your name on the S617 member directory - and make your first real pull
request. This is the same loop you practiced in Guide 2, now for keeps.

---

## Step 1 - Copy the template
In your **S617 fork**, go to the `members/` folder. Copy `_TEMPLATE.md` to a **new
file** named after you: `members/firstname-lastname.md` (or `members/your-handle.md`).

> **You only add your *own* new file** - you never edit a shared list. That's why 25
> people can do this at once without a single merge conflict.

## Step 2 - Fill it in
Add your name, focus, and links. Point **Portfolio** at your repo now; swap in your live
`username.github.io` URL once Pages is up. (See `members/EXAMPLE-alex-rivera.md` for the format.)

## Step 3 - Commit and push to your fork
```bash
git add members/firstname-lastname.md
git commit -m "Add <your name> to the directory"
git push
```

> 📸 **Screenshot 01** - your new members file, committed to your fork.
<!-- ![Members file](images/a01-members-file.png) -->

## Step 4 - Open the pull request
On your fork, click **Compare & pull request**, give it a clear title
("Add <your name> to the directory"), and **Create pull request**. Your entry is now
*proposed* to S617; once it's reviewed and merged, you're in the directory.

> 📸 **Screenshot 02** - the pull request open against the S617 repo.
<!-- ![Open PR](images/a02-pr.png) -->

---

✅ **That's a real contribution to a public repository** - the exact skill employers
look for. Your commit history now shows you can collaborate with Git.
