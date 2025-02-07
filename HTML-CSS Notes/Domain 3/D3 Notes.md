# Document structure using HTML

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
