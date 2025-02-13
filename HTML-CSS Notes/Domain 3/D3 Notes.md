# Document structure using HTML

<p id="top"> Top </p>

## Tables

```html
<table>
    <tr>
        <td>Cell 1-a</td>
        <td>Cell 1-b</td>
    </tr>
    <tr>
        <td>Cell 2-a</td>
        <td>Cell 2-b</td>
    </tr>
</table>
```

<table>
    <tr>
        <td>
            Cell 1-a
        </td>
        <td>
            Cell 1-b
        </td>
    </tr>
    <tr>
        <td>
            Cell 2-a
        </td>
        <td>
            Cell 2-b
        </td>
    </tr>
</table>

Table headers can be created with `<th>`

```html
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Cell 1-a</td>
        <td>Cell 1-b</td>
    </tr>
    <tr>
        <td>Cell 2-a</td>
        <td>Cell 2-b</td>
    </tr>
</table>
```

<table>
    <tr>
        <th>
            Header 1
        </th>
        <th>
            Header 2
        </th>
    </tr>
    <tr>
        <td>
            Cell 1-a
        </td>
        <td>
            Cell 1-b
        </td>
    </tr>
    <tr>
        <td>
            Cell 2-a
        </td>
        <td>
            Cell 2-b
        </td>
    </tr>
</table>

## Headings

Headings
: Headings are for organizing a page into a hierarchy.
There are 6 heading levels: `<h1>` to `<h6>`
: `<h1>` is the largest
: `<h6>` is the smallest

## Line Break

We can start a new line by using a line break `<br>`

```html
<p>This has no line break.</p>
<p>
    This has a <br />
    line break.
</p>
```

<p>This has no line break.</p>
<p>This has a <br> line break.</p>

## Horizontal Rule

We can create a line on the page to separate content by creatinh a horizontal rule`<hr>`

<hr>

Span
: `<span>` elements allows us to style a single character, word, or short phrase

```html
<p>Today is a <span style="color:green;">special</span> day.</p>
```

<p>
Today is a <span style="color:green;">special</span> 
day.
</p>

## Construct and analyze markup that uses HTML5 semantic elements

Summary/Details

```html
<details>
    <summary>Click the show/hide the text</summary>
    <p>Hi there!</p>
    <details></details>
</details>
```

<details>
    <summary>Click the show/hide the text</summary>
    <p>Hi there!</p>
    <details></details>
</details>

Figure/Figcaption
: figure is for images, charts, and graphs
: figcaption is for the caption

## Construct an analyze markup that implements navigation

Anchor element
: Anchor elements are link
:They look like this `<a>`
:We use the `href=""` attribute for the link destination
: We use the `target=_"blank"` attribute to make the link open in a new tab

```html
<a href="example.com">example.com </a>
```

<a href="https://example.com">example.com </a>

Bookmarks
: We can create internal links by linking to ids

```html
<a href="#top"> Go to top of notes </a>
```

<a href="#top"> Go to top of notes </a>

Relative vs Absolute Links
: Relative links relate to files inside the website, for example `index.html`, `about.html`, `contact.html`
:Absolute links are unique addresses such as `google.com`, `gmetric.net`, `wikipedia.org`

## Navigating folders

"../"
: Goes up a folder

"name of file"/
: goes down into a folder of that name

"name of file"."file extension"
: runs that file

map/area
: The "map" element, along with the "area" element, allows for the creation of images that have spots on them that are clickable hyperlinks

## Forms
