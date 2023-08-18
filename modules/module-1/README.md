# 📝 Module 1 Study Guide

## Table of Contents

1. [Command-Line](#command-line)

2. [Git and Github](#git)

3. [HTML](#html)

4. [CSS](#css)

5. [Other resources](#resources)

6. [Activity tracker](#tracker)
 
## ⌨️ Command-Line <a name="command-line"></a>

### Links

[Basic commands](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools/Command_line#basic_built-in_terminal_commands)

### Notes

- `cd <folder-name>` will enter the directory specified

- `cd ..` will go back one directory

- `mkdir <dir-name>` will make a directory in the current directory you are in

- `touch <filename>` will create a file in the current directory

## 😸 Git and Github <a name="git"></a>

### Links

[Github](https://docs.github.com/en/get-started/quickstart/hello-world)

[Git basics](https://www.atlassian.com/git)

### Notes

- Use `git pull origin main` to sync your local repo with the one on GitHub

- `git status` will inform you of any changes made in local repo

- `git add` will stage files for commit. Use `git add -A` to stage all files or use `git add <filename>` to stage a single file

- `git commit -m "your message"` will commit your changes after you have used `git add`. Make sure to write a descriptive message for your commits.

- `git push` will push your commits to your GitHub repo.

## 🏗️ HTML <a name="html"></a>

### Links

[Hypertext markup language](https://developer.mozilla.org/en-US/docs/Web/HTML)

[Attributes](https://developer.mozilla.org/en-US/docs/Glossary/Attribute)

[HTML cheatsheet](https://coding-boot-camp.github.io/full-stack/html/html-cheatsheet)


### Notes

- Use `<!--Your comment-->` to place comments in your html code.

- Use "#" in the href of an `<a>` tag as a placeholder. Example `<a href="#"></a>`

- Use classes `class="your-class-here"` for styling multiple elements with css

- Use id's `id="your-id-here"` to style unique elements with CSS

- Use `<link rel="stylesheet" type="text/css" href="<path-to-css">` in the head of your html file to link a css stylesheet

### Examples

Boilerplate html

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>HTML 5 Boilerplate</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
	<script src="index.js"></script>
  </body>
</html>
```

## 🎨 CSS <a name="css"></a>

### Links

[Color](https://developer.mozilla.org/en-US/docs/Web/CSS/color)

[Font](https://developer.mozilla.org/en-US/docs/Web/CSS/font)

[CSS selector](https://developer.mozilla.org/en-US/docs/Glossary/CSS_Selector)

[Display](https://developer.mozilla.org/en-US/docs/Web/CSS/display)

[The box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

[Position](https://developer.mozilla.org/en-US/docs/Web/CSS/position)

### Notes

- You can style by html elements.

- Use `.your-class` to style a class in yuor html

- Use `#your-id` to style an id in your html

- Use `*` to target everything on the page. 

- Use lists for navbars

### Examples

Styling with elements, classes, and id's

```
<!--style by element-->
h1 {
    font-size: 24px;
}

<!--style by class-->
.your-class {
    color: red;
}

<!--style by id-->
#your-id {
    color: blue;
}

<!--style everything-->
* {
    color: blue;
}
```

## 📓 Other Resources <a name="resources"></a>

### Links

[Markdown cheatsheet](https://www.markdownguide.org/cheat-sheet/)

[Professional README guide](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide)


### Notes

## ✔️ Activity tracker <a name="tracker"></a>
- [x] 02-Stu_Command-Line

- [x] 04-Stu_Git

- [x] 06-Stu_HTML

- [x] 08_Stu_Attributes

- [x] 10-Stu_CSS-color

- [x] 12-Stu_CSS-units-fonts

- [x] 14-Stu_CSS-selectors

- [x] 16-Stu_HTML-display

- [x] 18-Stu_CSS-box-model

- [x] 20-Stu_CSS-positioning

- [ ] 22-Stu_Mini-Project
