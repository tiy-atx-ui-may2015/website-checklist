This is a checklist that the May 2015 UI Design class contributes to about all general HTML/CSS steps.


# HTML
- [ ] Remember to include a `meta` tag for UTF-8
- [ ] Include a link to your CSS file
      - `<link rel="stylesheet" type="text/css" href="stylesheet-name">`
- [ ] Add a reset
      - http://meyerweb.com/eric/tools/css/reset/

- [ ] Use comments to organize your HTML.

 >    <! ————————  Typography  ————————> 

- [ ] For horizontal navs: Use <li>s in <ul>s in <div>s, along with display: in-line block.
- [ ] Remember to wrap your content in a main container div



# CSS
- [ ] Add reset
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
- [ ] Use alt text attributes on images
- [ ] Indent nested elements
- [ ] name class values with names related to the content
- [ ] When using `display: inline-block' make sure to add comments to your HTML to close the small space between divs
- [ ] Vertical align doesn't work with float.

- [ ] Use comments to organize your CSS:
 (The system from Shay Howe’s lessons works well.)

>  /*
  ========================================
  Grid
  ========================================
  */


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
      - type in the command “sass —watch "css/style.scss” (location of your sass file) to initialize Sass
      - remember to turn off when not in use

