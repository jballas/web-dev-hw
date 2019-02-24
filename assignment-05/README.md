# Julia Ballas

## MART 341.50

## Assignment

1. How many document <head> and <body> elements can a page have? How are these elements different, or what role do they play?

There can be an unlimited amount of elements within the head and body, but the head document elements are only used once, while elements in the body are reused. For instance, you only need to state the `<title>` of your site once in the `<head>`, while a `<h2>`  heading might be used multiple times throughout the `<body>`. The head elements are used to tell the browser information about the site, from meta information about the author. The body elements contain the content of the page and vary depending on what the website is about.

2. Describe the difference between structural and semantic markup.

Structural elements on a website are the bones. They are the bare necessity for a site to be understood. It includes Headings and paragraphs. Semantic markup adds in details to the website from empahsising important words with `<em>` tags to indicating abbreviations with `<abbr>`. If a website negelects the semantics, it will still function, but it will not be optimized for search engines or as user friendly.

## Free Response

While creating my simple recipe website I realized how easily it is to mix up `<sup>` and `<sub>` tags. It makes the code so much harder to read when you have numbers surrounded by these tags, but the HTML website is much clearer with these semantic markup elements.

### Coding
I practiced adding extra links in my website. In particular I wanted to experiment with the internal links to click to different portions of the same page. I made a link in the ingredients. `<a href ="#alternatives">Shortening</a>`. You click on shortening and it goes to the `<h3 id="alternatives">` However, since the website is so short, you can't really tell that it goes anywhere. It was good to practice this. I wonder if its possible to highlight a heading, after an internal link has been clicked. Or, if that is even worth bothering. On most webpages we are used to scrolling up and down on our phones and don't click on links unless we have to.
