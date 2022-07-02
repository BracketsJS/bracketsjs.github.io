![BracketsJS Icon](https://github.com/dinonull/bracketsjs.github.io/raw/main/favicon.png)
# BracketsJS Docs
## Why
[@JaydenDev](https://github.com/JaydenDev) developed BracketsJS using some new ideas, some code from their previous projects and ended up spending more time naming it than actually coding it. It has a few features already that'll suffice for a release and will make some things easier like dark mode for example.

## Goal
The goal of this project is to make a javascript library that makes creating web apps easier to create.

## Contributing
Contributing is easy, fork the [Github repository](https://github.com/BracketsJS/BracketsJS), make the some changes that you think will benifit BracketsJS and make a pull request. It is recommended that you prefix the name of your commits and pull requests with "feat: " if it adds a new feature or "fix: " if it fixes any bugs.

## Forking
You are completely free to fork this project and make your own version that follows the MIT License. It is recommended that you give credit to our group and keep it open source as well.

## Installing
Installing BracketsJS is as easy as linking the script in the HEAD of your HTML document:
```html
<!DOCTYPE html>
<html>
  <head>
    <script src="https://cdn.jsdelivr.com/gh/BracketsJS/BracketsJS/dist/bundle.js"></script>
    ...
  </head>
  <body>
    ...
  </body>
</html>
```
## Methods
### createElem
Creates an element with the given parameters.
```javascript
brackets.createElement(element[, parentId, id, className, innerHTML, href]);
```
| Parameter     | Description                      | Optional |
|:-------------:|:--------------------------------:|:--------:|
| `element`     | The tag name of the new element. | No       |
| `parentId`      | The `id` of the parent of the new element.  | Yes      |
| `id`      | The `id` of the new element.  | Yes      |
| `className`      | The class name of the new element.  | Yes      |
| `innerHTML`      | The class name of the new element.  | Yes      |
| `href`      | If the new element is a link this is the `href` atrribute of it.  | Yes      |
### removeElem
Removes a element.
```javascript
brackets.removeElem(id);
```
| Parameter     | Description                      | Optional |
|:-------------:|:--------------------------------:|:--------:|
| `id`     | The id of the element to remove | No       |
### removeLinks
Removes all link elements.
```javascript
brackets.removeLinks();
```
| Parameter     | Description                      | Optional |
|:-------------:|:--------------------------------:|:--------:|
### swapStyles
Swaps stylesheet with the stylesheet provided.
```javascript
brackets.swapStyles(stylesheet);
```
| Parameter     | Description                      | Optional |
|:-------------:|:--------------------------------:|:--------:|
| `stylesheet`     | The path to the CSS stylesheet. | No       |
### addScript
Injects a script into the head.
```javascript
brackets.addScript(script);
```
| Parameter     | Description                      | Optional |
|:-------------:|:--------------------------------:|:--------:|
| `script`     | The path to the Javascript script. | No       |
### loadCSSFile
Loads a CSS file.
```javascript
brackets.loadCSSFile(file);
```
| Parameter     | Description                      | Optional |
|:-------------:|:--------------------------------:|:--------:|
| `file`     | The path to the CSS file. | No       |
### swapFavicon
Swaps favicons.
```javascript
brackets.swapFavicon(favicon)
```
| Parameter     | Description                      | Optional |
|:-------------:|:--------------------------------:|:--------:|
| `favicon`     | The path to the favicon. | No       |
### toggleElemVisibility
Toggles element visibility.
```javascript
brackets.toggleElemVisibility(id)
```
| Parameter     | Description                      | Optional |
|:-------------:|:--------------------------------:|:--------:|
| `id`     | The `id` of the element to toggle | No       |
### toggleClass
Toggles class of element.
```javascript
brackets.toggleClass(id, className)
```
| Parameter     | Description                      | Optional |
|:-------------:|:--------------------------------:|:--------:|
| `id`     | The `id` of the element to toggle | No       |

### detectURIArgs
Detects URI arguments.
```javascript
brackets.detectURIArgs()
```
| Parameter     | Description                      | Optional |
|:-------------:|:--------------------------------:|:--------:|
| `id`     | The `id` of the element to toggle | No       |
