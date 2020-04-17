# js-bookmarklets

### Click all the follow buttons in GIT following page
```js
javascript: Array.from(document.getElementsByTagName({{tagName}})).filter(a=> a[{{attr}}]=={{value}}).forEach(a=>a.click());void(0);
```
prompt version
```js
javascript: var tagName = prompt("TagName");var attr = prompt("AttributeName"); var value = prompt("Value");Array.from(document.getElementsByTagName(tagName)).filter(a=> a[attr]==value).forEach(a=>a.click());void(0);
```
