Responsive Columns
=========
Pretty bloody simple responsive column layout. Licensed under [WTFPL](http://www.wtfpl.net) so go nuts.

This is how you make 2 columns.

```html
<div class="columns">
	<div class="columns-wrap">
		<div class="col span_1_of_2">
			Insert awesome
		</div>
		<div class="col span_1_of_2">
			Insert awesome
		</div>
	</div>
</div>
```

You can have up to 8 columns. If you're really tricky, you can do things like this.

```html
<div class="columns">
	<div class="columns-wrap">
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
</div>
```

If you want the columns to be spaced once they're turned to rows on mobile, just add `class="spaceOnMobile"` to the `columns` div.