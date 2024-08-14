---
title: 'My First Portfolio Post'
pubDate: 2022-08-14
description: 'This is the first post of my new Astro Portfolio.'
author: 'Fernan Gonzalez'
image:
    url: 'https://docs.astro.build/assets/rose.webp'
    alt: 'The Astro logo on a dark background with a pink glow.'
tags: ["astro", "blogging", "learning in public"]
---

# My Journey Building This Portfolio

Published on: 2022-07-01

Welcome to my _new blog_ about learning Astro! Here, I will share my learning journey as I build a new website.

## Steps.

1. **Installing Astro**: I created a new Astro project and set up my online accounts.

2. **Making Pages**: I then learned how to make pages by creating new `.astro` files.

3. **Making Blog Posts**: This is my first blog post! I now have Astro pages and Markdown posts!

#### Pre-Requisites

What I had installed previously to start the project

- **Node.js** Version < 19

- **Text Editor** Vs Code in my code

- **Terminal** in my case I also used Windows Subsystem for Linux (WSL) (Ubuntu)

#### Installing Astro

1. In the terminal run anywhere

```bash
  # create a new project with npm
  npm create astro@latest
```

2. Confirm y to install create-astro

3. When the prompt asks, “Where would you like to create your new project?” type in the name of a folder to create a new directory for your project, e.g. ./portfolio

4. You will see a short list of starter templates to choose from. Use the arrow keys (up and down) to navigate to the “Empty” template, and then press return (enter) to submit your choice.

5. When the prompt asks you if you plan on writing TypeScript, type n.

6. When the prompt asks, “Would you like to install dependencies?” type y.

7. When the prompt asks, “Would you like to initialize a new git repository?” type y.

8. Install NPM

```bash
  cd portfolio
```

**From now on I'm going to take for granted that your terminal is placed in portfolio.**

```bash
  npm install
```

9. You can now open VS Code to continue.

```bash
  code .
```

#### Installing Tailwind (Optional)

I'll install Tailwind to style my portfolio

1. ```bash
    npx astro add tailwind
  ```

when asked install dependencys type y.

when asked make changes in config file type y.

#### Making Pages

1. Run the command to start the Astro dev server

```bash
  npm run dev
```

2. In your browser. Astro uses http://localhost:4321 by default if port 4321 is available.



#### Commit your local code to GitHub (Optional)

1. You need to have an account in [GitHub](https://github.com/)

2. Go to the page where your repositories are. Look for a green button that reads new and complete the form where you are redirected

3. Once created push your local repository. Go to the terminal and execute

```bash
  git remote add origin git@github.com:{Your user name}/{Your git repository name}.git
  git branch -M main
  git push -u origin main
```

#### Deploy your code on vercel (Optional)

1. You need to have an account in [Vercel](https://vercel.com/)

2. Import your React project into Vercel.

3. Vercel will detect that you are using Astro and will enable the correct settings for your deployment.

4. Your application is deployed! (e.g. my-name-portfolio.vercel.app)

