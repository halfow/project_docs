# Mermaid

Some **text**!

```{admonition} Here's my title
:class: warning

Here's my admonition content
```

(section-two)=
## Here's another section

And some more content.

% This comment won't make it into the outputs!
And here's {ref}`a reference to this section <section-two>`.
I can also reference the section {ref}`section-two` without specifying my title.

:::{note}
And here's a note with a colon fence!
:::

And finally, here's a cool mermaid diagram!

```{mermaid}
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
