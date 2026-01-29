# Exercise 04 — Merge Conflicts (Resolving Them Safely)

In this exercise you will learn how to:

- Understand what a merge conflict is
- See how conflicts happen in real projects
- Resolve a simple merge conflict safely
- Update a Pull Request after fixing a conflict
- Follow the same conflict-resolution process used in real Parents for Scouting, Inc. (PFSI) projects

---

## 🛡️ Safety Reminder

This is a public training sandbox.

Do NOT:
- Add any real personal data (especially youth data)
- Add secrets (passwords, API keys, tokens)
- Discuss real people, real incidents, or real units

Only use:
- Fake / sample content
- Training-only changes

If you are unsure whether something is allowed, do not add it.

---

## 🎯 Goal

You will:

- Create a small change that conflicts with someone else’s change
- See how GitHub reports a merge conflict
- Fix the conflict
- Update the Pull Request so it can be merged

---

## 🧠 What Is a Merge Conflict?

A merge conflict happens when:

- Two people change the same part of the same file
- GitHub does not know which version is correct
- A human must decide what the final version should be

Merge conflicts are normal in real projects. They are not an error — they are part of collaboration.

---

## 📁 Step 1 — Find the Shared Training File

Your instructor or the repository will provide a shared file, usually located at:

conflicts/shared-file.md

If the conflicts folder does not exist yet, your instructor will create it or tell you which file to use.

---

## 🌿 Step 2 — Create Your Branch

1. Make sure you are on:

main

2. Create a new branch named:

conflict-<your-username>

Example:

conflict-JulesVincent

---

## ✏️ Step 3 — Make Your Change

1. Open the shared file, for example:

conflicts/shared-file.md

2. Edit the same line or section that other participants are instructed to edit.

3. Make a small, safe change such as:
- Add your username to a list
- Or change a single word in a sentence

4. Commit your change with this message:

Edit shared file for merge conflict exercise

Make sure you commit to:

conflict-<your-username>

---

## 🔁 Step 4 — Open a Pull Request

1. Go back to the repository homepage.
2. Click:

Compare & pull request

3. Use this title:

Edit shared file for conflict exercise

4. In the description, write:

This is part of the merge conflict training exercise.

5. Click:

Create pull request

---

## ⚠️ Step 5 — Wait for a Conflict

As other participants submit similar changes, GitHub may show:

This branch has conflicts that must be resolved

This means your change overlaps with someone else’s change and GitHub needs you to fix it.

---

## 🛠️ Step 6 — Resolve the Conflict

When GitHub shows a conflict:

1. Open your Pull Request.
2. Click:

Resolve conflicts

3. GitHub will show both versions of the file with markers similar to:

<<<<<<<
your version
=======
their version
>>>>>>>

4. Edit the file so it contains the correct final content.
For training:
- Keep both changes if possible
- Or fix the line so it makes sense

5. Delete the conflict markers.

6. Click:

Mark as resolved

7. Click:

Commit merge

---

## 🔄 Step 7 — Finish the Pull Request

- Your Pull Request will update automatically.
- A maintainer can now review and merge it.

---

## ✅ You Are Done When

- You created a conflict branch
- You opened a Pull Request
- GitHub reported a merge conflict
- You resolved the conflict
- Your Pull Request is ready to be merged

---

## 🧠 What You Learned

- Merge conflicts are normal in team work
- Git cannot always decide what is correct — humans must
- The goal is:
  - Keep all correct changes
  - Remove only the conflict markers
- Calm, careful conflict resolution is part of professional development

---

## 🏁 Next Exercise

Proceed to:

exercises/05-clean-history.md

---

## ✅ Remember

Merge conflicts are not a failure. They are a normal part of working on a team and are solved through careful review and communication.
