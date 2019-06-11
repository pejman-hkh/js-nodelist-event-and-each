# JS NodeList
Add each function and all events to javascript NodeList


# Usage Example


```js
$('.mytabs > li').click(function() {
	$(this).data('aaa', 'bbbb');

	console.log( $(this).data('aaa') );

    $('.tab-content > div.active').removeClass('active');
    $('.tab-content '+this.dataset.target+'').addClass('active');
})
````