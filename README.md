# Article_Lib

## Base :
### 1. Import lib
Caution: put this code in the tag ```<head>```
```html
<script src="https://sendeyo.com/get/d/69a7f65341"></script>
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
