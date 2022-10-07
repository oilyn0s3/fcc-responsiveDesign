## freeCodeCamp's Responsive Deisgn Certification
I'll be making this like a note, so that I could look this up later if I wanted to.  
The full freeCodeCamp's curriculm can be found [here](https://www.freecodecamp.org/learn/2022/responsive-web-design).  
## List of things I learned along the way  
### Different Tags and their meaning  
- ```<meta name="viewport" content="width=device-width, initial-scale=1.0" />``` : This gives the browser instructions on how to control the page's dimensions and scaling. The `width=device-width` part sets the width of the page to follow the screen-width of the device (which will vary depending on the device). The `initial-scale=1.0` part sets the initial zoom level when the page is first loaded by the browser.

- A HTML Document can be divided into various parts that convey or show what content they hold, this increases accessibility.
This can be done by dividing the document/layout into various segments using:
  - `<header> , <main> , <footer>` they work as their name suggests.  
  - `<section>` shows that the content inside is grouped (i.e. relates to a single theme), and should appear as an entry in an outline of the page.
  - `<div>` does not convey any meaning, aside from any found in its `class`, `id` `lang` and `title` attributes.  
  
- `<article>` element represents a self-contained composition in a page, which is intended to be independently distributable or reusable. Examples include: a forum post, a magazine or newspaper article, or a blog entry or any other independent item of content.  
- `<figure>` element represents self-contained content, potentially with an optional caption, which is specified using the `<figcaption>` element. The figure, its caption, and its contents are referenced as a single unit.
  eg:
  ```html
<figure>
    <img src="/media/cc0-images/elephant-660-480.jpg"
         alt="Elephant at sunset">
    <figcaption>An elephant at sunset</figcaption>
</figure>
```

