# JS NodeList Add Events And Each Functions
Add each function and all events to javascript NodeList


# Usage Example
`qsa = document.querySelectorAll` and `qs = document.querySelector`

```js
qs('.mytabs > li').click(function() {
	alert('test1');
});


qsa('.mytabs > li').click(function() {
    var cDiv = qs('.tab-content '+this.dataset.target+'');
    qs('.tab-content > div.active').classList.remove('active');
    cDiv.classList.add('active');
});
````