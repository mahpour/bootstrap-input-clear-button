# jQuery Clear Text plugin

Adds an iOS style clear button to the input fields using bootstrap icons. clear icon appears upon focus and will disappear on blur events.

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