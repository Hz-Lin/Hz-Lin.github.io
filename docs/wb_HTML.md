# HTML

## I.Elements and Structure

### 1.Introduction

HTML stands for Hyper Text Markup Language:

- A *markup* language is a computer language that defines the structure and presentation of raw text.
- In HTML, the computer can interpret *raw text* that is wrapped in HTML elements.
- *HyperText* is text displayed on a computer or device that provides access to other text through links, also known as *hyperlinks*.


### 2.HTML Anatomy

![HTML Anatomy](img/0001.html_anatomy.png)


### 3.Key HTML Elements

**The Body**  
Only content inside the opening and closing body tags can be displayed to the screen.

```HTML
<body>
  <p>Hello World</p>
</body>
```

**Headings**  
In HTML, there are six different headings, or heading elements.

```HTML
<body>
  <h1>main headings</h1>
  <h2>subheadings1</h2>
  <h3>subheadings2</h3>
  <h4>subheadings3</h4>
  <h5>subheadings4</h5>
  <h6>subheadings5</h6>
</body>
```

**Divs**  
<div\> is short for “division” or a container that divides the page into sections. It can contain any text or other HTML elements, such as links, images, or videos. 

```HTML
<body>
  <div>
    <h1>main headings</h1>
    <p>Great for grouping elements</p>
  </div>
</body>
```

**Attributes**  
Attributes are content added to the opening tag of an element and can be used in several different ways, from providing information to changing styling. Attributes are made up of the following two parts:

- The name of the attribute
- The value of the attribute

```HTML
  <div id="map">
    <p>Catan Map</p>
  </div>
```

**Displaying Text**  
If you want to display text in HTML, you can use a paragraph or span:

- Paragraphs (<p\>) contain a block of plain text.
- <span\> contains short pieces of text or other HTML. They are used to separate small pieces of content that are on the same line as other content.

It’s best to use a <span\> element when you want to target a specific piece of content that is inline, or on the same line as other text.

```HTML
  <div>
    <p>Generate a <span>Catan Map</span> here.</p>
  </div>
```

**Styling Text**  

- The <em\> tag will generally render as *italic* emphasis.
- The <strong\> will generally render as **bold** emphasis.

```HTML
  <div>
    <p>Here you can genrate a <strong>Catan Map</strong> for <em>four to five</em> player.</p>
  </div>
```

**Line Breaks**  

The line break element is unique because it is only composed of a starting tag <br\>. 
You can use it anywhere within your HTML code and a line break will be shown in the browser.

```HTML
  <div>
    <p>Here is a<br>Catan Map</p>
  </div>
```

**Unordered Lists**  

Use an unordered list tag (<ul\>) to create a list of items in no particular order. An unordered list outlines individual list items with a bullet point.  
The <ul\> element should not hold raw text and won’t automatically format raw text into an unordered list of items. Individual list items must be added to the unordered list using the <li\> tag. The <li\> or list item tag is used to describe an item in a list.


