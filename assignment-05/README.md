# Julia Ballas

## MART 341.50

## Assignment

1. How many document <head> and <body> elements can a page have? How are these elements different, or what role do they play?

A webpage has one `<head>` and one `<body>` element and they must contain certain elements. The head must have a `<title>` within, but there are other elements that help browsers collection information about your site, such as meta tags with author and description. Within the `<body>` of an HTML document, the content should be identified by heading and paragraph elements to make it easier to read. Other elements can significantly contribute to the webpage's readability, such as alternative text attributions within images for screen readers.

2. Describe the difference between structural and semantic markup.

Structural elements on a website are the bones. They are the bare necessity for a site to be understood. It includes headings, such as `<h1>` and paragraphs. Semantic markup adds in details to the website from emphasizing important words with `<em>` tags to indicate abbreviations with `<abbr>`. If a website neglects the semantics, it will still function, but it will not be optimized for search engines or as user friendly.

## Free Response

While creating my simple recipe website I realized how easy it is to mix up `<sup>` and `<sub>` tags. It makes the code so much harder to read when you have the tags surrounding the numbers, but the HTML website is much clearer.

### Coding
I practiced adding extra links in my website. In particular I wanted to experiment with an internal link, to click to different portions of the same page. I made a link within the ingredients. `<a href ="#alternatives">Shortening</a>`. You click on "shortening" and it goes to the heading belowed labeled: `<h3 id="alternatives">`. However, since the website is so short, you can't really tell that it goes anywhere. It was good to practice this. I wonder if its possible to highlight a heading, after an internal link has been clicked. Or, if that is even worth bothering. If we have to think of designing for mobile first, then we are more used to scrolling up and down on our phones, than clicking on links. Is the internal link still useful?
