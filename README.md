# jQuery Clear Text plugin

## Usage:

```javascript
$("input").inputClear();
```

To exclude certain input elements from having clear option:

```html
<input type="text" class="no-clear" />
```

or if you can't touch your existing code just add exclude option:

```javascript
var options= {'exclude':'myclass' }
$("input").inputClear(options);
```

Live example on JsFiddle:  http://jsfiddle.net/ELGga/embedded/result/