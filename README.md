To add my sound drops to Propane, add this to caveatPatchor.js:

```
    var head = $$('head')[0];
	if (head)
	{
	    var script = new Element('script', { type: 'text/javascript', src: 'http://chrismo.github.com/propane/hax.js?' + new Date().getTime()});
	    head.appendChild(script);
	}
```	