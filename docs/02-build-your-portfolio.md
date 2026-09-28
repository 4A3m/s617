
# Guide 3 - Build Your Portfolio Site

Now the real thing. You'll create your own repository, drop in a portfolio template, make it yours, and (as a stretch) publish it live on the web. **This repo is entirely yours** - separate from S617 - so it reads to a recruiter as your own work.

> Today's win is getting the template committed to your own repo. Getting it
> live on GitHub Pages is a great stretch goal - but if the clock beats you, that
> part is easy homework.

---

## Step 1 - Create your portfolio repo
Create a **new repository** named **exactly** `YOUR-USERNAME.github.io`
(all lowercase, your real username). *Why that name:* it publishes to the clean root
URL `https://your-username.github.io`, and it reads as 100% your own site. Make it **Public**.

> 📸 **Screenshot 01** - the "Create a new repository" form with the `username.github.io` name.
![Create repo](images/b01-create-repo.png)
![Create repo](images/b01-2-create-repo.png)
![Create repo](images/b01-3-create-repo.png)


## Step 2 - Get the template
Fork S617 repo 
<!-- ![fork](images/b02-fork.png) -->

Chose one of the templates in templates/portfolio/

plain-rename-to-index

![Template preview](../templates/portfolio/images/plain-rename-to-index.png)

cyber-rename-to-index

![Template preview](../templates/portfolio/images/cyber-rename-to-index.png)

cybergirl-rename-to-index

![Template preview](../templates/portfolio/images/cybergirl-rename-to-index.png)

cyberstar-rename-to-index

![Template preview](../templates/portfolio/images/cyberstar-rename-to-index.png)



From your **S617 fork**, open `templates/portfolio/index.html`, click **Raw**, and save
the file. Then add it to your new repo - the simplest way in the browser is
**Add file -> Upload files** on your new repo and drop `index.html` in.
*(Comfortable with the command line? Clone your new repo and copy `index.html` into it.)*

## Step 3 - Make it yours
Open `index.html` and fill in every spot marked with an `<!-- EDIT: ... -->` comment:
your name, role, a short about paragraph, your skills, and a couple of projects or lab
writeups. You don't need to touch the styling unless you want to.

> ✍️ Keep it honest and specific. "Built and documented a network-scanning lab with nmap"
> beats "passionate about cybersecurity." Recruiters read this first.

** Feel free to use AI to make the template yours ** 

![AI change](images/s03-ai-prompt.png)
Down the generated code

![AI change download](images/s03-ai-code-download.png)

Rename the file to index.html

![rename](images/s03-rename.png)

Your index file is working now locally in your computer

![local-index](images/s03-local-index.png)

**Review and edit your portfolio carefully** and save your changes.


## Step 4 - Commit and push
Commit your changes (in the browser, that's the **Commit changes** button; from the
command line, `git add`, `git commit`, `git push`).

![upload](images/s03-upload.png)

Drag or Choose your index.html file to upload it

![drag](images/s03-drag.png)

> 📸 **Screenshot 02** - your repo showing `index.html` committed.
![Committed](images/b02-committed.png)

## Step 5 *(stretch)* - Go live with GitHub Pages
**Settings -> Pages -> Build and deployment -> Source: Deploy from a branch -> `main` / root -> Save.**
Wait a minute or two, then visit `https://your-username.github.io`.

> 📸 **Screenshot 03** - the Pages settings screen, source set to `main`.
![Pages settings](images/b03-pages.png)

> 📸 **Screenshot 04** - the live portfolio in a browser.
![Live site](images/b04-live.png)

---

✅ **You have a portfolio.** Even before it's live, your repo link works - which is all
you need for the next guide.
