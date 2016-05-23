---
title:
length:
tags:
---

### NOTES
 - Specificity refers to the set of rules that govern behavior of styling on an html page.
 - Talk about definition of CSS - Cascading Style Sheet

### Goals

By the end of this lesson, you will:

* Understand the relationship between HTML and CSS elements
* Be able to define what CSS stands for and how a CSS file is structured
* Understand the weight of each css element and how they differ
* Be able to define specificity in the context of styling html elements

### Structure

* Part 1: Quick review of basic HTML and CSS structure
* Dig into CSS specificity and how to control what your stylesheet is doing

### Repository

* [CSS Specificity Repo](https://github.com/martensonbj/css-specificity)

### Lets Get Into It

Let's start by creating an html and css file.

`touch index.html main.css`

Then set up the HTML file with a basic skeleton.

```
// index.html //
<!DOCTYPE html>
<html>
<head>
  <title>CSS & Specificity & Basketball</title>
</head>

<body>
  <h1> CSS & Specificity </h1>
</body>

</html>
```

Now we need to tell our HTML file where to find the stylesheet:
```
// index.html //
<head>
  <title>CSS & Specificity & Basketball</title>
  <link rel="stylesheet" type="text/css" href="main.css" />
</head>
```

Add an unordered list that keeps track of your favorite NBA players and a second one that lists favorite teams.

```
<body>
  <h5>Favorite Players</h5>
  <ul>
    <li>DeAndre Jordan</li>
    <li>Blake Griffin</li>
    <li>Kevin Love</li>
  </ul>

  <h5>Favorite Teams</h5>
  <ul>
    <li>LA Clippers</li>
    <li>MN Timberwolves</li>
    <li>Boston Celtics</li>
  </ul>
</body>
```

At some point we will want to change some things about how our text looks. Right now it is in default Times New Roman which is uninteresting. Lets shake things up and add some more exciting from our friends at fonts. 

### Resources

* [Link to first outside resource]()
