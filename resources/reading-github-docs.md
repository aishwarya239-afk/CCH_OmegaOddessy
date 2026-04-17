# 📖 How to Read GitHub Documentation — Your Complete Reference Guide

> **This file is your user manual for the user manual.**
> Bookmark it. Come back to it anytime you feel stuck or confused.
> Every developer — beginner or expert — uses these same docs daily. You are not behind. You are exactly where you need to be.

---

## 🗺️ Your 5-Step Learning Path Through GitHub Docs

Follow these steps in order. Each one builds on the last.
You do not need to do them all in one sitting. One step at a time is perfect.

| Step | What You'll Do | Time Needed | Link |
|------|---------------|-------------|------|
| 1 | Understand what GitHub is | 5 mins | [About GitHub and Git](https://docs.github.com/en/get-started/start-your-journey/about-github-and-git) |
| 2 | Create your account and profile | 10 mins | [Create an account](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github) · [Set up profile](https://docs.github.com/en/get-started/start-your-journey/setting-up-your-profile) |
| 3 | Create your first project | 15 mins | [Hello World tutorial](https://docs.github.com/en/get-started/start-your-journey/hello-world) |
| 4 | Learn to navigate the docs | 10 mins | [GitHub Docs home](https://docs.github.com/en) · [GitHub Glossary](https://docs.github.com/en/get-started/learning-about-github/github-glossary) |
| 5 | Explore your career track | Your pace | [Finding inspiration](https://docs.github.com/en/get-started/start-your-journey/finding-inspiration-on-github) · [GitHub Skills](https://skills.github.com) |

---

## 🏠 The Most Important Page to Bookmark

**https://docs.github.com**

This is GitHub's official documentation — their complete user manual. It is:
- Free, always
- Written in plain English
- Kept up to date by GitHub themselves
- Searchable (use the search bar at the top)

> 💡 **Rule 1 of reading docs:** You don't need to read everything. Just search for what you need *right now*. Treat it like a dictionary — you don't read a dictionary cover to cover, you look up the word you need.

---

## 📚 Step 1 — Understand What GitHub Is

**Open this doc:** https://docs.github.com/en/get-started/start-your-journey/about-github-and-git

### The Big Picture (Before You Open Anything)

Before reading a single doc, it helps to have the right mental picture.

**Git** and **GitHub** are two different things that work together.

| | What it is | Real-life analogy |
|--|-----------|-------------------|
| **Git** | A system that tracks every change you make to your files | Like "Track Changes" in Microsoft Word — but for any file, forever |
| **GitHub** | A website where you store your Git projects online | Like Google Drive — but with version history, collaboration tools, and a public profile |

> 🌸 **For non-coders:** You do not need to use Git's command-line tools to benefit from GitHub. Everything in this guide can be done entirely in your web browser at github.com. No installation required.

---

## 👤 Step 2 — Create Your Account and Profile

**Open these docs:**
- Create an account: https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github
- Set up your profile: https://docs.github.com/en/get-started/start-your-journey/setting-up-your-profile

### How to Read a "How To" Doc on GitHub

When you open any GitHub doc that walks you through steps, you will see a structure like this:

```
Prerequisites
  (things you need before you start)

Step 1: [Action]
Step 2: [Action]
Step 3: [Action]

Next steps
  (what to explore after this)
```

**Your job is simple:** Read one step. Do that step. Move to the next.

> 💡 **Rule 2 of reading docs:** If you see a word you don't understand, look it up in the GitHub Glossary (https://docs.github.com/en/get-started/learning-about-github/github-glossary). Every GitHub term is defined there in plain English.

### Important Terms You Will See in Your Account Setup

**Username**
Your unique identity on GitHub. Appears in all your links.
- Example: if your username is `priya-comeback`, your profile is at `github.com/priya-comeback`
- Choose something professional — employers will see this
- Use your name or a variation: `sarah-jones`, `meera-pm`, `divya-finance`

**Profile README**
A special file you can create that shows on your GitHub homepage — like a mini "About Me" page.
- Example: Divya, a project manager, writes: *"PM professional with 8 years in logistics. Currently learning GitHub and Python. Open to opportunities in operations and tech."*
- This is entirely optional, but very powerful for career comeback

**Public vs Private repository**
- **Public:** Anyone on the internet can see it. Good for portfolios and sharing.
- **Private:** Only you (and people you invite) can see it. Good for personal work.

---

## 📁 Step 3 — Create Your First Project (Repository)

**Open this doc:** https://docs.github.com/en/get-started/start-your-journey/hello-world

This is GitHub's own official beginner tutorial. It takes about 15 minutes and you do everything in your browser.

### What Is a Repository?

A **repository** (often shortened to **repo**) is your project folder on GitHub.

Think of it like this:

```
Your Computer                    GitHub
─────────────────                ──────────────────────────────────────
📁 My Documents                  Your GitHub Profile
  📁 Work Projects         →       📁 career-comeback-resources  (repo)
    📄 budget-2024.xlsx              📄 README.md
    📄 notes.docx                    📄 finance-resources.md
    📄 plan.pdf                      📁 resources/
```

The difference is that your GitHub repo:
- Is backed up online automatically
- Remembers **every version** of every file, forever
- Can be shared with a link
- Shows the world your work and skills

### Key Terms You Will See in the Hello World Tutorial

---

**README**

The `README.md` file is the front page of your repository. When someone visits your project, the README is the first thing they see — displayed automatically below your files.

- The `.md` stands for **Markdown** (a simple way to format text — more on this in Step 5)
- Think of it as the cover page and introduction of your project

*Example README for a teaching resources repo:*
```
# Mrs Sharma's Year 6 Science Resources
A collection of lesson plans, worksheets, and revision materials.

## What's in here
- Lesson plans organised by topic
- Assessment templates
- Student-friendly revision guides

Created by Anita Sharma | Last updated: April 2025
```

---

**Commit**

A **commit** is the act of saving your work to GitHub, with a short note explaining what you changed.

Every commit creates a permanent snapshot of your files at that moment in time.

*Real-life analogy:* Imagine every time you saved a Word document, you also had to write a sticky note saying what you changed. A year later, you could look back through all the sticky notes and see the entire history of your document.

*Example commit messages:*
- `"Add lesson plan for photosynthesis unit"`
- `"Update budget template with Q3 figures"`
- `"Fix typo in sales playbook introduction"`
- `"Add new supplier checklist to logistics folder"`

> 💡 **Good commit messages are short and specific.** Bad: *"changes"*. Good: *"Add contact details to team README"*.

---

**Branch**

A **branch** is a separate, safe copy of your project where you can make changes without affecting your main work.

*Real-life analogy:* Imagine you have a printed report. You want to try rewriting one section, but you're not sure if the new version will be better. You photocopy the relevant pages, experiment on the copies, and if you like the result — you replace the original pages. If you don't like it — you throw the copies away and your original is safe.

In GitHub:
- The **main branch** = your official, final version
- A **new branch** = your experimental copy

*Example:*
> Priya is updating her project management templates repo. She wants to try a new layout for her status report template, but isn't sure it will work. She creates a branch called `new-status-report-layout`, makes her changes there, and when she's happy, she merges it back into main. If she didn't like it, she simply deletes the branch — the main version was never touched.

---

**Merge**

**Merging** is the act of bringing the changes from a branch back into your main project.

*Following the example above:* After Priya is happy with her new template layout on her test branch, she merges it into main. Now the official version of her project has the new layout.

---

**Pull Request (PR)**

A **pull request** is a formal way of asking for your changes to be reviewed and merged.

You will not need this for solo projects — but it is worth knowing the term. When working in a team, instead of merging directly, you open a pull request so a teammate can review your changes first.

*Example:* Think of it like sending a document to a manager saying: *"I've made these changes — can you review and approve before we update the official version?"*

---

**Fork**

A **fork** is a copy of someone else's repository that lives in your GitHub account.

This lets you take any public project on GitHub, copy it to your own account, and experiment with it freely — without affecting the original.

*Example:* You find a beautiful CV template repository. You fork it to your account, then customise it with your own information and style. The original template is unchanged. Your version is yours to do whatever you like with.

---

**Clone**

To **clone** a repository means to download a copy of it to your own computer so you can work on it locally.

> 🌸 **For beginners:** You don't need to clone anything yet. Everything in this guide can be done entirely in the browser. Cloning is something to explore later.

---

**Issues**

**Issues** are GitHub's built-in task list and discussion tool. You can use them to:
- Track things you want to add or fix in your project
- Write notes to yourself about future ideas
- Collaborate with others on tasks

*Example for a project manager:*
> Maya uses her GitHub repository like a simple project tracker. She creates issues such as:
> - `"Add risk register template"`
> - `"Update stakeholder communication guide"`
> - `"Find and add example RACI matrix"`
> She assigns them to herself, marks them done when complete. It's a lightweight to-do list for her repo.

---

## 🗺️ Step 4 — How to Navigate GitHub Docs Like a Pro

**Bookmark:** https://docs.github.com/en
**Glossary:** https://docs.github.com/en/get-started/learning-about-github/github-glossary

### The Structure of GitHub Documentation

When you open GitHub Docs, you'll see the content is organised into sections in the left sidebar. The main ones relevant to beginners are:

```
GitHub Docs
├── Get started           ← Start here. Everything for new users.
│   ├── Start your journey
│   ├── Using GitHub
│   └── Writing on GitHub
├── Repositories          ← All about creating and managing projects
├── Pull requests         ← For collaborating and reviewing
├── Issues                ← For tracking tasks and discussions
└── GitHub Pages          ← For building free websites from your repo
```

### The 3 Rules of Reading Technical Documentation

**Rule 1: Search first, browse second**
Use the search bar at the top of any doc page. Type what you're trying to do in plain English.
- Try: *"how to create a repository"*
- Try: *"how to add a file"*
- Try: *"what is a branch"*

**Rule 2: Look for "Quickstart" pages**
Almost every GitHub feature has a Quickstart guide — a short, step-by-step version of the full documentation. Always look for the Quickstart first.
- Example: Instead of reading the full 10-page repository guide, find and open *"Quickstart for repositories"*

**Rule 3: The glossary is your best friend**
Whenever you see a word you don't recognise, open the GitHub Glossary in a new tab and search for it. The glossary defines every GitHub term in one or two sentences.

### Common Documentation Phrases Explained

When reading GitHub docs, you'll often see these phrases:

| Phrase you see | What it means |
|----------------|---------------|
| *"Navigate to your repository"* | Go to your project page on GitHub |
| *"In the upper-right corner"* | Look for a button at the top right of the page |
| *"Click the pencil icon"* | Click the edit button (looks like a pencil ✏️) |
| *"Commit your changes"* | Save your work with a short message |
| *"Create a new branch"* | Make a safe copy to work on |
| *"Open a pull request"* | Ask for your changes to be reviewed |
| *"Merge the pull request"* | Approve and add the changes to the main version |
| *"Clone the repository"* | Download a copy to your computer |
| *"Fork the repository"* | Copy someone else's project to your account |

---

## ✍️ Step 5 — Writing on GitHub (Markdown Basics)

**Open this doc:** https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

### What Is Markdown?

**Markdown** is a simple system for formatting text. Instead of clicking buttons like in Word, you type short symbols to create headings, bold text, lists, and links.

GitHub automatically converts Markdown into beautifully formatted text when you view a file.

Every `.md` file on GitHub (including this one!) is written in Markdown.

### The Only Markdown You Actually Need to Know

**Headings** — use `#` symbols

```
# Big heading (like a title)
## Medium heading (like a section)
### Small heading (like a sub-section)
```

**Bold and italic**

```
**This text will be bold**
*This text will be italic*
```

**A bullet list**

```
- First item
- Second item
- Third item
```

**A numbered list**

```
1. First step
2. Second step
3. Third step
```

**A link**

```
[Text the reader sees](https://the-actual-url.com)

Example:
[GitHub Docs](https://docs.github.com)
```

**A line across the page (divider)**

```
---
```

> 💡 That's genuinely all you need for a great README. You don't need to learn anything more complex than this to have a professional, well-formatted GitHub profile.

### Seeing Markdown in Action

When you are editing a file on GitHub, you'll see two tabs at the top:
- **Edit** — where you type your Markdown
- **Preview** — where you see it formatted

Always click Preview before saving, so you can see exactly how it will look.

---

## 🌟 Putting It All Together — Example Walkthrough

Here is a complete example of how someone new to GitHub would use the documentation to complete a real task.

---

**Scenario:** Fatima works in logistics. She wants to create a GitHub repository to store her process templates and SOPs (Standard Operating Procedures). She has never used GitHub before.

**Step 1:** Fatima opens GitHub Docs and searches *"create repository"*

**Step 2:** She finds and opens the *"Hello World"* tutorial

**Step 3:** She follows the steps — creating a repo called `logistics-process-templates`

**Step 4:** She edits the README file. She types this Markdown:

```markdown
# Logistics Process Templates

A collection of SOPs, checklists, and process guides I've developed.

## What's Inside
- Warehouse intake checklists
- Supplier onboarding process
- Daily dispatch SOP
- KPI tracking templates

## About
Created by Fatima | Operations & Logistics Professional
```

**Step 5:** She commits (saves) her README with the message: `"Add introduction README"`

**Step 6:** She previews her repository. It looks professional. She copies the link and shares it with our group: `github.com/fatima-logistics/logistics-process-templates`

**Total time:** About 20 minutes.
**Prior experience needed:** None.
**Things she installed:** Nothing.

---

## 🔖 Quick Reference — All Links in One Place

### Official GitHub Documentation

| Resource | Link | What it's for |
|----------|------|---------------|
| GitHub Docs (home) | https://docs.github.com | The complete user manual |
| GitHub Glossary | https://docs.github.com/en/get-started/learning-about-github/github-glossary | Definitions for every GitHub term |
| About GitHub and Git | https://docs.github.com/en/get-started/start-your-journey/about-github-and-git | Start here — what everything is |
| Create an account | https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github | Sign-up walkthrough |
| Set up your profile | https://docs.github.com/en/get-started/start-your-journey/setting-up-your-profile | Profile photo, bio, location |
| Hello World tutorial | https://docs.github.com/en/get-started/start-your-journey/hello-world | Create your first repo in the browser |
| Upload a project | https://docs.github.com/en/get-started/start-your-journey/uploading-a-project-to-github | Add existing files to GitHub |
| Finding inspiration | https://docs.github.com/en/get-started/start-your-journey/finding-inspiration-on-github | Discover projects in your field |
| Learning resources | https://docs.github.com/en/get-started/start-your-journey/git-and-github-learning-resources | GitHub's own recommended next steps |
| Markdown basics | https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax | How to format your README |

### Free Interactive Learning

| Resource | Link | What it's for |
|----------|------|---------------|
| GitHub Skills | https://skills.github.com | Free courses, you learn inside GitHub itself |
| GitHub Pages guide | https://docs.github.com/en/pages | Build a free website from your repo |

---

## 💬 A Note Before You Go

When you feel confused by a new technology, that feeling is completely normal — it does not mean you are not capable. It means you are learning.

Every person who is confident with GitHub today was once looking at the same screen you're looking at now, reading the same documentation, feeling the same uncertainty.

The difference between them and where they started is simply this: they opened a doc, followed one step, and kept going.

You have the same manual they had. You have the same GitHub. You have the same ability to learn.

The only step that matters right now is the next one. 🌸

---

*Career Comeback Hub | Created with ❤️ | [Back to main resources](../README.md)*
