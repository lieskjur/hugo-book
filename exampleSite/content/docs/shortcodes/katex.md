# KaTeX

KaTeX shortcode let you render math typesetting in markdown document. See [KaTeX](https://katex.org/)

## Example
{{< columns >}}

```latex
{{</* katex [display] [class="text-center"]  */>}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{</* /katex */>}}
```

<--->

{{< k display >}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{< /k >}}

{{< /columns >}}

## Display Mode Example

Here is some inline example: {{<k>}}\pi(x){{</k>}}, rendered in the same line. And below is `display` example, having `display: block`
{{< k display >}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{< /k >}}
Text continues here.
