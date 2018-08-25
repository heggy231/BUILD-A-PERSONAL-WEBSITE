- Attribute for HTML tag pizza, attributes is like <> Options for each tag!
<pizza size="large" crust="thin" type="hawaiian">

- <input type="email"> pairs with submit button!
ex) 
  <input type="email">
  <input type="submit">

- To instruct the users what info to input: aka placeholder (add default text to input to inform user)
  <input type="email placeholder="Your email">

# CSS basic:
- HTML: structure of content that goes inside the tags.  Style by default browser style.

- CSS: Controls the style of the HTML content.  CSS allows change colors, fonts, layout, and more!

- For this lesson just add directly inside of HTML file
<style>


- property: controls one aspect of an HTML element's style, text-align, color, width, background, etc.
// text-align is property here
// center is value (options for text-align: left, right, center, justify)
<style>
  h1 {
    text-align: center;
  }
</style>

- How to select all tags to something?
2) Document structure:
The best way to select all elements at once is to have a parent element that contains all the other elements.
 For HTML, <body> design for selecting all elements

<body>
<h1>Anna Dowlin</h1>
<p>Hi! I'm Anna, a NYC-based marketer. Say hello!</p>
<input type="email" placeholder="Your email">
<input type="submit">
</body>

- Before body, start with <head> which contains elements such as <style>, <title> not part of visible content on the web page.

