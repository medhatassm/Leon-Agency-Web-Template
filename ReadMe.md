# Leon Website Template

## Description

This template is just design for home page of agency website, it have modern and simple design with small line of code to make it readable for any one, and it have a lot of features using on it to make the website responsive with anu screen size, like grid system and flex-box, and most important it use prefix to compatible to any browsers version.

I make this website home page to practice HTML & CSS after 40 day of learning them from ElZero Web School and Dr.Angela Boot-Camp Web Course.

## Tools:
- HTML
- CSS

## What i do in this template?

1. Using Stander of web design structure.

    - normalize.css file to return all element to default property value.

    - make a global rules for all the stander design.

    ```
    /* Start Global Rules*/
    * {
        box-sizing: border-box;
        -webkit-box-sizing: border-box;
        -moz-box-sizing: border-box;
        -moz-box-sizing: border-box;
    }   

    html {
        scroll-behavior: smooth;
    }

    body {
        font-family: "Work Sans", sans-serif;
    }
    ```

    - make variables to reuse it in element.

    ```
    /* Start Variables */
    :root {
        --main-color: #6155A0;
        --second-color: #8C89B0;
        --section-background: #f6f6f6;
        --p-color: #777;
        --padding-sections: 60px;
        --line-height-p: 1.6;
        --transition-duration: 0.5s;
    }

    /* End Variables */
    ```

2. Using Container to make all website have same padding and margin from parent at any screen size.

```
.container {
    padding-left: 15px;
    padding-right: 15px;
    margin-left: auto;
    margin-right: auto;
}
/* Small */
@media (min-width: 768px) {
    .container {
        width: 750px;
    }
}

/* Medium */
@media (min-width: 992px) {
    .container {
        width: 970px;
    }
}

/* Large */
@media (min-width: 1200px) {
    .container {
        width: 1170px;
    }
}
```

3. Using Grid system to design section like (services, Feature, and more..), to make the design responsive to any screen size with less line of code.

4. Using Media Query to make specific property value when website show at mobile screen.

5. Using Scrolling smooth to make website move between links smoothly.


>[!tip]
>This Website design is learning project from ElZero Web School Website,
>And this one of four template that i make to learn front-end basics. (1/4).

**Thanks For Reading and i hope you like it ❤️.**

*Made By Medhat Assem.*