[version]: https://img.shields.io/badge/Download-1.0.0-blue
[download]: https://sendeyo.com/get/d/69a7f65341

[ ![version][] ][download]

# Article_Lib

## Base :
### 1. Import lib
Go to `https://github.com/PastaLaPate/Article_Lib/tree/Stable`
Download the file article_lib.js
Caution: import the lib in tag ```<head>```
```html
<script type="text/javascript" src="path/article_lib.js"></script>
```

### 2. Create section
The first step is create an section

`Caution: use this code after the import but still in the tag <head>`

```js
window.onload = function get_body() {
  var body = document.getElementsByTagName('body')[0];
  addSection("section_name", parent, "section_css_class", "sub_container_class", "sub_container_id");
}
```

The fonction
```js
window.onload = function get_body() {
var body = document.getElementsByTagName('body')[0];
}
```
Allows me to have the `<body>` who will serve me to define the parent

I will use the following parameters : `"section_name" : "inreduction"`,`parent : body`,`section_css_class : "in_reduction"`,`"sub_container_class" : "sub_container"`,`"sub_container_id : "subcontainer"`

It gives that

```html

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<script type="text/javascript" src="js/article_lib.js"></script>
	<script type="text/javascript">
		window.onload = function get_body() {
  			var body = document.getElementsByTagName('body')[0];
			addSection("in_reduction", body, "in_reduction", "sub_container", "sub_container");
		}
	</script>
	<title></title>
</head>
<body>
	<div class="section_container">
		<div class="in_reduction" id="in_reduction">
			<div class="sub_container" id="sub_container"></div>
		</div>
	</div>
</body>
</html>
```
