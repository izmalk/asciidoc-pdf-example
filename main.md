An example of a basic [AsciiDoc](https://asciidoc.org) document prepared
by Doc Writer.

# Introduction {#_introduction}

A paragraph followed by an unordered list[^1] with square bullets.[^2]

-   item 1

-   item 2

-   item 3

# Main {#_main}

Here's how you say \"`Hello, World!`\" in Prawn:

::: formalpara-title
**Create a basic PDF document using Prawn**
:::

``` ruby
require 'prawn'

Prawn::Document.generate 'example.pdf' do
  text 'Hello, World!'
end
```

# Conclusion {#_conclusion}

That's all, folks!

[^1]: AsciiDoc supports unordered, ordered, and description lists.

[^2]: You may choose from square, disc, and circle for the bullet style.
