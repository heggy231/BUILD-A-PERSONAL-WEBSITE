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
  * <title> goes before style tag inside of head tag.

- How to tell Browswer we are using HTML5 markup?
  * Write <!DOCTYPE html> first line before everything else!  this tells browser we're using the newest version, HTML5.

- Boilerplate: basic foundation structure that every website have doctype, head, body

<!DOCTYPE html>
<head>
  <!-- meta info goes here -->
</head>
<body>
  <!-- Content goes here -->
</body>

3. 3 common styles
 1) background: black; // change background color
 2) color: white; // font
 3) font-family: helvetica; // change font look using font-family!

-- stage one (iteration 1) completed! --

- Part 3: Images and form styling
objective: 
1) include logo img,
2) Add a background img, 
3) Style the email input form


- adding img: 
<img src="/assets/anna.png">
* 2 types of url
// relative url (works only file is on the same domain as the current pg)
// absolute url (links includes http:// and full domain name before the directory (/assets/logo.png))

* Add background img
  background: url("url");
  - Prevent img to look tied
    background-size: cover; // flexes as img 

* Form styles
  - font-size: 22px // making font-sz bigger!

* resource for images unsplash it for background image
https://picsum.photos/images
Image Gallery

Get a specific image by appending ?image to the end of the url

https://picsum.photos/200/300?image=994

* input styling
  1) border to be 0
  2) padding is space btwn edge of element and the stuff inside it.  
  we will even it out for input element

* call to action! Make the submit button noticeable.
  select element by attributing square bracket
  ex)
  input[type="submit"] {
    background: red;
    color: white;
  }

  ex) to style email 
    <input type="email" placeholder="Your email">
  input[type="email"] 
  or
  input[placeholder="Your email"]
  
  
