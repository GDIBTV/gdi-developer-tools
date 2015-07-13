# Better Web Debugging: A Developer Tools Workshop

Slides and course materials for GDI Burlington’s Developer Tools workshop. Developed by Rachael Arnold.

This course is meant to be taught as a one-night, 2.5 hour session. It is highly recommended that students have prior knowledge of HTML, CSS, and Javascript, as knowldege of them are assumed.

## Content

This workshop covers:

- Inspecting and manipulating the DOM
- Emulating devices
- Using the console as a REPL
- Javascript debugging overview
- Network profiling

If time permits, instructors may include saving local source files and other advanced topics.

## Cloning Reveal submodule 

Reveal is a submodule. To clone it correctly or learn more, see [these instructions](http://git-scm.com/book/en/Git-Tools-Submodules#Cloning-a-Project-with-Submodules). 

## Theme customization in Reveal 

You can change theme colors by changing the theme css to any of the following options:
```html
  <link rel="stylesheet" href="css/theme/gdidefault.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdilight.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdisunny.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdicool.css" id="theme">
```
You can change the text editor theme by changing the highlight.js css to the following options:
```html
  <link rel="stylesheet" href="lib/css/dark.css">
  <link rel="stylesheet" href="lib/css/light.css">
```
You can change transition by changing the reveal transition property in Reveal.initialize
```javascript
  Reveal.initialize({
  				transition:  'default', // default/cube/page/concave/zoom/linear/none
  			});
```
