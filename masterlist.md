This is a checklist that the May 2015 UI Design class contributes to about all general HTML/CSS steps.


# HTML
- [ ] Add your language to the HTML
      - `<html lang="en">`
- [ ] Remember to include a `meta` tag for UTF-8

- [ ] Include a link to your CSS file
      - `<link rel="stylesheet" type="text/css" href="stylesheet-name">`
- [ ] Add a reset
      - http://meyerweb.com/eric/tools/css/reset/

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
- [ ] Vertical align doesn't work with float.

# SASS
- [ ] Partial files
      - Create file names in this format: _file-name.scss
      - Link the partial files to the main .scss file with `@import 'reset';` at the top of your .scss main
      - Common partial files to create:
        - Colors: define all colors as variables
        - Type: define all fonts sizes and styles
        - Grid: define the grid system for the overall layout
