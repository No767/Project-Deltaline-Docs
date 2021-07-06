# Contributing to Deltaline 
Deltaline is completely open source, licensed under the GPL-3.0 License. Currently, it's written in HTML, but I plan to rewrite it in Vue.js later on. The Logo is licensed under the CC-BY-ND-NC 4.0 License, and can be found [here](https://github.com/No767/Logo-Favicon). All other works within Deltaline are all rights reserved. 

**So, how do you contribute?**
Well it's already listed in the repo, but here's the [contributing](https://github.com/No767/Deltaline/blob/master/contributing.md) guidelines

## Styleguides

### Git Commit Messages

- Describe what is the change (branch change, clean up code, etc)
- If it's updating the other files (that dont have to go through the CI), add a [ci skip] label in the front of the commit message or use [skip ci] or [skip netlify] so netlify won't try and build and deploy it and give the "failed" rating on the badge

### Issues

- Add a label
- Use one of the templates that is available

### Pull Requests

- Describe the change (issue fix, clean up code, etc)
- When doing a pull request, make sure the pull request goes into the dev branch
- And dont delete the dev branch
- List the branch, and the commit number starting from the most recent commit

## Code Styleguides
Please make sure that the code is readable and clean. for example, 

```

  <head><meta name="viewport" content ="width=device-width, initial-scale=1, user-scalable=yes" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
<link rel="shortcut icon" type="image/jpg" href="Dcey SMP Logo V4 Release.webp"/>
<title>Deltaline</title>
</head>

``` 

(proper example) This is a proper way to do it. But for example, 

```

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" type="image/jpg" href="Dcey SMP Logo V4 Release.webp"/>
    <title>Deltaline</title>

```
this one is too messy and it's kinda hard to read

**Long story short**: Just make it easy to read