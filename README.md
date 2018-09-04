# Link.CSS
First, add the stylesheet in between the head:
```
<head>
  <link rel="stylesheet" href="link.css">
</head>
```
Create a link and give it the class 'lnk':
```
<a href="" class="lnk">Click Me</a>
```
This will create a default link.

You can adjust the size:
```
<a href="" class="lnk s">Click Me</a>
```
There are six total sizes: s, m, l, xl, xxl, xxl.
By using the class, "full", the link will fill up the div space.
```
<div style="display:inline-block; width: 500px">
	<a href="" class="lnk full">Your Own Size</a>
</div>
```
This link will be 500px wide.

Changing color:
```
<a href="" class="lnk lnkRed">Click Me</a>
```
There are 21 colors in total.
