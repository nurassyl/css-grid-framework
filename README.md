### CSS Grid mini framework

---

#### Dependencies
- [normalize.css](https://necolas.github.io/normalize.css)
- [less](http://lesscss.org)

---

#### Templates
- [Figma](https://www.figma.com/file/DSMDgDGMv9i48ZRtZ9ibt7NA/CSS-Grid)

---

Compile to CSS
```
npx lessc ./src/grid.less ./examples/basic/grid.css --autoprefix
npx lessc ./examples/basic/style.less ./examples/basic/style.css --autoprefix
```

---

###### Examples
```
<div class="container">
	<div class="row">
		<div class="col col-2">
			<div>1</div>
		</div>
		<div class="col col-2">
			<div>2</div>
		</div>
	</div>
</div>
```
