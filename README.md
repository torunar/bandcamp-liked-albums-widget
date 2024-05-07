# Widget to show liked/wishlisted albums from Bandcamp

## How to use

* Log in to your account at [https://bandcamp.com](https://bandcamp.com).
* Open the browser console — press F12 if you use in Firefox, Chrome or Safari.
* Paste and run the following code:
```javascript
alert(`https://torunar.github.io/bandcamp-liked-albums-widget/?fan_id=${
  JSON.parse(pagedata.dataset.blob).identities.fan.id
}`);
```

* Use URL from the pop-up message to embed your liked albums list anywhere:
```html
<iframe src="{widget URL}" width="690" height="720" frameborder="0" />
```
