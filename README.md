# wheelSwipe
Swipes events generate a mouse event - wheel.

## Example
``` HTML
  <script src='js/wheelSwipe.min.js'></script>
	<script>
		
		wheelSwipe();
  
		const	body = document.querySelector('body');

		body.addEventListener('wheel', function(e) {
			console.log(e)
		})

	</script>
```

## Settings

### wheelSwipe( selector, propagation, delta )

| Argument | Type | Description |
|----------|------|-------------|
| Selector    | string  | This is the css-selector of the DOM element that you want to use. Default = "body". |
| Propagation | boolean | If you don't need stopPropagation, use false. Default = true.  |
| Delta       | number  | WheelEvent.deltaX or WheelEvent.deltaY, Default = 125 |
