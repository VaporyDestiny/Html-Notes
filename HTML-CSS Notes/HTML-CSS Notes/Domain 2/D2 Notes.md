# CSS Fundamentals

CSS
: Cascading Style Sheet

Rule set
: Basic building block of css

Selector
: Selects what element we want to change

Property
: What about the element we are changing

Value
: What we are setting the property to

Types of style sheets
: Inline: Written as an attribute in the element
: Internal: Written in the style element in the head element
: External: Written in a separate file that ends in .css

```html
<!--Inline CSS Example-->
<p style="color:red;"></p>
```

```html
<!--Internal CSS Example-->
<head>
    <style>
        p {
            color: red;
        }
    </style>
    <head></head>
</head>
```

```css
/* External CSS Example */
p {
    color: red;
}
```

Precedence
: What happens when two css rulesets on different style sheets conflict

```css
/* CSS file named style.css */
h1 {
    color: blue;
}
```

```html
<!-- HTML file named index.html -->
<!DOCTYPE html>
<html>
    <head>
        <style>
            #style1 {
                color: red;
                font-size: 30px;
            }
            #style2 {
                color: blue;
                font-size: 40px;
            }
            #style3 {
                color: green;
                font-size: 20px;
            }
        </style>
    </head>
    <body style="color: purple; font-size: 10px;">
        <h1>Race!</h1>
        <p id="style1">On your mark.</p>
        <p>Get ready</p>
        <p id="style3">Get set</p>
        <p style="color: green; font-size: 20px">Red light</p>
        <p style="color: red;">Soon</p>
        <p style="font-size: 30px">GO!</p>
    </body>
</html>
```

Race: Blue
On your mark.: Red, 30px
Get Ready: Purple, 10px
Get Set: Green, 20px
Red Light: Green, 20px
Soon: Red, 10px
GO!: Purple, 30px
