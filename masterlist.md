This is a checklist that the May 2015 UI Design class contributes to about all general HTML/CSS steps.


# HTML
- [ ] Remember to include a `meta` tag for UTF-8
- [ ] Include a link to your CSS file
      - `<link rel="stylesheet" type="text/css" href="stylesheet-name">`
- [ ] Add a reset
      - http://meyerweb.com/eric/tools/css/reset/
- [ ] Remember to always close your divs/tags
- [ ] Remember to keep your code clean (Ex. indentation)

- [ ] Use comments to organize your HTML.

 >    <! ————————  Typography  ————————>

- [ ] For horizontal navs: Use <li>s in <ul>s in <div>s, along with display: in-line block.
- [ ] Remember to wrap your content in a main container div



# CSS
- [ ] Add reset
- [ ] box-sizing: border-box;
- [ ] Close all tags
- [ ] Add box-sizing to layout (here or in a grid/layout Sass partial)
       ` html {
	                box-sizing: border-box;
          }
        *, *:before, *:after {
          	box-sizing: inherit;
          } `
- [ ] Font-size: when using em/rem's, make sure to set back-up size in pixels
      `font-size: 16px;
       font-size: 1rem;`

- [ ] For horizontal `<nav>`: Use `<li>`s in `<ul>`s in `<div>`s, along with `display: inline-block` or `float: left`.
- [ ] Remember to wrap your content in a main container div


- [ ] Use alt text attributes on images
- [ ] Indent nested elements
- [ ] name class values with names related to the content
- [ ] When using `display: inline-block' make sure to add comments to your HTML to close the small space between divs
- [ ] Vertical align doesn't work with float.


- [ ] Remember to close your elements with ;


- [ ] Use comments to organize your CSS:
 (The system from Shay Howe’s lessons works well.)

>  /*
  ========================================
  Grid
  ========================================
  */

#Terminal 
-[ ] terminal commands
    - ls = Short listing
    - cd [folder] = Change directory
    - touch [file] = Create new file
    - mkdir [dir] = Create new directory

# SASS
- [ ] Partial files
      - Create file names in this format: _file-name.scss
      - Link the partial files to the main .scss file with `@import 'reset';` at the top of your .scss main
      - Common partial files to create:
        - Colors: define all colors as variables
        - Type: define all fonts sizes and styles
        - Grid: define the grid system for the overall layout
        - Mix-ins: define all of the mix-ins for your site
      - DRY - Don't Repeat Yourself
- [ ] Initialize Sass
      - type in the command “sass --watch "css/style.scss” (location of your sass file) to initialize Sass
      - remember to turn off when not in use

# Responsive
- [ ] Add the below to your HTML body to make sure RWD works on all screen sizes
  `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
- [ ] Double check the RWD Checklist: http://rwdchecklist.com/
- [ ] Comment out the end of your media queries like the below to prevent confusing/missing brackets
  `} /*end of media query*/`

  [ ] Plan first by sketching
  [ ] Create smallest media query first
  [ ] Use em units for font-size
  [ ] Use percentages % for width, margin-left and margin-right

      - type in the command “sass —watch "css/style.scss” (location of your sass file) to initialize Sass
      - remember to turn off when not in use


