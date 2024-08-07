# HTML & CSS introduction: 
 
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
- Inside the paragraph, there is another phrase that is emphasized, which we have turned into a separate element by using opening and closing em tags:<p>abdbsdabi <em>emphasizes text</em></p> 
- HTML elements can be nested within one another 
- an entire HTML document is basically a bunch of HTML elements nested inside each other: it is called a DOM (Document Object Model) tree 

 

### HTML Headlines <h1></h1>... <h6></h6> 

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


<b> To summarize, there are four elements in HTML that allow us to mark text as bold or italicized. Two of them, "<em>" and "<strong>", convey meaning and serve a language-related purpose. The other two, "<i>" and "<b>", do not carry any specific meaning and are used solely for visual styling. <b>


 
### HTML Lists 

In HTML, there are three types of lists: unordered lists, ordered lists, and definition lists. 

- To define the entire list and specify its type, we wrap all the items in a <ul></ul> element, which stands for an unordered list.   
-The next type of list is the ordered list, which is similar to the unordered list but with a slight difference. Instead of using <ul> to wrap the list items, we use <ol></ol>. This will display the list with numbered steps, showing the order clearly. 
- Unordered and ordered lists are quite similar, except for the wrapping element they use. 
- In HTML, there is another type of list called the "definition list" or "description list."<dl></dl>. Unlike unordered or ordered lists with their list items. This is basically like you are creating a list of definitions. Within the <dl> tags you first add <dt></dt> and within that tag, it would be the definition title. After the <dt> tags you add <dd></dd> tags as the "definition description". 

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
<q></q>= These quotes are simply typed in, but we believe they should be curly quotes, not straight ones
<!-- HTML attributes provide additional information to HTML elements. In this case, the datetime attribute allows us to specify the date or time in a format that computers can understand. We write it like this-->
<time datetime="2025-05-08">May 8, 2025</time>.(Date Element)
-  for time stamps: <time datetime="14:15:28.5">14:15:28.5</time>.(Time element)
```
<b> That is a basic introduction to HTML attributes, and we will delve deeper into them in a later section. For now, it is important to know that using the datetime attribute helps us communicate the precise timing to computers. <b>

### HTML Date and Time Inputs

 - To format a specific moment or range in time in a way that computers can understand, we use the <time> element. It consists of an opening tag (<time>) and a closing tag (</time>). For example, we can use it like this:
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
- Class attribute = 
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
- he A element is inline and can be placed within a paragraph or any other text, or even the image itself.
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
























   
 
