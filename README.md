<!--
MAINTAINER NOTES (hidden when rendered):
• Replace every <S617-ACCOUNT> with the real account/org name once it exists.
• Replace <EXAMPLE-REPO-URL> with the sandbox repo used for the practice loop.
• LICENSE: not chosen yet. Pick one before publishing publicly (see chat notes) -
  a permissive license (e.g. MIT) or a docs license (CC BY 4.0) are common for
  teaching repos. Decide with Prof. Algamal / the college.
• The DISCLAIMER below should be reviewed and approved by Prof. Algamal and the
  college's legal/compliance contact before this goes public under HCCC's name.
-->

# Cybersecurity Lab - Room S617 .Portfolio Workshop

The home base for the S617 GitHub workshop and the labs you'll complete through
the semester. Every lab you commit here and in your own repos becomes public proof
of what you can do - so that by the end of the term you don't *build* a portfolio,
you already have one.

> ## ⚠️ Disclaimer - Educational Use Only
> All materials in this repository are for **educational purposes only**, for use
> against systems you own or are explicitly authorized to test. Unauthorized access
> to computer systems is illegal. **Read the full terms in [DISCLAIMER.md](DISCLAIMER.md)
> before running any lab.**

> ## 🔐 Before you publish anything - read [docs/privacy-and-safety.md](docs/privacy-and-safety.md)
> This is a **public** repository. Your commits, your links, and anything you push
> here can be seen by anyone, permanently. The privacy guide shows you how to keep
> your email, your secrets, and your personal information safe. Read it first.

## Start here - the guides

Work through these in order. The first one is **pre-work**: come to the workshop
with a secured account already set up.

1. **[Setup your account securely](docs/00-student-setup-guide.md)** - do this *before* the workshop
2. **[Practice the Git loop](docs/01-practice-loop.md)** - a no-stakes warm-up
3. **[Build your portfolio site](docs/02-build-your-portfolio.md)** - your own page on GitHub Pages
4. **[Add yourself to the directory](docs/03-add-your-link.md)** - your first real pull request
- **[Privacy & Safety](docs/privacy-and-safety.md)** - read before you publish
- **[Git cheat sheet](CHEATSHEET.md)** - the commands you'll actually use

## How to use this repo

1. **Fork it** to your own account (the **Fork** button, top right).
2. **Clone your fork:**
   ```
   git clone git@github.com:YOUR-USERNAME/cyber-portfolio-workshop.git
   ```
3. **Link the original** so you can pull new labs all semester:
   ```
   git remote add upstream https://github.com/<S617-ACCOUNT>/cyber-portfolio-workshop.git
   git pull upstream main
   ```

## What's in here

- **`docs/`** - the step-by-step guides above.
- **`members/`** - the directory of everyone in S617. You add yourself here (see guide 4).
- **`templates/portfolio/`** - a portfolio template to copy into your own repo (see guide 3... I mean guide 3 = build).
- **`labs/`** - each workshop adds a lab here. Pull them from upstream as they're released.

## The semester contract

> Every lab. Committed. Documented. That's the whole trick.

## After you graduate

S617 is built by HCCC cybersecurity students - and it keeps growing after you leave.
Alumni are welcome to come back, contribute new labs, and mentor the next cohort.
Graduating isn't an exit; it's a move from student to contributor.
