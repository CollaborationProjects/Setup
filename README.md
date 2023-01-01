# Collaboration Repo Setup Guide

__Welcome!__ This document is a short tutorial on how to setup and start working on our collaboration project.

### Table of Contents

Click on links to jump to each section.

- [Git & GitHub](#git--github)
- [Technical Jargon](#technical-jargon)
- [Setup](#setup)
  - [Actions to be familiar with](#actions-i-would-like-you-to-be-familiar-with)
- [Test Repo (Optional)](#test-repo-optional)

---

### Git & GitHub

`Git` is a version control software that can track changes made to specified files and/or folders.

`GitHub` is a website that allows users to collaborate on projects simultaneously with git version control.

> ***I'm using these tools because it allows me to spend most of my time on the most important parts of the project while minimizing opportunities for errors to arise.***

See the technical jargon section below for definitions on the terms I mention in this document.

---

### Technical Jargon

- __repo__: shorthand for repository, a "drive" where mostly everything related to the project is stored

- __GitHub Desktop__: a desktop application that simplifies typing commands into a point-and-click process

- __commit__: saves a "snapshot" of your changes, default is all changes any file in your repo

- __fetch__: download changes made by members of your team

- __push__: take changes you made and upload to GitHub so members of your team can download

- __`.gitignore`__: file telling git which files should not be tracked

---

### Setup

#### 1. Installation

1. create a __GitHub__ account [here](https://github.com/) → `Sign Up`

1. download __GitHub Desktop__ [here](https://desktop.github.com/)

1. install __GitHub Desktop__ to your computer

1. sign in to __GitHub Desktop__ using account you created in Step 1

> ***Note:***
> - don't worry too much about choosing the ***best*** username because you can change your that later
> - make sure to download the appropriate version of GitHub Desktop for your computer's operating system

#### 2. Create separate data folder

To avoid accidental uploads of potentially sensitive data, I recommend storing any raw data files (`.csv`,`.xlsx`...) in a separate but easily accessible folder on your computer.

#### 3. Join Repo

After installing and connecting your GitHub account to GitHub Desktop, you will need to be added to the organization/repo.

>_Send me your GitHub username and I will take care of this step._

#### 4. Know how to interact with GitHub & GitHub Desktop

Unless you want to become a master, knowing the basics is enough to get started.

##### Actions I would like you to be familiar with:

- ***view files***: Go to the repo on GitHub website, click `Code`, click on file you would like to view
  
  - In most cases, the only files you will need to take a look at are: 
    - `.ipynb`
    - `.md`
    - `.html`

  >The only way to view `.html` files (from private repo) is to download and open with browser.

- ***fetch***: This process should be done automatically by GitHub Desktop. If not, you can click `Fetch Origin` and wait for the logo to stop spinning.

  >

- ***commit & push***: Changes since last commit will auto-populate.
  1. Choose ___ branch
  2. Confirm all changes are correct
  3. Add a summary
  4. Add a description (optional)
  5. Click commit to ___ branch
  6. `Fetch Origin` button should change to `Push Origin`
  7. Click `Push Origin`
  8. Wait for logo to stop spinning

  >Official documentation: [Committing & reviewing changes](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/committing-and-reviewing-changes-to-your-project)

- ***tracking tasks***: Done entirely on GitHub website.
  1. Click `Issues` tab inside the repo
  1. `New Issue`
  1. add `Title`, `Comment` & `Label`
  1. `Submit new issue`

  >Official documentation: [Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/quickstart)

#### 5. Install & setup other tools

Depending on the project, there might be need for other tools. 

The table below lists some of the formats where an alternative should be used.

|Format|Reason|Alternative|
|---|---|---|
|raw data/files|potentially sensitive information|encrypted email/storage|
|Word (.doc/.docx)|formatting issues|Google Docs|
|files > 100 MB|GitHub storage restriction|dedicated cloud drive|

#### 6. Ready to begin

Everything is set up and you are now ready to begin!

<h4 align="center"> 
    Feel free to ask me if you need help or are unsure about things.
<h4>

---

#### Test Repo (Optional) 

I have a [test repo](https://github.com/Proj-Collab/Sandbox) set up if you would like to practice and/or confirm everything works as intended.
