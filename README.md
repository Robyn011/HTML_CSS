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
- Italic:<code> <em>Whenever you want to emphasis a sentence</em>, <i> to distinguish simply visually, such as a movie title</i> </code>
- Bold:  <code> <strong> used to show importance, seriousness, or urgency </strong>, <b> more generic and neutral and it does not carry any specific meaning </b> </code>

<code> 
<b> To summarize, there are four elements in HTML that allow us to mark text as bold or italicized. Two of them, "<em>" and "<strong>", convey meaning and serve a language-related purpose. The other two, "<i>" and "<b>", do not carry any specific meaning and are used solely for visual styling. <b>
</code>

 
### HTML Lists 

In HTML, there are three types of lists: unordered lists, ordered lists, and definition lists. 

- To define the entire list and specify its type, we wrap all the items in a <ul></ul> element, which stands for an unordered list.   
-The next type of list is the ordered list, which is similar to the unordered list but with a slight difference. Instead of using <ul> to wrap the list items, we use <ol></ol>. This will display the list with numbered steps, showing the order clearly. 
- Unordered and ordered lists are quite similar, except for the wrapping element they use. 
- In HTML, there is another type of list called the "definition list" or "description list."<dl></dl>. Unlike unordered or ordered lists with their list items. This is basically like you are creating a list of definitions. Within the <dl> tags you first add <dt></dt> and within that tag, it would be the definition title. After the <dt> tags you add <dd></dd> tags as the "definition description". 

<b>In summary, we now have three types of lists in HTML: unordered lists, ordered lists, and definition lists.</b>

### HTML Quotes 

To create something that looks like a quote you do this: 
<code>
<blockquote> 
<p> "write the quote here"</p> 
<cite>-name from who the quote came from</cite> (it would be italic) 
</blockquote> 
</code>

<q></q>= These quotes are simply typed in, but we believe they should be curly quotes, not straight ones
- HTML attributes provide additional information to HTML elements. In this case, the datetime attribute allows us to specify the date or time in a format that computers can understand. We write it like this: <time datetime="2025-05-08">May 8, 2025</time>.(Date Element)
-  for time stamps: <code><time datetime="14:15:28.5">14:15:28.5</time>.</code> (Time element)

<b> That is a basic introduction to HTML attributes, and we will delve deeper into them in a later section. For now, it is important to know that using the datetime attribute helps us communicate the precise timing to computers. <b>

### HTML Date and Time Inputs

 - To format a specific moment or range in time in a way that computers can understand, we use the <time> element. It consists of an opening tag <code> (<time>) and a closing tag (</time>) </code>. For example, we can use it like this: <code> <time>May 8th</time> or <time>May 8th 2025</time> </code>
 - the main purpose of the <code> <time> </code> element is to convey the exact date or time to computers. To achieve this, we use an HTML attribute called "datetime."

<b> That is a basic introduction to HTML attributes, and we'll delve deeper into them in a later section. For now, it's important to know that using the datetime attribute helps us communicate the precise timing to computers. </b>

### HTML Code, pre and br














   
 
