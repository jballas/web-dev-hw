# Julia Ballas

## MART 341.50

## Assignment 09

1. Briefly describe the difference between the universal, element, class, and id selector types. When might you choose one over the other to style content?

  `*` or the universal selector allows you to select everything in your html file.

  An element selector allows you to select a particular element tag, such as `<h1>`, and change its properties throughout the html document.

  Inside your tags you use the class or id and can directly modify them. A class tag is preferable, because you can use multiple classes on one element, or reuse a class for different elements. The id is unique to only one element.


2. Describe your color palette, including the 3 colors you chose. List their color names, rgb values, or hex codes

  I choose three colors for my web design based on the images from the decades graphics. I wanted mainly cool colors, and to use a black and white pattern like a 1950s diner.

  - Mint Green `background-color:rgb(21, 166, 128);`
  - Stoplight red     `background-color: rgba(226, 16, 16, 0.75);`
  - Turquoise `color:rgb(47, 203, 200);`


## Free Response

### Coding Workflow

This week the main focus is developing a css style sheet. That means less work on the content and more of the style. So I just added a very quick HTML layout, with `<divs>` and `<spans>`. I made sure to add in classes and IDs so I can adjust them later.

I also want to try to make a checkerboard pattern out of CSS. I was inspired by the CSS rainbow art. Maybe this can be my banner at the top. It will be good practice to create this.

### Creating Art in CSS

CSS art is a pain when you try to use absolute positioning. I created four squares in my checkerboard and quit. Instead, I found a background image of that style. And instead made a header with 4 squares at the top in my color palette. When searching for how to create a checkerboard I discovered some pattern creation websites, and various people have created CSS backgrounds using the background gradient. This was a little beyond my level, so I decided to nix that idea. However, it did give me a good idea for my final project: the Hero image.

### Coding Struggles this week

CSS coding is so unforgiving. Several times I found myself frustrated because I forgot a hyphen in my ID. Or else I forgot a semi-colon. And I couldn't get my background image to appear because it was in my image folder and the style sheet is in the CSS folder. I figured it out eventually. Instead of `background-image: url("./images/checkerboard-pattern.jpg");` I had to have `background-image: url("../images/checkerboard-pattern.jpg");`. One extra dot and it worked!

### Conclusion

I am fairly satisfied with my workflow this week, even though it is a simple site. I experimented with CSS art, and I discovered more CSS elements I want to explore later.
