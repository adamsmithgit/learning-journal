[Introduction](index) • [The Growth Mindset](index#growthmindset) • [Learning Markdown](#) • [The Coder's Computer](coderscomputer)

## Learning Markdown

Markdown is a way to format plain text.

Markdown uses symbols to denote how text should be displayed. For example ** denotes **bold** text.

Markdown is helpful to coders as it provides a simple way to write prose using the same text editor as they use for coding.

Markdown supports a limited set of text formating options such as headings, lists, links, quotes, and code blocks. Using markdown it is quick to write and format text. It is considered more readable than markup languages that require opening and closing tags for all elements.

Github has extended the core Markdown to support additional symbols. For example Github Flavored Markdown (GFM) supports a table layout using colons. 
```
| Item          | Cost          | Quantity  | Total    |
|:--------------|--------------:| ---------:|---------:|
| Cat           |          $30  |         4 |     $120 |
| Dog           |          $40  |         2 |      $80 |
| Cow           |          $90  |         1 |      $90 |
```

Which will render like this:

| Item          | Cost          | Quantity  | Total    |
|:--------------|--------------:| ---------:|---------:|
| Cat           |          $30  |         4 |     $120 |
| Dog           |          $40  |         2 |      $80 |
| Cow           |          $90  |         1 |      $90 |


In addition to being a plain-text formatting syntax, Markdown is a text to HTML software tool. That is, the plain-text is beign converted to structurally valid HTML to be rendered by the browser. It makes sense then, that it also supports the direct entry of HTML. This is helpful in cases where the writer wants to format something that is not supported by Markdown. If we in a situation where only Markdown core was supported, we'd need to use HTML to format a table like this: 

```
<table>
  <tr>
    <td>Column 1</td>
    <td>Column 1</td>
  </tr>
</table>
```
Which will be rendered like this:
<table>
  <tr>
    <td>Column 1</td>
    <td>Column 1</td>
  </tr>
</table>

[TOP](markdown)
<hr class="ljhr" />
