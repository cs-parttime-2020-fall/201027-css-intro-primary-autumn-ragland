# 20-10-27 CSS Intro Primary

### Assignment
Create a CSS file and style the provided HTML file to look like wireframe image provided using only the tags/class/ids already available in the provided HTML file. You will need to link the newly created CSS file to the HTMl file provided.

### Set Up
1. copy the assignment git url in github after accepting the assignment
1. clone the assignment in the `html-css-basics` directory using `git clone COPIED URL`
1. open the assignment in VSCode
1. open the provided HTML file using `ctrl o` in the browser

### Linking files
1. create a new css file called `style.css`
2. link the css file to the html file using the `link` tag in the `head` - set the `rel` attribute to `stylesheet` and the `href` attribute to the css file path
```html
 <link rel="stylesheet" href="style.css">
```
3. check that the files are linked by setting the `background-color` property of the body to any color other than white/gray and refreshing the page

### Push File Changes in the Terminal
1. `git status` : check if file changes have been made
1. `git add -A` : stage changes for commit
1. `git commit -m "meaningful message"` : commit changes with appropriate message
1. `git push` : reflect local changes remotely 

### Resources
[Concept Documentation Info on HTML + CSS](https://github.com/cs-parttime-2020-fall/part-time-program-syllabus/blob/master/htmlCSS.md)
