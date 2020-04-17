# js-bookmarklets

### Click all the follow buttons in GIT following page
```js
javascript: Array.from(document.getElementsByTagName({{tagName}})).filter(a=> a[{{attr}}]=={{value}}).forEach(a=>a.click());void(0);
```
prompt version
```js
javascript: var tagName = tagName || prompt("TagName");var attr = attr || prompt("AttributeName"); var value = value || prompt("Value");Array.from(document.getElementsByTagName(tagName)).filter(a=> a[attr]==value).forEach(a=>a.click());void(0);
```

### Inverval Clicking
start
```js
javascript:var inverval_clicking_id = inverval_clicking_id || prompt('dom_id');var timeout = prompt('How fast in ms', 100); var interval_clicking_int = setInterval(() => document.getElementById(inverval_clicking_id).click(), timeout)
```
stop
```js
javascript: clearInterval(interval_clicking_int)
```
