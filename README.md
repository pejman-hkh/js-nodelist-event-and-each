# JS NodeList
Add each function and all events to javascript NodeList


# Usage Example


```js
$('.mytabs > li').click(function() {
	$(this).data('aaa', 'bbbb');
	console.dir(  $(this).data('aaa', 'bbb') );

	console.log( $(this).data('aaa') );

   	$('.tab-content > div.active').each(function() {
    	console.log( this );
    }).removeClass('active');
    $('.tab-content '+this.dataset.target+'').addClass('active');
})

````


OR

```js
document.querySelectorAll('.mytabs > li').click(function() {
	document.querySelectorAll(this).data('aaa', 'bbbb');
	console.dir(  document.querySelectorAll(this).data('aaa', 'bbb') );

	console.log( document.querySelectorAll(this).data('aaa') );

   	document.querySelectorAll('.tab-content > div.active').each(function() {
    	console.log( this );
    }).removeClass('active');
    document.querySelectorAll('.tab-content '+this.dataset.target+'').addClass('active');
})

```