# My Project

This project uses a 7-1 architecture pattern with SASS and HTML.

## Project Structure

The project has the following structure:

```
my-project
├── src
│   ├── sass
│   │   ├── abstracts
│   │   │   ├── _variables.scss
│   │   │   └── _functions.scss
│   │   ├── base
│   │   │   ├── _reset.scss
│   │   │   └── _typography.scss
│   │   ├── components
│   │   │   └── _buttons.scss
│   │   ├── layout
│   │   │   ├── _header.scss
│   │   │   └── _footer.scss
│   │   ├── pages
│   │   │   └── _home.scss
│   │   ├── themes
│   │   │   └── _theme.scss
│   │   └── vendors
│   │       └── _bootstrap.scss
│   └── main.scss
├── index.html
└── README.md
```

## Files

- `src/sass/abstracts/_variables.scss`: Contains all the Sass variables used throughout the project.
- `src/sass/abstracts/_functions.scss`: Contains all the Sass functions used throughout the project.
- `src/sass/base/_reset.scss`: Resets all the default styles that the browser applies.
- `src/sass/base/_typography.scss`: Contains all the base styles related to typography.
- `src/sass/components/_buttons.scss`: Contains all the styles related to buttons.
- `src/sass/layout/_header.scss`: Contains all the styles related to the header of the website.
- `src/sass/layout/_footer.scss`: Contains all the styles related to the footer of the website.
- `src/sass/pages/_home.scss`: Contains all the styles related to the home page.
- `src/sass/themes/_theme.scss`: Contains all the styles related to the theme of the website.
- `src/sass/vendors/_bootstrap.scss`: Contains all the styles related to the Bootstrap framework.
- `src/main.scss`: The main Sass file that imports all the other Sass files.
- `index.html`: The main HTML file of the website.

## Usage

To use this project, clone the repository and open `index.html` in your browser.
```