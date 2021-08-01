# The Odin Project - Google Homepage

## Goal

To deconstruct the [Google](http://www.google.com) homepage and rebuild it.

## Simple Page Element Observations

- CSS Grid is not used, Flexbox is.
- Google logo is an image.
- Search box has limited scaling with window size (defined min and max size).
- No text or image scaling with window size, only whitespace.
- Links underline on hover, buttons and boxes shadow.
- Hamburger menu and Google signin/profile logos can be recreated with CSS.
- Hamburger menu drops down to a fixed box with Google Apps (scrolls).
- Footer stacks vertically when squeezed. *Carbon neutral* goes to top, left elements next, and then right elements.

## To-Do

Header:

- [x] About, Store
- [x] Gmail, Images, Hamburger Button, Account Button
- [ ] ~~Hamburger Menu~~
- [x] Final formatting

Main:

- [x] Google Logo
- [x] Search Bar
- [x] Google Search Button, I'm Feeling Lucky Button
- [ ] ~~I'm Feeling Lucky slot machine effect~~
- [x] Final formatting

Footer:

- [x] Advertising, Business, How Search works links
- [x] Carbon neutral notice
- [x] Privacy, Terms, Settings links
- [x] Final formatting

## Skills Used

### Git/Github

Set up a repo in Github and actively updated it over the course of the project. Used .gitignore for scratch files.

### Developer Tools

Threw up the Google home page and my reconstruction side by side in Firefox to compare and contrast elements with devtools and quickly identify and copy property values.  Simple tweaks and experiments were tested live in browser.

### HTML

Created a basic scaffolding for the site with header, main, and footer sections. Built out the page from there using divs to group elements as necessary.

### CSS

Employed a mix of Grid and FlexBox to orient elements.  Wrangled SVG effects (magnifying glass, hamburger dots) to behave properly with CSS (their behavior seemed rather strange compared to an image). Faithfully duplicated the colors, styles, and hover/click effects employed. Used absolute, relative, and viewport units.
