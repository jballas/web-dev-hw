
# Julia Ballas

## MART 341.50

## Final Project: Personal Website

1. Did you learn anything new about web development (ie using GitHub, version control, repositories)?

I was already familiar with github from a previous class on coding, so I jumped straight into using a repo and my github desktop. I can't imagine going back to manually uploading files, or connecting them. This semester I did access my files online, and updated from there sometimes.

2. Did you learn anything new about web design (ie using media, color, fonts)?

There is so much more to web design than learning your basic html. There is the structural components, but then the actual design is an entirely different thing. I found working from scratch much harder than I expected to get really good looking CSS websites. I will have to keep on practicing to get my ideas to appear online.

## Free Response
I want my final project to be an author website. The goal of the page is to feature the newest book available and encourage people to buy it. Mostly people find the website through word of mouth, rather than just stumbling on it. So I need to have excerpts availble to try and convince them it is worth buying.

I have been studying Adobe XD, so I'm going to layout a very rough draft of my page in XD before I begin to code. The tricky part will be recreating what I design in code.

### Colors

Main Color: light pink: #EA6E8B
bright pink: #EA008B;
Highlights: light blue: #3FA4BE
Shadows: dark blue: #1B4A56
Bright Call to Action: yellow #FFDE59
neutral: gray #707070

### Fonts

Main Font, logo font: Alternative Gothic No 2 D

basic web font: Noto Serif, Serif

### Icons

Instagram
Pinterest
YouTube
Amazon
Goodreads

### Coding HTML

I have my basic layout created already, with the meta, and basic html tags. Here's the 5 step plan.

- Step 1: basic html layout
- Step 2: create about, contact, book and blog pages
- Step 3: Add basic div and images to each page
- Step 4: Add text
- Step 5: `<nav>` bar, footer
- Step 6: create Contact form elements

This wasn't hard to put together. I used some of content from my wordpress website, but I made sure to recreate the code from scratch and not just copy and paste. After I get my layout and content, then I have to change it depending on my

### Coding CSS

- Step 1: Focus adding css to index.html: classes, h1, etc.
  - 1.2: Book
  - 1.3: blog
  - 1.4: About
  - 1.5: Contact
- Step 2: Add Typography
- Step 3: Nav bar, with hover using Pseduo classes
- Step 4: Contact form

### Issues or Concerns

Recaptcha from Google
I wanted to impliment a recaptcha in my contact form. So I researched Google's recaptcha and applied for a key for the website and added in a code. I'm not sure I implimented it correctly.

Script added inside the `<head>`
```HTML
<!-- Google Recaptcha Script from https://developers.google.com/recaptcha/docs/display -->
<script src="https://www.google.com/recaptcha/api.js" async defer></script>
```

Added this form to the `<body>` and a personalized sitekey from google.
```html
<form action="?" method="POST">
      <div class="g-recaptcha" data-sitekey="6LdataAUAAAAAHkIYpPo585VwuKMlanM8FfkkwAe"></div>
      <br/>
      <input type="submit" value="Submit">
    </form>
```


### Conclusion
