

Some code check here:


```js
// Stata code with highlighting 

levelsof x, local(lvls)

foreach x of local lvls {

	display "`x'"

	}

```