# Using percentages and avoiding heights

## Percentages vs fixed width
- using width in px makes our layout fixed size. where as using percentage makes our layout responsive according to our parent element.
```html
<!DOCTYPE html>
<html>
<head>
	<style>
    	.parent{
        	background-color: green;
            width: 80%;
            height: 50px;
            padding: 25px;
            margin: 0 auto;
        }
        .child{
        	background-color: yellow;
            width: 90%;
            height: 37.5px;
            margin: 0 auto;
            
        }
    </style>
</head>

<body>
	<div class="parent">
    	<div class="child">
        </div>
   </div>
</body>
</html>
```

## Percentages in child
- here we can see that the child element is taking 90% of the width of the parent element.
