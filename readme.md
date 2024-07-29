# HTML
<img src= "html5_bg_no_icons.png" alt="formats" width="" height="" >
 
## TABLE OF CONTENT
### 1.  Introduction to HTML
### 2.  HTML Basics
### 3.  Text Formatting
### 4.  Anchors   
### 5.  Images  
### 6.  Lists
### 7.  Tables      
### 8. References

 ## 1. Introduction to HTML
       
  ###  What is HTML?
       - HTML stands for Hyper Text Markup Language.
       - HTML is the standard markup language for creating Web pages.
       - HTML describes the structure of a Web page.

 ###   History of HTML
       HTML was created by Sir Tim Berners-Lee in late 1991 but was not officially released.
       It was published in 1995 as HTML 2.0. HTML 4.01 was published in late 1999 and was a major version of HTML.
 ###   Year	        Version
       1989	        Tim Berners-Lee invented www
       1991	        Tim Berners-Lee invented HTML
       1993	        Dave Raggett drafted HTML+
       1995	        HTML Working Group defined HTML 2.0
       1997	        W3C Recommendation: HTML 3.2
       1999	        W3C Recommendation: HTML 4.01
       2000	        W3C Recommendation: XHTML 1.0
       2008	        WHATWG HTML5 First Public Draft
## 2.  HTML Basics
       
       - All HTML documents must start with a document type declaration: <!DOCTYPE html>.

       - The HTML document itself begins with <html> and ends with </html>. 
       
**Example**
  ```jsx  
        <!DOCTYPE html>
         <html>
         <body>
        <h1>My First Heading</h1>
        <p>My first paragraph.</p>
        </body>
        </html>  
 ``` 
 ###   HTML Tags and Elements
       
       The HTML element is everything from the start tag to the end tag:
       <tagname>Content goes here...</tagname>
       Examples of some HTML elements:
       <h1>My First Heading</h1>
       <p>My first paragraph.</p>

 ###       Start tag	           Element content	         End tag
            <h1>	               My First Heading	          </h1>
            <p>	                   My first paragraph.	      </p>
            <br>	                   none	                   none
            **Example**
  ```jsx          
      <!DOCTYPE html>
     <html>
    <body>

       <h1>My First Heading</h1>
       <p>My first paragraph.</p>

      </body>
    </html>
 ```  
 ###  Attributes
       
       -All HTML elements can have attributes
       -Attributes provide additional information about 
        elements
       -Attributes are always specified in the start tag
       -Attributes usually come in name/value pairs like: name="value"

###  The href Attribute
      
      The <a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:  

**Example**              
  ```jsx
                <a href="https://www.w3schools.com">Visit W3Schools</a>
  
  ```   
 ###  The src Attribute   
       The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be 
        displayed:

**Example**
  ```jsx
        
                  <img src="img_girl.jpg">
  ```
###   The width and height Attributes
      The <img> tag should also contain the width and height attributes, which specify the width and height of the image (in 
      pixels):
      
**Example**
 ```jsx
                  <img src="img_girl.jpg" width="500" height="600">
 ```
 ###  The alt Attribute
      The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason 
      cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a 
      screen reader.
      
**Example**
 ```jsx
                  <img src="img_girl.jpg" alt="Girl with a jacket">
```
###  The style Attribute
     
     The style attribute is used to add styles to an element, such as color, font, size, and more.
     
**Example**
```jsx
                   <p style="color:red;">This is a red paragraph.</p>
```

**The following example specifies English as the language and United States as the country:**
```jsx

       <!DOCTYPE html>
       <html lang="en-US">
        <body>
        ...
       </body>
       </html>
```
###  The title Attribute
      The title attribute defines some extra information about an element.
      The value of the title attribute will be displayed as a Mohit when you mouse over the element:

**Example**
```jsx
              <p title="Mohit">This is a paragraph.</p>
```

###   Comments      
      
      HTML comments are not displayed in the browser, but they can help document your HTML source code.

**Example**
 ```jsx
             <!-- Write your comments here -->
 ```     
###   Add Comments
    
    With comments you can place notifications and reminders in your HTML code:

**Example**
```jsx
             <!-- This is a comment -->

             <p>This is a paragraph.</p>

             <!-- Remember to add more information here -->
```
##  3. Text Formatting
     Formatting elements were designed to display special types of text:
     -<b> - Bold text
     -<strong> - Important text
     -<i> - Italic text
     -<em> - Emphasized text
     -<mark> - Marked text
     -<small> - Smaller text
    
###  HTML <b> and <strong> Elements
     
     The HTML <b> element defines bold text, without any extra importance.

**Example**
 ```jsx
              <b>This text is bold</b>
```
    
###  HTML <i> and <em> Elements
      The HTML <i> element defines a part of text in an alternate voice or mood. 
      The content inside is typically displayed in italic.

      Tip: The <i> tag is often used to indicate a technical term, a phrase from another language, 
      a thought, a ship name, etc.

**Example**
 ```jsx
            <i>This text is italic</i>
```
      The HTML <em> element defines emphasized text. The content inside is typically displayed in italic.

      Tip: A screen reader will pronounce the words in <em> with an emphasis, using verbal stress.

**Example**
```jsx
            <em>This text is emphasized</em>
```
###  HTML <small> Element
      The HTML <small> element defines smaller text:

**Example**
```jsx
               <small>This is some smaller text.</small>
##   HTML Headings
       HTML headings are defined with the <h1> to <h6> tags.

       <h1> defines the most important heading. <h6> defines the least important heading.
       
**Example**
```jsx
                   <h1>Heading 1</h1>
                   <h2>Heading 2</h2>
                   <h3>Heading 3</h3>
                   <h4>Heading 4</h4>
                   <h5>Heading 5</h5>
                   <h6>Heading 6</h6>
 ```
 ##  HTML Paragraphs
       The HTML <p> element defines a paragraph.

       A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before 
       and after a paragraph.

**Example**
```jsx
                    <p>This is a paragraph.</p>
                    <p>This is another paragraph.</p>
 ```
 ##  4. Anchors 
 **Example**
 

###   What is Anchor Tag?
      The Anchor tag in HTML can be defined as a means to create a hyperlink that can link your current page on 
      which the text is being converted to hypertext via <a> (anchor tag) to another page.
      ```jsx     
      <a href="URL">Text Here</a>
 ```   

 ###   Program for Anchors tag       
        
**Example**
 ```jsx
            <!DOCTYPE html>
            <html>

            <body>
                  <a href="https://www.instagram.com/_mohit_prajapati12?igsh=cGtyMHVjNnplcWN2">Welcome to Mohit Prajapati</a>
               </body>

            </html>
 ```    
 ##  5.Images
 ###   HTML Image 
      The HTML <img> tag is used to embed an image in a web page.

      Images are not technically inserted into a web page; images are linked to web pages. The <img> 
      tag creates a holding space for the referenced image.

      The <img> tag is empty, it contains attributes only, and does not have a closing tag.

      The <img> tag has two required attributes:

      src - Specifies the path to the image
      alt - Specifies an alternate text for the image
      
**Example**
```jsx
         <img src="url" alt="alternatetext">
```
###  The src Attribute
      The required src attribute specifies the path (URL) to the image.

      -Note: When a web page loads, it is the browser, at that moment, that gets the image from a web server and inserts it 
       into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, 
       otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser 
       cannot find the image.

**Example**
```jsx
          <img src="img_chania.jpg" alt="Flowers in Chania">
```
###  The alt Attribute
       The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because 
       of slow connection, an error in the src attribute, or if the user uses a screen reader).

       The value of the alt attribute should describe the image:
      
**Example**
 ```jsx 

           <img src="img_chania.jpg" alt="Flowers in Chania">
```
###   Image Size - Width and Height
      You can use the style attribute to specify the width and height of an image.
      
**Example**
 ```jsx     
         <img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">
```
        Alternatively, you can use the width and height attributes:
         
**Example**
```jsx
         <img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">
```

##  6.Lists
       HTML lists allow web developers to group a set of related items in lists.

**Example**

       An unordered HTML list:                       An ordered HTML list:
            Item                                         First item
            Item                                         Second item
            Item                                         Third item
            Item                                         Fourth item

###   Unordered HTML List
       An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.
       The list items will be marked with bullets (small black circles) by default:

**Example**
 ```jsx      
           <ul>
            <li>Coffee</li>
            <li>Tea</li>
            <li>Milk</li>
           </ul>
```
###   Ordered HTML List
       An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.
       The list items will be marked with numbers by default:

**Example**
```jsx       
                   <ol>
                      <li>Coffee</li>
                      <li>Tea</li>
                      <li>Milk</li>
                   </ol>
```
##   7.Tables 
       HTML tables allow web developers to arrange data into rows and columns.
<img src= "Screenshot 2024-06-15 123800.png" alt="" width="" height="" >

       Define an HTML Table
       A table in HTML consists of table cells inside rows and columns.

**Example**

 ```jsx
               <table>
                 <tr>
                    <th>Company</th>
                    <th>Contact</th>
                    <th>Country</th>
                  </tr>
                  <tr>
                    <td>Alfreds Futterkiste</td>
                    <td>Maria Anders</td>
                    <td>Germany</td>
                  </tr>
                   <tr>
                   <td>Centro comercial Moctezuma</td>
                   <td>Francisco Chang</td>
                   <td>Mexico</td>
                   </tr>
              </table>
```
### Table Cells
     Each table cell is defined by a <td> and a </td> tag.

**Example**
```jsx
<table>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
</table>
```
### Table Rows
    Each table row starts with a <tr> and ends with a </tr> tag.

**Example**
```jsx
<table>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
  <tr>
    <td>16</td>
    <td>14</td>
    <td>10</td>
  </tr>
</table>
```
### Table Headers
    Sometimes you want your cells to be table header cells. In those cases use the <th> tag instead of the <td> tag:

**Example**
```jsx
<table>
  <tr>
    <th>Person 1</th>
    <th>Person 2</th>
    <th>Person 3</th>
  </tr>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
  <tr>
    <td>16</td>
    <td>14</td>
    <td>10</td>
  </tr>
</table>
```

## 11.References
 ### https://www.w3schools.com/html/default.asp
 ### https://www.geeksforgeeks.org/html-introduction/

