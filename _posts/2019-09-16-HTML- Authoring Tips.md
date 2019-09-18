---
published: true
---
## HTML Authoring Tips
This article is a series of tips to help you get more comfortable working with HTML.

### HTML Foundations
Every HTML page you create for this course will need the following code to begin and end each page, so please copy and paste this block of code every time you create a fresh HTML file:

```html
<!doctype html>

<head>
  <title>TITLE GOES HERE</title>
  <link rel="stylesheet" type="text/css" href="CECT.css">
</head>

<body>
    WEBSITE BODY CONTENT GOES HERE
</body>

</html>
```

This block begins with a declaration that the file you are creating is an HTML file, so the computer knows what it is reading when it parses the file. 
`<!doctype html>`

Then you are state information about the website as a whole. You should input the title of your website within the `<title>` tags. 

 ```html
<title>TITLE GOES HERE</title>
```
  
This title will appear in the tabs of your internet browser: 
```html
<title>Writing with Digital Technologies</title>
```
![HTML Tab Title Example]({{site.baseurl}}/img/HTML_Title_Tabs.png)

Then you link your external CSS stylesheet, which details the look and feel of your website. 
`<link rel="stylesheet" type="text/css" href="CECT.css">`

Then you need to close the `<head>` tag with 
`</head>`. You must always close your tags in HTML. Otherwise a computer will not know where to stop reading a line and will assume that everything after `<head>` belongs in the head of your website, and will never appear on screen. 

```html
<head>
   ...
</head>
```

I recommend, whenever you add a new tag, to close it out. Then input the content between the tags. For example, if you are adding a paragraph `<p>`, immediately type out the closing tag `</p>` before adding your paragraph text. 

Content within the `<body> </body>` tags will appear on screen and make up your webpages. 

### CSS
CSS  is a rule-based language, in which you define the rules, to specify styles that will be applied to your HTML document. 

For a better understanding of how CSS operates under the hood, I recommend reading this [CSS overview](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)from Mozilla.

Mozilla also has a great [CSS tutorial](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps) that you may find useful for your website project.

My main piece of advice for CSS is to, as much as possible, leave styling to CSS. Make your stylesheet thorough, and continue to add style definitions as you implement new elements in your HTML. Try to avoid inline styles for the sake of maintenance and consistency throughout your site.

### Structuring Your Code
When working in your authoring environment (Atom or similar) it is best practice to create a visual hierarchy by indenting lines. Here’s an example of what I mean:

```html
<div class="container">
  <div class="column left">
    <a href="#">
<button class="button-red">Register for classes</button>
</a>
    <div class="importantlinks">
      <h3>Important links</h3>
      <ul>
        <li><a href="#">Link 1</a></li>
        <li><a href="#">Link 2</a></li>
        <li><a href="#">Link 3</a></li>
        <li><a href="#">Link 4</a></li>
      </ul>
</div>
  </div>
</div>
```

Using the visual space of your authoring environment will help you organize and navigate your code. It is easy to see the relationships between the elements in the block of code above because I visually emphasized their hierarchical relationships. 

### Linking
Links are fragile. A broken link is a huge usability and accessibility concern. Test your links frequently to ensure that everything is still functional. 

Common causes of broken links include:
* Changing the linked file name
* Moving the linked file (thus changing the file path)
* Link rot (when linking to external sites. See the [Wikipedia](https://en.wikipedia.org/wiki/Link_rot) article for more information.)

### Navigation
Website navigation reflects the underlying structure of the website. If the website is constructed properly, the navigation elements will be effective and easy to use. The complexity of the site’s navigation is "ultimately determined by the site hierarchy" [(Lin, 2017)](https://www.uxbooth.com/articles/the-rules-for-modern-navigation/). Ideally, you want to create an information structure with a flat hierarchy containing relatively few layers, to make navigation quicker and "provide a clear, simple path to all the web pages from anywhere on the website" [(Lin, 2017)](https://www.uxbooth.com/articles/the-rules-for-modern-navigation/).

![Flat Navigation Hierarchy]({{site.baseurl}}/img/Flat_Hierarchy.jpg)

### Images 
When possible, make your images flexible. See this [Stack Overflow post](https://stackoverflow.com/questions/4684304/how-can-i-resize-an-image-dynamically-with-css-as-the-browser-width-height-chang) about creating flexible images using CSS. 

When finding images to use on your site, please be sure to use images or icons with Creative Commons licenses. I recommend using the following sources for images:
* [flikr Creative Commons](https://www.flickr.com/creativecommons/) for photos. 
* [Wikimedia Commons](https://commons.wikimedia.org/wiki/Main_Page) from Wikipedia for more Creative Commons media. 
* [The Noun Project](https://thenounproject.com/) for icons and vector images.
* [The University of Minnesota Photoshelter Gallery](https://umn.photoshelter.com/index)  
	**NOTE:** You can access images with your UMN login credentials.

### File organization
Keep your files in a safe and stable location on your computer (somewhere where you will not move them from once you tell git where the files are). If you move these files, git will not be able to find them and your GitHub Pages site will not work.
