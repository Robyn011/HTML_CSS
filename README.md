# HTML & CSS: Introduction to HTML: 
 
## The Function of HTML 

The Web relies on three different programming languages — HTML (HyperText Markup Language), CSS (Cascading Style Sheets), and JavaScript. Each language has its role to play. By combining these languages, developers can achieve resilience, robustness, and power in their websites.  

### HTML: 
 
- a straightforward structure without any programming logic, loops, or functions. 
- even if something is wrong with the HTML code, such as missing or misspelled elements, HTML ignores it/ takes a guess and fixes it 

 
### CSS: 

- It is responsible for how everything looks 
- When there is a hiccup in the CSS code, the browser is smart enough to skip that part and move on to the rest 

 

### JavaScript: 

- It is responsible for creating cool and interactive stuff. 
- If there is a problem within the code, unlike HTML and CSS, it won't try to figure out the problems of the code and it will just not work. 
 

## Text Formatting 

### HTML Syntax 

- It uses tags (opening tags and closing tags) 
- Some elements, like paragraphs, require both an opening and a closing tag, while others do not. 
- These tags work together to define elements 
- Inside the paragraph, there is another phrase that is emphasized, which we have turned into a separate element by using opening and closing em tags:
```html 
<p>abdbsdabi <em>emphasizes text</em></p> 
```
- HTML elements can be nested within one another 
- an entire HTML document is basically a bunch of HTML elements nested inside each other: it is called a DOM (Document Object Model) tree 

 

### HTML Headlines ```<h1></h1>... <h6></h6> ```

- these elements serve the purpose of dividing the content into smaller, more digestible chunks 
- The HTML elements used for marking up headlines come in six diverse types: h1, h2, h3, h4, h5, and h6. 
- Remember, there is no strict formula, but leveraging these six levels can greatly enhance the structure and coherence of your content. You have the flexibility to decide when and how to use the six levels of headline options to establish a semantic hierarchy.  

 

### HTML Bold and Italics 

- There are four HTML elements related to this, two for bold and two for italic. 
- Italic:
  ```html
  <em>Whenever you want to emphasis a sentence</em>, <i> to distinguish simply visually, such as a movie title</i>
  ```
- Bold:
  ```html
  <strong> used to show importance, seriousness, or urgency </strong>, <b> more generic and neutral and it does not carry any specific meaning </b>
  ```


<b> To summarize, there are four elements in HTML that allow us to mark text as bold or italicized. Two of them, ```<em>``` and ```<strong>```, convey meaning and serve a language-related purpose. The other two, ```<i>``` and ```<b>```, do not carry any specific meaning and are used solely for visual styling. <b>


 
### HTML Lists 

In HTML, there are three types of lists: unordered lists, ordered lists, and definition lists. 

- To define the entire list and specify its type, we wrap all the items in a ```<ul></ul>``` element, which stands for an unordered list.   
-The next type of list is the ordered list, which is similar to the unordered list but with a slight difference. Instead of using ```<ul>``` to wrap the list items, we use ```<ol></ol>```. This will display the list with numbered steps, showing the order clearly. 
- Unordered and ordered lists are quite similar, except for the wrapping element they use. 
- In HTML, there is another type of list called the "definition list" or "description list."```<dl></dl>```. Unlike unordered or ordered lists with their list items. This is basically like you are creating a list of definitions. Within the ```<dl>``` tags you first add ```<dt></dt>``` and within that tag, it would be the definition title. After the ```<dt>``` tags you add ```<dd></dd>``` tags as the "definition description". 

<b>In summary, we now have three types of lists in HTML: unordered lists, ordered lists, and definition lists.</b>

### HTML Quotes 

To create something that looks like a quote you do this: 
```html
<blockquote> 
<p> "write the quote here"</p> 
<cite>-name from who the quote came from</cite> (it would be italic) 
</blockquote> 
```

```html
<q></q> = <!--These quotes are simply typed in, but we believe they should be curly quotes, not straight ones
 HTML attributes provide additional information to HTML elements. In this case, the datetime attribute allows us to specify the date or time in a format that computers can understand. We write it like this -->
<time datetime="2025-05-08">May 8, 2025</time>.(Date Element)
-  for time stamps: <time datetime="14:15:28.5">14:15:28.5</time>.(Time element)
```
<b> That is a basic introduction to HTML attributes, and we will delve deeper into them in a later section. For now, it is important to know that using the datetime attribute helps us communicate the precise timing to computers. <b>

### HTML Date and Time Inputs

 - To format a specific moment or range in time in a way that computers can understand, we use the ```<time> ```element. It consists of an opening tag (```<time>```) and a closing tag (```</time>```). For example, we can use it like this:
   ```html
   <time>May 8th</time> or <time>May 8th 2025</time>
   ```
 - the main purpose of the <time>  element is to convey the exact date or time to computers. To achieve this, we use an HTML attribute called "datetime."

<b> That is a basic introduction to HTML attributes, and we'll delve deeper into them in a later section. For now, it's important to know that using the datetime attribute helps us communicate the precise timing to computers. </b>

### HTML Code, pre and br
- ```<code></code>``` is used for displaying some code onto the website.
- The text inside a ```<pre>``` element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks
- The ```<br>``` element is a simple tag without an opening or closing tag.It inserts a single line break.

### HTML Superscripts, Subscripts and Small Text
- ```<sub></sub>``` - will allow the element to drop down below the baseline and get a little smaller
- ```<sup></sup>```- will allow the element to jump up higher and get a little smaller.
- ```<small></small>``` - could be used for something such as copyright

<b>Small, sub, and sup are the elements that can help you get the details right when it comes to typography and conveying the full meaning of your content.</b>

## HTML Capabilities

### Troubleshooting and Debugging HTML Code

To access the developer tools, we can either right-click on the demo and select "inspect element," or opt to go to "tools," then "web developer," and choose "inspector." This will open up the developer tools, which offer a wide range of tabs with different tools or controls as it is sometimes also referred to.

### HTML Attributes
- Class attribute = used to assign one or more class names to an HTML element. These class names can be used to apply CSS styles or manipulate the element with JavaScript. By grouping elements with the same class name, you can manage their styles or behaviors collectively, rather than individually.
- Id Attribute = we can only use unique names once on an entire HTML page. IDs can be used for CSS targeting. IDs come in handy when we need to address specific elements in JavaScript or targeted links.

  <b>As a user, you can modify the content, but please note that refreshing the webpage will revert it back to the original state. This is because HTML alone only provides the editing functionality; the back-end developers need to create a system for capturing and saving the new content. The process of saving content varies across different websites and is typically implemented in JavaScript.</b>

### Aria Roles

- ARIA Roles are like extra attributes that we can add to HTML elements to make them more meaningful and help browsers understand what they represent.
- They make it possible for people with disabilities to use. Without them, it would be against the law if the websie is inaccessible for people with disabilities.
- ARIA came about when the web began replacing native applications, and it is particularly valuable for ensuring that everyone can use the full functionality of a complex interface in an app.
- ARIA is a powerful tool that greatly enhances web accessibility and is worth exploring further, especially working with a team struggling with semantic HTML or building a complex application interface
- ARIA Roles provide the necessary tools to make your site accessible to everyone.

### Formatting HTML

- If you use elements like ```<pre>, <code>, or <textarea>,``` or if you modify the whitespace handling with CSS, then extra spaces and indentations can matter
- In HTML, comments are inserted by typing ```<!--" at the start and "-->``` at the end. This feature helps us quickly identify when code is commented out and prevents any confusion when it does not function as expected.
-``` <video src= "file.mov"></video>```
- ```<canvas></canvas>```
- ```<img src= ""/>```

### Unusual Characters

- character chart: https://www.w3schools.com/html/html_symbols.asp

## HTML Navigation and Linking

### HTML Links

-``` <a href = "https://example.com">This is a link.</a>```
- ```<p>This is a sentence <a href = "https://example.com">witha link</a> in the midset od the text</p>```
- ```<p><a href = "https://example.com"><img src = "https://graphiccreationlab.weebly.com/uploads/5/1/1/2/51125965/3976798_orig.jpg"></a></p>```
- When we want to create a link,``` <i>we use the A element</i>```, which stands for anchor. To do this, we need to add an href attribute with a URL enclosed in quotes. This URL is where the link will take us. The term href stands for Hypertext Reference, a nerdy phrase from the past. Between the opening and closing A tags, we can place text or images, or both, to make them clickable.
-  An element is inline and can be placed within a paragraph or any other text, or even the image itself.
- the difference between HTTP and HTTPS: The "S" in HTTPS stands for Secure

<b>When creating links as developers or content creators, we need to include them ourselves. This protocol was one of the most significant inventions when the web was created. This is how links are made using absolute URLs.</b>

### HTML URL Pathways

- When linking to something within the same site and domain as the page containing the link URL can be used
- Creating a relative URL is not only useful for the A element (linking), but it is also a skill used to reference image files, video files, CSS, JavaScript files, or any other where a file’s path is specified.
- URLs can be either relative or absolute. Relative URLs are based on the current file's location, while absolute URLs start from the root of the website. By using folders and index.html files, we can create clean and user-friendly URLs.

### Navigation

- Each link is wrapped in an element with the correct URL, and then enclosed in an "li" element to create a list of links. To maintain the order, wrap the whole list in a "ul" element, which represents an unordered list. Finally, encompass the entire menu in a "nav" element to indicate that it is the site's navigation.

## HTML Working with Graphics and Images

### Images
- When we want to add an image to a webpage, we use the image element, which is simply written as IMG. ```<img src = "image.jpg" alt= "brown dog" width = "400" height = "300">```

elements we need to include within every image attribute:
1. we need the source attribute(SRC)
2. we need the alt attribute(ALT)
3. we need the width and the height of the image aka the width and heigh attribute

<b>It does not matter whether the height or the width is specified first. In HTML, the order of attributes within an element can be whatever you prefer.</b>

### Image Formats

There are four main file formats commonly used on the web these days, each with its own strengths and weaknesses when it comes to compressing images such as GIF, SVG, JPG, PNG.

#### GIF
- GIFs are great for compressing illustrations that have large areas of the same color
- supports 256 colors
- images can end up looking pixelated
- GIFs can have transparent areas, but the edges between transparent and solid parts can be jagged.

#### SVG
- SVGs are perfect for logos, icons, and other types of illustrations
- a vector file that contains instructions for drawing rather than individual pixels : it can be scaled to any size without losing quality, and the file size remains small
- a programming language for graphics
- can be exported from programs and handled just like other file formats on the web

#### JPG
- a popular choice for compressing photographs
- Most digital cameras save images in JPG format, but when placed on the web, it is important to resize and compress them appropriately.
- Avoid using gigantic, half-compressed JPGs on your websites : Slows down your website

#### PNG
- is a newer format
- works well when you need transparency in a photograph
- sometimes outperforms both GIF and JPG in compressing certain types of images

### Figcaption and Figures
- to match a caption to that image

  ```html
  <figure>
   <img src = "random.png" width = "960" height = "720" alt = "shiny black dog in the sun">
   <figcaption> Write any caption over here :) </figcaption>
  </figure>


- Use the figcaption element to wrap the text and designate it as a caption
- It is not just a regular paragraph or a generic div.
- Figures can be used for more than just images e.g: use them for an interactive graphic

## Working with Media

### Working With Audio
- The audio element is different from the image element because it has both an opening and a closing tag
- more modern and gives it more power and flexibility.
- we use a source attribute to provide the URL of the audio file
```<audio controls src ="audio.mp3"></audio>```
- different audio files: MP3
```html
<audio conrols>

 <source
    src = "http:example.com/birds.ogg"
     type = "audio/ogg; codec=opus">
   <source
     src = "https://s3-us-west-2amazonaws.com/s.odpo.io/10558/birds.mp3"
      type = "audio/mpeg">
   Sorry your browser does not support audio.

</audio>
```

<b>There are other attributes that can be used with the audio element too. For example, "loop" will make the file repeat from the beginning once it reaches the end. "Autoplay" can automatically play the audio as soon as the page loads, but be cautious with this one as most people dislike it when audio starts playing on a webpage without their consent. </b>

### Working With Video

- Just like the audio element, the video element has an opening and closing tag.
- To display a video, use the source attribute to specify the video file.
- the browser will automatically create a video player
  ```html
  <video>
    <source src = "https://s3-us-hest- z.a,azonaws.com/s.cdpn.io/10558/moonwalk.480p.vp3.webn" type = "video/mp4">
  </video>
'''

### Working With Captions and Subtitles

![Figure_62_Working_with_the_video_captions_and_the_track_element](https://github.com/user-attachments/assets/9a5c868b-c379-4ba0-8d84-71b43de9a375)

- We are going to use the track element and link it to a text file to add captions to the video
-  element adds functionality to the video player, allowing viewers to toggle captions on and off or switch between different subtitle options
-  file format called ibvtt - web video text tracks

### Embedding Media via Iframes

- refers to taking content from one site and placing it within the middle of another site's page. 

![Figure_64_Working_with_the_iFrame_element](https://github.com/user-attachments/assets/02f832b2-0d39-4b4f-b908-e80bbd539d7d)

## HTML Content Identification

### HTML Language Suppoort

- By setting things up correctly, search engines will understand which language websites are in.

![HTML-CSS101M1Fig63](https://github.com/user-attachments/assets/a4a39663-c7d0-49da-bf37-17a056c66e65)

- lang: used to specify the language of a webpage.(not only to indicate language or regional versions of a language, but also other qualities like the writing system used)
- the lang attribute is most commonly wrapped within the HTML element.
- the lang attribute only required to be set once
- dir- to indicate direction of where the computer should read the webpage from.
- the dir attribute is only required to be set once
![HTML-CSS101M1Fig64](https://github.com/user-attachments/assets/ff78bb48-9836-4750-8a82-973d161bfab5)

- meta charset = "UTF-8" : a massive specification that encodes content to support the vast range of characters, scripts, and even emojis.
- the meta charset attribute is used to inform the browser about the character set being use, otherwise your computer will expect one thing and but receives something else

- you place ``` meta charset = "UTF-8"``` within the head element on every page og the website
- <b>By defining the lang, dir, and charset for a project, you contribute to a more inclusive future for the web.</b>

### HTML Generic Elements, Div and Span

![HTML-CSS101M1Fig66](https://github.com/user-attachments/assets/bf3ddde0-44a7-48c7-8537-feea33051468)

- div: a block-level element
- span: an inline element
- Technically you can get away with using divs and spans for everything.

![Figure_69_Working_with_div_and_span_elements](https://github.com/user-attachments/assets/443a4daa-3c71-4c55-979f-df82e9d065c1)
There is a simple article wrapped in an article element. it had a headline and four paragraphs. When working on thhe CSS layout, you are required to group these paragraphs together, the goal is to add a background color only to the paragraphs, excluding everthing everything else. To achieve thism introduce a div with a class called "boxes". By targeting this box class with CSS, the changes taking effect can be seen. Now, imagine there is a particular phrase in the middle of the text that needs to be specifically targeted for some reason e.g. it is written in Spanish, and we want to change its language attribute go reflect that. To acconplish this, we use the inline element span to mark the desired phrase. Both div and span can make us of various global attrribues like class, id, lang. and aria roles.
Div and span come in handy when there is not another suitable element anf acting as a last resort option. 

## HTML Integration

### HTML Page 

- HTML files are a vital part of the web and plays a major role in explaining all the elements. attributes, roles, and tools used to mark up content on websites or web apps.

![Figure_71_Structure_of_the_whole_HTML_file_1](https://github.com/user-attachments/assets/9e927b27-decd-48f7-a990-7586a44dad7f)

What every website needs:

1. the file should start wuth a doctype statement which indicates the era of your HTML page
2. we need to enclose our code or everything but the "doctype" statement within a HTML element. ```<html></html>```

start with declaring the language being used within the page, then the content flow/ direction of the content. Within the HTML element, there are two main parts where your content goes:

1. ```<head></head>``` : contains all the metadata that the browser needs to know but will ot display on the page
2. ```<body></body>``` : for all the content and is composed of various elements already discussed in this course. The body is where most of the action happpens.

### Document Head

- character set: something you do not want your users to see and it is intended for the browser. 
- ensure all meta elements are only placed inside the head as the provide metadata about the page.

![Figure_72_HTML_file_Head_Section_1](https://github.com/user-attachments/assets/29480732-27dc-44be-927f-877cbaae9f6d)

- title element: not visible content. appears on the browser tab or bookmark when it is saved. the name that appears under top sites when a new browser is opened.

![Figure_73_The_Meta_Tag](https://github.com/user-attachments/assets/265d8124-de56-43ea-a424-4b5742ecb85e)

- meta element: has multiple uses:
  1. to inform the browser that the layout has ben adjusted to fit small screens, making it a responsive website.
  2. without the meta tag, the browser assumes the page follows an older layout designed fir desktops, which needs to be scaled down for mobile devices.
  3. the meta tag is employed to assign a name to the webpage when saved to the home screen
- It is also useful to include a description of the site, which appears in search engine results.

![Figure_74_The_Link_Element_1](https://github.com/user-attachments/assets/aa270abd-848f-4c54-a71b-1f75ced4d3ae)
- The link element is a crucial component used extensively within the head section. It serves to connect various assets that should load, such as CSS files, fonts, and favicons. To inform the browser about the type of asset, utilize the rel attribute.
- The script tag is a commonly used element in an HTML document's head. It instructs the browser to load a JavaScript file. Although it is typically placed at the end of the document, some also include it in the head.
**The HTML head serves as a central hub for connecting and setting up various components, ensuring that all assets are loaded and sharing page information with other sites and platforms. In a way, it is like the headquarters for getting the page off to a good start.**



### Content Structuring

#### 1. Main

The main element is used once per webpage and tells the browser where the main content is located.

#### 2. Header

difference between a head element and a header element:
- The head element contains doecument metadata, and a header element contains text to be displayed. The link element is a crucial component used extensively within the head section. It serves to connect various assets that should load, such as CSS files, fonts, and favicons. To inform the browser about the type of asset, utilize the rel attribute.
(Head is where the file's metadata lives and is not displayed to users. Header is used for site headers, article headers, and headers within the content. A header is usually found at the top of most web pages and may include a logo, site name, and navigation.)
  
#### 3. Footer

The footer signifies that there are extra things to convey, regardless of its position on the page.

#### 4. Article

-  often starts with a title, subtitle, author's name, and publication date
-  can also be considered a header
-  The article element wraps around any type of content unit, whether it is a long written article, a short snippet, a teaser card, a tweet, or even an app element. It represents a standalone unit of content.
-  containing links, copyright information, and additional details about the company


#### 5. Section

- used to mark sections of content
- It is also useful for dividing different topic zones on a website


#### 6. Aside

-  is for content that is off to the side
-  additional information, but it is not apart of the articles main flow.
-  Ads cam also be marked as an aside.The visual layout often conveys meanig and these HTML elements help transfer that meaning from the design to the content.

**Remember, the main element is used once per page to wrap the main content, while the header, footer, article, section, and aside elements are the five sectioning elements in HTML. They are combined and nested to structure the content of a webpage.**

## Working with Forms and Interactive Elements

### Form Fundamentals
![Figure_76_Working_with_forms](https://github.com/user-attachments/assets/d2697fcd-2c77-450b-9a9b-279b5871e9e4)

- they have been an essetial part of the web for a long time. They are used for various tasks like logging into websites, making purchases, conducting searches, and adding content.
- It is important to use semantic form elements in HTML instead of divs ad spans because it allows us to leverage the built-in power of the browser. Therefore we avoid wasting time and effort trying to recreate functionalities that already exist in the browser.
- By using HTML form elements, we ensure that it will be compatible with all devices and input/output hardware, even those we may not be familiar with.
- creating a form:
1. we start with the form element( informs the browser about the presence of a form using opening and closing tags)
- in the newsletter sighnup form, there will be two fields:
1. Name: Use the input element to provide places for users to input their name
2. Email: Use the input element to provide places for users to input their email
- These field names can be turned into labels using the label element.
- The input element does not have a closing tag due to its older structure
-  a button is needed for users to submit the form: use a button element

### More Form Functions 

```html

<form action = "success.html" method = "get">
  <label for= "name" >Name</label>
  <input name = "name" id = "name" type = "text">
  
  
  
</form>

```

- by leaving the "type" element, the browser will automatically assume that it is text. The browser will verify that the data that was entered is what is given within the type. I the user tries to type anything other than what is told, they will get a warning and would be asked to fix it.
- We can also add a required attribute to make the email feel required and the browser will insist that the user should fill out the email field before the form can be submitted, and if an email is not entered, the browser will not submit the form when the submit button is selected. Instead, a reminder to fill out the required fields is given.

### Other Form Element Types
```html
   <form action = "received.html" method = "get">
     <label for = "name">Name</label>
     <input id = "name" name = "name" type = "text">

     <label for = "email">Email</label>
     <input id = "email" name = "email" type = "email"
         placeholder = "you@example.com">
      
      <label for = "password">Password</label>
      <input id = "password" name = "password" type = "password">

      <label for= "search">Search</label>
      <input id = "search" name = "search" 
         type = "search" placeholder = "&#128269;">

      <label for = "phone">Phone Number</label>
      <input id = "phone" name = "phone" type = "tel">

```

- checkboxes, select lists, and radio buttons.
- checkboxes : use a label and an input and this time with a type of checkbox. Include an attribute of checked which tellls the browser that by default, when the page first loads, we would like this box to start out as checked. 

## Organizing Tabular Information in HTML

### Building HTML Tables

-To create an HTML table, you use several diffferent HTML elements in just the right combination. Table, TR, TH, and TD.

- ``<table></table>`` (table)- wraps the whole table
- ``<tr></tr>``(TR - table row) - wraps around a set of elements, defining them as belonging to the same row. used in colspan, rowspan, headers
- ``<th></th>``(TH -table header) - Defines a header for a column. used in colspan, rowspan, scope.
- ``<td></td>``(TD- table data) = marks the actual bits of data

In HTML we use the TR element to markup each row, a couple of TR opening and closing tags to make a couple of rows, then we put the content inside of each row. Then use the TD element to wrap a cell of content and the image with the image element. Including some CSS to make the table look more like something you want. We put the content for the header in the first row, wrapping each one in a TH element insead of a TD element. TD stands for table data, whilst TH stands for table header.


Why are Tables the prefered option for creating layouts in HTML email?
- Because the other better options are not supported

## Recap: Introduction to HTML

### MDN Web Docs

- a place to find authoritative reference documentation.(e.g. looking things up in a dictionary but pertaining to HTML)
- describes each element, each attribute, what it is used for, how to write the code, etc.
- has code examples, browser support charts, and links to where you can find that particular technology in a specification.
- There is also alot of great advice on MDN about how to best combine HTML elements for particular use cases and typaes of content.

### HTML Specifications

- a document written by the w3c that defines all of the rules of HTML, or Hypertext Markup Language
- The canonical source of truth about any web technology. 
- The web standard document from which that technology came. 
- The web and all of its parts, HTTP, URL, HTML, CSS, JavaScript. Each of these technologies exist because of a group of people collaborated on a plan for that technology.

### WCAG Guidelines 

- stands for Web Content Accessibility Guidelines
- it is the official specification on accessibility best practices.

### CSS 

- The styling of the website


# HTML & CSS: Introduction to CSS:

## HTML and CSS

### What is CSS?

- it is a style sheet that holds all the styles for your webpage.
- it affs visual appeal to your webpage. 
- to connect the css page to your HTML page, you simply just link them together
- A style sheet within the browser determines this unattractive appearance, with Times New Roman font, bold headings, and blue underlined link which aren't pleasing to the eye. By using CSS, it'll make our pages look better by changing the font, colors, and spacing.



CSS has two parts:
- The selector(specifies a pattern in HTML, and if the pattern matches. selects specific elements of our page)
- The declaration blocks(the styles within the declaration block are applied to the corresponding HTML elements)


### CSS Components

![HTML-CSS102Fig2](https://github.com/user-attachments/assets/84d648bc-b297-46c7-969d-0e94ea76ec96)

In CSS, each style declaration consists of two parts:

- A property
- A value

### Writing Your first Comment and Element Selector

![Figure_3_CSS_selector](https://github.com/user-attachments/assets/c5ac274f-e588-4bb6-9f07-a6037b1e1e7d)


### Writing a Class Selector

- You can assign classes to HTML elements to create a reference point for styling.
- class: an attribute that can be added to any HTML element, providing additional details about that element.
- we access the class attribute using a dot (.) efire the class name to differentiate it from HTML element selectors. e.g .intro
- we can use a span element with a class attribute 
- **Remember, the style declarations can be placed in any order. If we apply the "guarentee" class to a prograph element, the entire paragraph will be orange and bold. The HTML helps us select a specific part of a sentence.**

### Grouping Selectors

- Whenever you see selectors grouped together with commas, it means each of those items is a separate selector. Whether it is paragraphs, list items, or anything with the class "mineral," the text will be styled as green.
(the comma is like an "and" e.g, h1,p { color: green;}, which means make h1 green AND make p green)

### Decendent Selectors

- Decendant Selector- allows us to select list items that are decendants of either an ordered or an unordered list. The relationship can be direct or indirect similar to a family tree.
- the space between a list signifies a decendant relationship


## Identify a Color Scheme
 
 ### Formatting Color in CSS

hex codes color wheel:

![HTML-CSS102Fig17](https://github.com/user-attachments/assets/b676b61d-4806-40f6-88d0-ddd4d61462ba)

- usually 6-digits long
- consist of numbers zer to nine and letters A to F
- first two digit represent red, the next two represent green, and the final two represent blue.
- these digits correspond to numbers ranging from 0 to 255

Note: The chart of named colors also provides the hex value equivalent.

- whilst editing other people's CSS, you may come across different syntax worth mentioning. For instance, the hex value "778899" can be shortened to "789" if each two-digit pair is the same. This three digit format is relatively common but only applicable when the numbers are identical


"778899cc"

- Another syntax is the RGB format, where colors are written out using Base 10 numbers to specify the red, green, and blue channels. this dormat can also be represented as an eight-digit hex number or RGBA.
- The last "cc" number corresponds to Alpha, which relates to the opacity and transparency of the color.


### Background and Text Color in CSS 

similar to the "Formatting Color in CSSS" section, but you just use background-color: "whatever color you want".


### Understanding Images in CSS

- When working with images, it is important to choose the right format.

### Working with Background Images in CSS

- background: url('image url/ link in here')
- background images can flex and can tile both horizintally(x-axis) and vertically(y-axis)


tip: Percentages can be used to adjust where these images appear on the page. It depends on the background image you are using, but it can look good.

## CSS Boxes, Types and Sizes

### Undestanding Type in CSS

People who are not designers usually categorize fonts into two types:

1. Serif
2. Sans serif


With computer typesetting, sans serif fonts are mainly used on the web for ectended text because they look clean and are easy to read.

### Applying Type Formatting with CSS

To improve the appearance using different fonts:

1. add a font-family property to the body element. This property allows us to change the fonts on the page.
2. Use a font stack, starting eith Arial, then Helvetica, and finaly Sans-serif, The web browser will evaluate these fonts in order. If Aerial is installed, it will be displayed. Outherwise, it will try Helvetica. If neither is available, the default Sans-serif font on the computer will be used.

On your computer, have both Arial and Helvetica installed. If we look at the plus sign on the page, we can easily compare the two fonts. When Arial is removed from the font stack and only Helvetica is used, the plus sign shifts slightly. This demonstrates difference between the two fonts. If Helvetica is removed from the font stack and only Helvetica is used, the plus sign shifts slightly. This demonstrates the difference between the two fonts. If Helvetica is removed as well and we just use the font-family Sans-serif as the font for the entire page. However, it is not necessary to stick with just one use a serif font like Georgia and Times New Roman for h1.

NB: Remember to enclose font names with more than one word in quotes, and place the comma outside the quotes.

By having a contrasting serif font for headings and a Sans-serif font for paragraphs, we improve readability, especially for longer text on screens. We can also experiment with additional properties. For instance, we can make the text italic by adding font-style: italic. Additionally, if we want to remove the bold style from our headings, we can set the font weight to normal. Thede adjustments give our headings a unique look. Just by removing the Times text from the page and using Sans-serif font, the overall appearance has already improved signigicantly. It is much easier to read.

### Understanding and Applying size in CSS

There are two types of sizing:
#### Absolute:
- Pixels
- Don't change with screen size

### Relative:
- Percentage 
- Rems
- Changing with screen size zoom

Absolute sizes, such as points ir pixels, remain the same regargless of the screen size.

Reletive units, Like percentages or R-E-M can adjust based on the page size. When you zoom in, the font sizes using relative units scale proportionally with the rest of the page.

### Understanding the Box Model in CSS

- padding: The space between the border and the content. It cant also have its own background color. When we add padding, we are essentially pushing the edge of the box away from the contenent.

- Margin: The space between elements on the page. If you want to separate intersecting elements, adding some margin will do the trick.

We can assign properties to individual sides or apply them to all four sides at once. There are shorthand values available for border, padding, and margin, which provide a more concise way to set these properties. Only a few examples have been provided here, but there is more to explore on this topic. 


We can a red border of one pixel thickness by using CSS property : ```border : 1px solid red```. This will create a solid red border around the element. If we use the property ```border-left```, it will only apply the border to the left side of the box, while the other sides remain unaffected.


When it comes to setting margins, using ```margin: 1rem```will add one REM of margin to all four sides of the sides of the box. However, if we specifically use ```margin-right```, it will only add the margin to the right side of the box.

Padding also provides flexibiliy. We can use fractional REMs to set padding on all four sides or only on a single side. There are other shorthand notations available for padding and margin, as well as longhand properties for borders. But let's not dive into all the different variations right now to avoid confusion.

 ## Advanced CSS Properties and Concepts

 ### Styling Links With CSS

 The best way to approach links is by using the "a" anchor tag. We can specify "a" and set the color to 648fff, a nicer blue color than before. This style will apply to all links, including visited links, which will also turn blue. The reason behind this is that the browser's style sheet had blue and purple for links, but now we've added a new style that makes everything blue.

 NB: Remember, there are different states for links, and we can make expectations for each state

 One common exception is the "a:hover" state, which triggers when we hover over a link. in this case, the color can be changed to pink(fe6100) and the underline can be removed by using ```text-decoration: none```.


If we want separate styles for visited and unvisited links, we can also do that. We have to define the blue color as the ```a:link``` style for unvisited links, and the shade of purple as the ```a:visited``` style for visited links on your page, they should now appear in this pleasant shade off purple. And, of course, the hover style remains intact for when we roll our mouse over the links.

NB: Just keep in mind that the order of these styles in crucial. Either use ```a``` and then ```a:hover``` or ```a:link```, ```a:visited```, and ```a:hover``` in that specific order for the styling to work correctly.

### Inheritance in CSS
The ```*``` selector selects everything. 

### Debugging CSS with Borders and Background Colors

The distinction between block and inline elements is important. Block elements, take up the full width of their container "in this case, the body"

Inline Elements, like the links, are only as wide as their content.

tip: If you are unsure about how something looks, you need to see it in order to style it. Just put a border around it and add some background colors.









