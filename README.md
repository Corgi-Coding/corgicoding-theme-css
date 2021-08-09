# corgicoding-theme-css

Render css based on the markdown format modified by typo.css.

***

- Author: Charles Chan
- Organization: Corgi Coding
- Github: https://github.com/Corgi-Coding

## How to use

There are two ways to use it

### Default

1. Add the `c-html-render` class to the dom element to be rendered.
2. Add the following code to the page.

``` html
    <!--   Prevent compatibility issues caused by different browsers   --> 
    <link rel="stylesheet" href="./style/normalize.css" />
    <!--   corgicoding.theme   -->
    <link rel="stylesheet" href="./style/corgicoding.theme.min.css" />
    <!--   github style code render   -->
    <link rel="stylesheet" href="./style/github.css" />
```

### NPM

1. Install package

```
    npm install corgicoding-theme-css
```

2. Import css file to the page.

```
    import "corgicoding-theme-css/dist/normalize.css";
    import "corgicoding-theme-css/dist/corgicoding.theme.min.css";

    import "corgicoding-theme-css/corgicoding.theme.min.css";
```

3. Add the `c-html-render` class to the dom element to be rendered.
