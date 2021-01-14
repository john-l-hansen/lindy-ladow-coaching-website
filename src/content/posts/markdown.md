---
template: blog-post
title: Tools
slug: /tools
date: 2020-03-14 22:53
description: "These personal tools exercise mental, emotional, physical and
  spiritual muscles. The benefits are immense and range in degree and diversity
  dependent on personal investment. "
featuredImage: /assets/img.sunrisemessage.jpg
---
### Tapping

**Tapping** is also known as EFT (Emotional Freedom Technique). It is a powerful holistic healing technique that resolves a range of issues. It's based on the combined principles of ancient Chinese acupressure and modern psychology. The basic **Tapping** technique requires you to focus on a negative emotion at hand.

I have been tapping with Brad for years and love his simple straight forward meathod. He has short videos on everything one can imagine to tap about. All you have to do is show up and follow along.

[Brad Yates - YouTube](<Brad Yates - YouTube>)

## Yoga

Yoga is a set of specific exercises, called poses, combined with specific breathing techniques and meditation principles are the building blocks of a yoga class. If a pose causes pain or proves too difficult, there are variations and modifications that can be made to help students. Props like blocks, blankets and straps — even chairs — can be used to help you get the most benefit from the poses. Yoga is not one-size-fits-all: The best yoga workout for you will depend on your individual needs and goals.

The benefits of a regular yoga practice are wide-ranging. In general, a complete yoga workout can help keep your back and joints healthy, improve your overall posture, stretch and strengthen muscles and improve your balance, says Roger Cole, Ph.D., a psychobiologist and certified Iyengar yoga teacher. Yoga also has “a restorative side that is deeply relaxing and rejuvenating,” Dr. Cole says. “Relaxation is built into every yoga session.”

In addition, yoga’s focus on the breath can calm you and help you learn to be more mindful of your body, says Dr. Timothy McCall, the author of “Yoga as Medicine,” and that can help you to move with greater ease.

In recent years, more and more research is demonstrating the wide-ranging health benefits of yoga: 

**Reduce back pain**

**Strengthen bones**

**Improve balance**

**Stave off mental decline**

**Reduce stress**

**Relieve depression**

[Yoga With Adriene - YouTube](<Yoga With Adriene - YouTube>)

### The Work

<https://thework.com/>

### Gratitude Exercise

I discovered [Part 1: The 2020 Secret Santa Special - YouTube](<Part 1: The 2020 Secret Santa Special - YouTube>) and use these videos to expand my graditude. 

> ### Window Medifore
>
> Look at your life as if sitting on a sofa and looking out a window. There you are big and bold.
>
> Questions
>
> Medifore Formation
>
>
>
> ### Defensive Dung
>
> We are all defensive at times. The stories we tell ourselves to rationalize our defenses are really nuggets of gold. 
>
> Questions.
>
>
>
> 1.

### Lists

Markdown supports ordered (numbered) and unordered (bulleted) lists.

Unordered lists use asterisks, pluses, and hyphens -- interchangably
-- as list markers:

* Red
* Green
* Blue

is equivalent to:

* Red
* Green
* Blue

and:

* Red
* Green
* Blue

Ordered lists use numbers followed by periods:

1. Bird
2. McHale
3. Parish

It's important to note that the actual numbers you use to mark the
list have no effect on the HTML output Markdown produces. The HTML
Markdown produces from the above list is:

If you instead wrote the list in Markdown like this:

1. Bird
2. McHale
3. Parish

or even:

3. Bird
4. McHale
5. Parish

you'd get the exact same HTML output. The point is, if you want to,
you can use ordinal numbers in your ordered Markdown lists, so that
the numbers in your source match the numbers in your published HTML.
But if you want to be lazy, you don't have to.

To make lists look nice, you can wrap items with hanging indents:

* Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
  Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
  viverra nec, fringilla in, laoreet vitae, risus.
* Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
  Suspendisse id sem consectetuer libero luctus adipiscing.

But if you want to be lazy, you don't have to:

* Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
  Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
  viverra nec, fringilla in, laoreet vitae, risus.
* Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
  Suspendisse id sem consectetuer libero luctus adipiscing.

List items may consist of multiple paragraphs. Each subsequent
paragraph in a list item must be indented by either 4 spaces
or one tab:

1. This is a list item with two paragraphs. Lorem ipsum dolor
   sit amet, consectetuer adipiscing elit. Aliquam hendrerit
   mi posuere lectus.

   Vestibulum enim wisi, viverra nec, fringilla in, laoreet
   vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
   sit amet velit.
2. Suspendisse id sem consectetuer libero luctus adipiscing.

It looks nice if you indent every line of the subsequent
paragraphs, but here again, Markdown will allow you to be
lazy:

* This is a list item with two paragraphs.

  ```
  This is the second paragraph in the list item. You're
  ```

  only required to indent the first line. Lorem ipsum dolor
  sit amet, consectetuer adipiscing elit.
* Another item in the same list.

To put a blockquote within a list item, the blockquote's `>`
delimiters need to be indented:

* A list item with a blockquote:

  > This is a blockquote
  > inside a list item.

To put a code block within a list item, the code block needs
to be indented *twice* -- 8 spaces or two tabs:

* A list item with a code block:

  ```
  <code goes here>
  ```

### Code Blocks

Pre-formatted code blocks are used for writing about programming or
markup source code. Rather than forming normal paragraphs, the lines
of a code block are interpreted literally. Markdown wraps a code block
in both `<pre>` and `<code>` tags.

To produce a code block in Markdown, simply indent every line of the
block by at least 4 spaces or 1 tab.

```javascript
import React from "react"
import { Link, useStaticQuery, graphql } from "gatsby"
import Navigation from "../components/navigation"

export default ({ children }) => {
  const data = useStaticQuery(
    graphql`
      query {
        site {
          siteMetadata {
            title
          }
        }
      }
    `
  )
  return (
    <div className="site-wrapper">
      <header className="site-header">
        <div className="site-title">
          <Link to="/">{data.site.siteMetadata.title}</Link>
        </div>
        <Navigation />
      </header>
      {children}
    </div>
  )
}
```

This is a normal paragraph:

`This is a code block.`

Here is an example of AppleScript:

```
tell application "Foo"
    beep
end tell
```

A code block continues until it reaches a line that is not indented
(or the end of the article).

Within a code block, ampersands (`&`) and angle brackets (`<` and `>`)
are automatically converted into HTML entities. This makes it very
easy to include example HTML source code using Markdown -- just paste
it and indent it, and Markdown will handle the hassle of encoding the
ampersands and angle brackets. For example, this:

```
<div class="footer">
    &copy; 2004 Foo Corporation
</div>
```

![Royal Mail](/assets/royal-mail-unsplash.jpg "TOOLS")

Regular Markdown syntax is not processed within code blocks. E.g.,
asterisks are just literal asterisks within a code block. This means
it's also easy to use Markdown to write about Markdown's own syntax.

```shell
tell application "Foo"
    beep
end tel
```

## Span Elements

### Links

Markdown supports two style of links: *inline* and *reference*.

In both styles, the link text is delimited by \[square brackets].

To create an inline link, use a set of regular parentheses immediately
after the link text's closing square bracket. Inside the parentheses,
put the URL where you want the link to point, along with an *optional*
title for the link, surrounded in quotes. For example:

This is [an example](http://example.com/) inline link.

[This link](http://example.net/) has no title attribute.

### Emphasis

Markdown treats asterisks (`*`) and underscores (`_`) as indicators of
emphasis. Text wrapped with one `*` or `_` will be wrapped with an
HTML `<em>` tag; double `*`'s or `_`'s will be wrapped with an HTML
`<strong>` tag. E.g., this input:

*single asterisks*

*single underscores*

**double asterisks**

**double underscores**

### Code

To indicate a span of code, wrap it with backtick quotes (`` ` ``).
Unlike a pre-formatted code block, a code span indicates code within a
normal paragraph. For example:

Use the `printf()` function.

<iframe src="https://sunflower-business-mobi.netlify.app/" width="600" height="400"></iframe>