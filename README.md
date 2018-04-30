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
npx lessc ./src/grid.less ./examples/basic/grid.css
npx lessc ./examples/basic/style.less ./examples/basic/style.css
```

---

###### Examples
```
<div class="container">
	<div class="row">
		<div class="col-5">1</div>
		<div class="col-7">2</div>
	</div>
</div>
```
