This span[^1] should have a custom style ([link]), but the text after the comma shouldn't, nor should the link.

The contents of this div should have a custom style, but [this link should not][link].

## This header should not have the div's custom style

> This blockquote should not.

    # This code block should not.

But this paragraph should.[^2]

This should have MyInnerStyle.

### This heading should not

This should have MyOuterStyle, but the following elision should have its own style. \...

> This blockquote should include **bold text with an elision: \...**

[^1]: Neither footnote nor footnote reference should get a custom style from its span.

[^2]: Neither footnote nor footnote reference should get a custom style from its div.

  [link]: http://example.com/
