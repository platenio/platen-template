# Details

Details shortcode is a helper for `details` html5 element. It is going to replace `expand` shortcode.

## Example
```tpl
{{</* details "Title Closed By Default" */>}}
## Markdown content
Lorem markdownum insigne...
{{</* /details */>}}
```
```tpl
{{</* details title="Title Open By Default" open */>}}
## Markdown content
Lorem markdownum insigne...
{{</* /details */>}}
```

{{< details "Title Closed By Default" >}}
## Markdown content
Lorem markdownum insigne...
{{< /details >}}

{{< details "Title Open By Default" open >}}
## Markdown content
Lorem markdownum insigne...
{{< /details >}}
