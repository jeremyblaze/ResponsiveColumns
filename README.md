Responsive Columns
=========
Pretty bloody simple responsive column layout. Licensed under [WTFPL](http://www.wtfpl.net) so go nuts.

This is how you make 2 columns...

```html
<div class="columns">
	<div class="col span_1_of_2">
		Insert awesome
	</div>
	<div class="col span_1_of_2">
		Insert awesome
	</div>
</div>
```

You can have up to 8 columns. If you're really tricky, you can do things like this...

```html
<div class="columns">
	<div class="col span_2_of_4">
		Insert awesome
	</div>
	<div class="col span_1_of_4">
		Insert awesome
	</div>
	<div class="col span_1_of_4">
		Insert awesome
	</div>
</div>
```

Other features...
- Instead of using `.columns` you can also use `.cols` (just slightly quicker to type)
- Add row spacing on mobile by adding the `.spaceOnMobile` class to the `.columns` element
- Add `.preserveOnMobile` to the `.columns` element and the columns will no longer break to rows on mobile
- Adjust the default gutter width by doing a find and replace of `60px`, and adjust the secondary gutter width by doing the same with `30px`
- Add `.vCenter` to the `.columns` element and the content will be centered vertically