# corgicoding-theme-css

Render css based on the markdown format modified by typo.css.

***

- Author: Charles Chan
- Organization: Corgi Coding
- Github: https://github.com/Corgi-Coding

*version 1.0.4: fix `li pre` style*  
*version 1.0.4: fix `li pre` style*  
*version 1.0.5: add feat global style*

## Demo

Here is an html file for your reference [link](./demo/index.html)

## How to use

There are two ways to use it

### NPM

1. Install package

```
    npm install @corgicoding/theme
```

2. Import css file to the page.

``` js
    /* On-demand import */
    import "@corgicoding/theme/dist/normalize.css";
    import "@corgicoding/theme/dist/github.css";

    import "@corgicoding/theme";
```

3. Add the `c-html-render` class to the dom element to be rendered.

### HTML

1. DownLoad this Repository.
2. Unzip
3. Add the `c-html-render` class to the dom element to be rendered.
4. Add the following code to the page.

``` html
    <!--   Prevent compatibility issues caused by different browsers   --> 
    <link rel="stylesheet" href="./dist/normalize.css" />
    <!--   corgicoding.theme   -->
    <link rel="stylesheet" href="./dist/corgicoding.theme.min.css" />
    <!--   github style code render   -->
    <link rel="stylesheet" href="./dist/github.css" />


    <div class="c-html-render" />
```
