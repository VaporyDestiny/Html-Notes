# HTML Fundamentals

HTML
: Hypertext markup language

Element
: Basic bulding block of HTML

Start-Tag
: Designates the start of an element

End-Tag
: Designates the end of an element

Attribute
: Modifies an element

Void Elements
: Do not need an end tag bc they DO NOT CONTAIN anything that appears on screen

Metadata
: Data about data

## Contruct Markup that uses meta elements

script/noscript
: The script element can run code usually javascript
: The noscript element gives a warning to users whose browser's cannot run code

```html
<script>
    alert("Your browers support JS");
</script>
<noscript>Your browser does not support JS</noscript>
```

style
: The style element allows us to write internal CSS

```html
<style>
    body {
        color: green;
    }
</style>
```

meta
: The meta element is where information about our websites go

```html
<meta charset="utf-8" />
<meta name="keywords" content="piano, guitar, violin" />
<meta name="description" content="A place for music" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

The last one in the code above sets the width of the page to the users screen width.

## Construct well-formed page markup

!DOCTYPE
: Tells the browser what markup language we are using (Almost always html)

```html
<!DOCTYPE html>
```

html
: This element holds all of the html code

```html
<html lang="en-US"></html>
```

head
: This element hold the metadata

```html
<head>
    <title>My Website</title>
</head>
```

body
: This element holds all of the html that is VISIBLE on your page

```html
<body>
    <p>This is a paragraph inside body</p>
</body>
```

entities
: Special characters such as copyright or trademark symbol. Starts with "&" ends with ";"

```html
<p>&copy;</p>
<!-- This makes the copyright symbol -->
```
