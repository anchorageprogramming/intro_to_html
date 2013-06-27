Introduction to HTML
=============

Cheat Sheet for the introduction to html class  
[Slides](https://docs.google.com/presentation/d/1IK-WMTb8YtQ14UJp652GOpRply1mggIqqdUI-ggYB-Q/edit?usp=sharing)

## Look at the source of a web page
1. Navigate to the [Anchorage Programming Workshop webiste](http://anchorageprogramming.org).
1. Right-click the page and select **View Page Source**.   

## Create the skeleton of your page
* Add the doctype `<!doctype html>`
* Add the html tags `<html></html>`
* Add the head tag `<head></head>`
* Nest the title in the head tag and add some text in between the opening and closing of the tag. `<title>Text</title>`
* Add the body tag `<body></body>`
* Write something inside the body
 
Should look something like this:
```html
<!DOCTYPE html> 
<html> 
  <head>
    <title>Hello World</title>
  </head>
  <body>
    Nice to meet ya!
  </body>
</html>
```

## Add Elements: paragraphs, headings, formatted text
All these elements should be nested inside the body tag.
* Create a paragraph tag. `<p>Text</p>` Add [text](https://www.google.com/search?q=ipsum&oq=ipsum) in between the opening and closing tag.
* Create several levels of headings, just add a number to h. Experiment! `<h1>Text</h1>`
* Bold some text. `<b>Text</b>`
* Italicize some text. `<em>Text</em>`

Here's an example:
```html
<!DOCTYPE html> 
<html> 
  <head>
    <title>Hello World</title>
  </head>
  <body>
    <p>Nice <b>to</b> meet <em>ya</em>!</p>
    <h1>Heading One</h1>
    <h2>Heading Two</h2>
    <h6>Heading Crazy</h6>
  </body>
</html>
```

## Add Elements: Link, Image, LineBreak
* Add a link: `<a href='url'>Text</a>`
* Add an image: `<img source='url' />` Use [google image search](http://images.google.com) to link to something good.
* Add a line break: `<br\>`

Here's an example:
```html
<!DOCTYPE html> 
<html> 
  <head>
    <title>Hello World</title>
  </head>
  <body>    
    <a href='http://commuterchallenge.bicycleanchorage.org'>Commute!</a>
    One <br/>Two<br/>
    <img src="http://www.readcwbooks.com/books.jpg" />
  </body>
</html>
```

## Add Elements: Ordered Lists, Unordered Lists, Tables
* Add an ordered list: `<ol><li>item</item></ol>`
* Add an unordered list: `<ul><li>item</li></ul>`
* Add a table: `<table><tr><td>Column</td></tr><tr><td>Value</td></tr></table>`

Here's an example:
```html
<!DOCTYPE html> 
<html> 
  <head>
    <title>Hello World</title>
  </head>
  <body>
    <h3>Ordered List</h3>
    <ol>
      <li>Wake up.</li>
      <li>Get dressed.</li>
      <li>Bike!</li>
    </ol>
    <h3>Unordered List</h3>
    <ul>
      <li>Planes</li>
      <li>Trains</li>
      <li>Automobiles</li>
    </ul>
    <h3>Table</h3>
    <table>
      <tr>
        <th>Name</th>
        <th>Average Miles</th>
      </tr>
      <tr>
        <td>Becky</td>
        <td>500</td>
      </tr>
      <tr>
        <td>Coral</td>
        <td>5000</td>
      </tr>
    </table>
  </body>
</html>
```
## Next steps
Sign up for Code academy and take the web Fundamentals class!  
[Code Academy](http://www.codecademy.com/tracks/web) 
