# A website built from scratch

- HTML
- CSS
- Wireframes
- git
- Markdown

## HTML

We started creating the skeleton (! + Enterin VSCode), then we created the header, linked the CSS and the other two big containers, main and footer.

Header contains a logo, a heading, and navigation.

## HTML

```
<header>
  <div class="logo">
    <p>My Logo</p>
  </div>
  <h1>Personal Training</h1>
  <nav class="nav-items">
    <a href="">Training</a>
    <a href="">About Us</a>
    <a href="">Contact</a>
  </nav>
</header>
```

## CSS

Defined primary and secondary colors, ass them to the backgrounds and text colors.

Flex-box for the header to align the three elements inside centered and vertically

```
header {
  background-color: #ff9900;
  display: flex;
  flex-direction: column;
  align-items: center;
}
```
