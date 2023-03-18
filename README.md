# Sass_and_SCSS

 An introduction to the CSS preprocessor Sass

------------------------------------------------------

## Contents
1. CSS Preprocessor
	- 1.1 The syntax Sass or SCSS


------------------------------------------------------

# 1. CSS preprocessor
With a CSS preprocessor the writing of CSS can be made easier, e.g. by eliminating repetitive writing work. And the code handling can be simplified thereby.

**Sass** is just one of many other CSS preprocessors, others would be **Less** and **Stylus**. A preprocessor is used to automate annoying tasks and provide new functionality. A simple example would be when creating a web page with CSS, a green color is assigned countless times to various CSS properties. Once this color green is to be changed to blue, all green elements must now be assigned the color blue. This is where Sass comes into action. Instead of constantly changing repetitive values, the change is made in only one central location according to the DRY principle (Don't repeat yourself).


------------------------------------------------------

## 1.1. The Sass or SCSS syntax
Sass and SCSS are not necessarily two different CSS preprocessors, because both are in the end Sass (Syntactically Awesome Style Sheet). They are just two different grammars. The original syntax was **Sass syntax**, and the syntax introduced afterwards was SCSS (Sassy CSS). The newer SCSS syntax, unlike the Sass syntax, uses curly braces and semicolons. By not using curly braces and semicolons, the Sass syntax is shorter, nesting is done with an indentation.

- Difference between the two syntaxes:

    - SCSS syntax (style.scss)
   ```
    $but-size: 100%;
    $color1: #00ff00;
    $color2: #ff0000;
    $spacing-p: 1em;
    $spacing-m: 0.5em;

    .button-form {
	    width: $but-size;
	    padding: $spacing-p;
	    margin: $spacing-m;
	    background-color: $color1;
	    &:hover {
	    background-color: $color2;
	    color: $color1;
	    }
    }
   ```

    - Sass syntax (style.sass):
   ```
    $but-size: 100%
    $color1: #fcfcfc
    $color2: #fafafa
    $spacing-p: 1em
    $spacing-m: 0.5em

    .button-form 
	    width: $but-size
	    padding: $spacing-p
	    margin: $spacing-m
	    background-color: $color1
	    &:hover 
	    background-color: $color2
	    color: $color1
   ``` 
