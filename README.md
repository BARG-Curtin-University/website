
# Contributing a Blog Post to the BARG Website

Contributing a blog post to the BARG website is a great way to share your research, insights, or experiences with our community. This guide will walk you through the process of cloning our website, adding a post, and pushing it back to the repository.

## Prerequisites

You will need to have Git and Hugo installed on your computer. If you do not have them installed, you can download them from the following links:

- [Git](https://git-scm.com/downloads)
- [Hugo](https://gohugo.io/getting-started/installing)

## Step 1: Clone the Website Repository

Open a terminal and navigate to the directory where you want to clone the website repository. Use the `git clone` command to clone the repository:

```bash
git clone https://github.com/BARG/website.git
```

After running this command, a copy of the website repository will be downloaded to your local machine.

## Step 2: Create a New Post

First, navigate to the posts directory within the website project:

```bash
cd website/content/posts/
```

Now create a new directory with the date and title of your post:

```bash
mkdir yyyy-mm-dd-your-post-title
```

Then navigate into the directory you just created:

```bash
cd yyyy-mm-dd-your-post-title
```

Next, create a new markdown file for your post:

```bash
touch index.md
```

Also, if you have a featured image, place it in the same directory and name it `featured.jpg`.

## Step 3: Write Your Post

Open the `index.md` file in a text editor and start writing your post. Here's a basic template you can use:

```markdown
---
title: "Your Post Title"
date: YYYY-MM-DD
---

Your post content goes here...
```

Once you're done writing, save and close the file.

## Step 4: Push Your Changes

First, navigate back to the root directory of the project:

```bash
cd ../../..
```

Next, stage your changes with the `git add` command:

```bash
git add content/posts/yyyy-mm-dd-your-post-title
```

Then, commit your changes with the `git commit` command:

```bash
git commit -m "Added new post: Your Post Title"
```

Finally, push your changes to the repository with the `git push` command:

```bash
git push origin main
```

## Step 5: Submit a Pull Request

Once you've pushed your changes, go to the [BARG website repository](https://github.com/BARG/website) on GitHub. Click on the "New pull request" button, then select your branch and submit your pull request. Provide a clear description of your changes.

One of our team members will review your post and may provide feedback or request changes. Once your post has been approved, it will be merged into the main branch and will be visible on the BARG website.

Thank you for considering contributing to the BARG website! Your insights will be greatly appreciated by our community.
