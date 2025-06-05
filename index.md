---
title: "NRG Research Page"
permalink: /
layout: default
---


# Our Group

The [Nuclear & Applied Robotics Group](https://robotics.me.utexas.edu) is an interdisciplinary research group whose goal is to develop and deploy remote systems in hazardous/challenging environments to minimize the risks undertaken by human personnel. 'Interdisciplinary' refers not just to the many facets of modern robotics (mechanical, electrical, controls, etc.) but developers also gather the necessary knowledge of the domains where they will be deployed (nuclear, energy, military, etc.).

# Our Mission

We want to reduce the exposure of human operators to hazards while minimizing the overall costs (training, execution, time, and money) associated with the use of remote systems, and do so in a way that increases the number of engineering scientists in the world who can develop these systems at UT and beyond.


If you're new to Markdown, take a look at
[GitHub's Markdown Guide](https://guides.github.com/features/mastering-markdown/).

## Step 1. Edit your Markdown file

Put all of your Markdown in a file with a simple name such as `index.md` or
`home.md`.

Add the following lines to the very top of the Markdown file, replacing
`Make a Website with Only Markdown` with the title you want to use for
your website:

``` ruby
---
title: "Make a Website with Only Markdown"
permalink: /
layout: default
---
```

These special lines are known as
[Front Matter](https://jekyllrb.com/docs/front-matter/) and they tell GitHub
the title and location of the page on your website.

Make sure to save your changes. 😉

## Step 2. Create a GitHub repository

If you don't already have one, create a free GitHub account at
[github.com](https://github.com).

Once you're signed in, click the `➕` icon in the top navigation bar to
create a new repository.

Name your repository and select `Public` access so your website will be
viewable by anyone.

Press the `Create Repository` button.

## Step 3. Upload your Markdown file

Click the `Uploading an existing file` link in the _Quick setup_ section of
your new repository.

Drag your Markdown file onto the new page or click the `Choose your files`
link to select the file from your file system.

Press the `Commit changes` button.

## Step 4. Turn on GitHub Pages

Navigate to the `Settings` tab of your repository on GitHub, then scroll
down to the `GitHub Pages` section of the page.

Select `master branch` as the `Source` option. Then click the `Choose a theme`
button in the section.

Use the carousel to choose and preview a theme for your website, then click the
`Select theme` button to apply that theme to your repository.

## Step 5. Behold your website!

If all went well, your website should be live!

To view it, click the link to your website in the `GitHub Pages` section on
the `Settings` tab of your repository on GitHub.

The URL is also structured in a specific way:

```
https://<user>.github.io/<repository>/
```

If you replace `<user>` and `<repository>` with your GitHub login and
repository name, you can also type the address directly into your
browser's address bar.

## Step 6. Use your own domain name

If you have your own domain name, you can also tell GitHub to host your
Markdown website at that domain.

### On GitHub

Go to the `GitHub Pages` section on the `Settings` tab of your repository on
GitHub, type your domain name (e.g. `www.markdownwebsite.com`) in the
`Custom domain` text box, then click `Save`.

### On your domain registrar

Login to your domain registrar's website and configure your domain name
settings (DNS).

Create a `CNAME` record that points your domain name (the exact same text
typed in GitHub's `Custom domain` field) to `<user>.github.io`
(replace `<user>` with your GitHub login).

Save your DNS settings.

After the DNS change propagates (this can take seconds, minutes, or hours),
you'll be able to visit your domain and see your beautifully-rendered
Markdown website! 😎

## Where to learn more

This feature of GitHub is known as GitHub Pages and there's much more to it
than demonstrated here.

If you want to take a deeper dive into GitHub Pages, visit
[pages.github.com](https://pages.github.com).

For more information about Jekyll, the underlying technology that GitHub pages
uses, visit [jekyllrb.com](https://jekyllrb.com/).
