---
layout: post
title:  "Make a Blog using Github.io and jekyll"
date: 2019-01-06 16:16::28 +0900
categories: study
---

# Create a repository on github

![Screenshot 2019-01-06 at 3.31.30 PM](/assets/githubscreenshot.png)

##### Head over to GitHub and create a new repository named username.github.io, where username is your username (or organization name) on GitHub.

If the first part of the repository doesn’t exactly match your username, it won’t work, so make sure to get it right.

# Clone the repository

Go to the folder where you want to store your project, and clone the new repository:

```
$ git clone https://github.com/username/username.github.io
```

# Hello World

Enter the project folder and add an index.html file:

```
$ cd username.github.io
$ echo "Hello World" > index.html
```

# Push It

Add, commit, and push your changes:

```
$ git add --all
$ git commit -m "Initial commit"
$ git push -u origin master
```

…and you're done!
Fire up a browser and go to https://username.github.io.

---
# Jekyll Quickstart on MacOS

Jekyll is a simple, extendable, static site generator. You give it text written in your favorite markup language and it churns through layouts to create a static website. Throughout that process you can tweak how you want the site URLs to look, what data gets displayed in the layout, and more.

### Install

```
$ sudo gem install jekyll bundler
```

### Create a new Jekyll site

```
$ jekyll new username.github.io --force
```

### Change Directory
```
$ cd username.github.io
```

### Delete index.html
```
$ rm index.html
```

### Build the site and make it available on a local server
```
$ jekyll serve
```

Now browse to http://localhost:4000

---

# Push to Github

```
$ git init
$ git remote add origin https://github.com/username/username.github.io.git
$ git add all
$ git commit - m "first jekyll commit"
$ git push
```

__We're done__
check it out on https://username.github.io.

---

# References
_**Github Page** https://pages.github.com/_
_**Jekyll** https://jekyllrb.com/docs/_