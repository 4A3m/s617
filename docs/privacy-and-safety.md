# 🔐 Privacy & Safety - Read Before You Publish

This is a **public** repository, and your portfolio will be public too. That's the
point - public work is what a recruiter can see. But public also means *permanent* and
*visible to anyone*, so a few habits protect you. These aren't just rules; they're the
same instincts the course is teaching you to apply everywhere.

## Your email is in every commit
Git stamps an email on every commit, and once it's pushed to a public repo that address
is in the history forever - easy for spammers to harvest. If you followed
**[Guide 1, Step 4](00-student-setup-guide.md)**, your commits use GitHub's private
`noreply` address instead of your real one. If you skipped it, do it *before* you push.

## Never commit secrets
Passwords, API keys, SSH **private** keys, `.env` files, tokens - none of it belongs in
a repo, public **or** private.

> **Git history is forever.** Deleting a secret in a later commit does **not** remove it
> from history. If you push a key, assume it's compromised and rotate it immediately.

This repo ships a `.gitignore` that blocks the usual offenders, GitHub's **secret
scanning** will warn you if a known key type slips through - but your habit of running
`git status` before every commit is the real defense.

## Sanitize your lab work
When you document a lab, **redact anything that identifies a real system**: real IP
addresses, hostnames, live target data, full packet captures. Describe the *technique*
and the *finding*, not a map to someone's network. Intentionally vulnerable machines stay
on an **isolated lab network** - never the open internet (see [DISCLAIMER.md](../DISCLAIMER.md)).

## Decide what to expose about yourself
Your portfolio can list a way to contact you - but choose deliberately, the way you'd
assess anyone's public footprint:
- **A dedicated email** (not your primary personal one) and a **LinkedIn** link are the
  professional norm. Avoid putting a **phone number** or home details on a public page.
- Before you publish, look yourself up the way an outsider would. Publish only what you're
  comfortable with the whole internet seeing.

## Being listed is your choice
Adding yourself to the members directory is **opt-in**. You can use a handle instead of
your legal name, list only a GitHub link, or choose not to be listed at all. Any of those
is completely fine - no explanation needed.

## Your repo visibility is yours to control
Every repo has a visibility setting: **private** (only you and people you invite) or
**public** (anyone). Change it anytime under **repo -> Settings -> General -> Change
visibility**. Know how to flip it both ways - controlling who sees your work is a core skill.
