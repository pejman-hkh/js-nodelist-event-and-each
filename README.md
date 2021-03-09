# JS NodeList
Add each function and all events to javascript NodeList


# Usage Example


```js
document.querySelectorAll('.mytabs > li').click(function() {
	$(this).data('aaa', 'bbbb');

	console.log( $(this).data('aaa') );

    document.querySelectorAll('.tab-content > div.active').removeClass('active');
    document.querySelectorAll('.tab-content '+this.dataset.target+'').addClass('active');
})
````
