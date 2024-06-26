# HTML Advanced
![Static Badge](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

This project involves creating a webpage from scratch, based on a design file provided in [Figma](https://www.figma.com/file/XrEAsu1vQj5fhVaNG38d2W/Homepage?type=design&node-id=0-1&mode=design&t=odbpkpcMXB66kvTC-0). The focus of this project is to build a solid foundation in HTML by crafting an HTML structure without any CSS styling.


## Learning Objectives

### What is HTML?
HTML (HyperText Markup Language) is the standard markup language used to create web pages. It structures the web content through the use of various elements which are denoted by tags. HTML is used to format text, create hyperlinks, insert images, forms, and other types of data, forming the building blocks of all websites.

In this project, the basic structure of an HTML document was established in **Task 1** with the use of tags like `<html>`, `<head>`, `<body>`, and later on with semantic elements like `<header>`, `<main>`, `<section>`, and `<footer>`.

### How do we create an HTML page from a wireframe?

Creating an HTML page from a wireframe involves interpreting a visual guide (the wireframe) that represents the skeletal framework of a webpage and translating it into HTML code. This includes laying out the structural elements, placing content blocks according to the design, and preparing the page for further styling and interactivity.

**Task 4** involved creating a video list section as specified by the wireframe design, using elements like `<div>`, `<h1>`, `<img>`, and `<p>` to layout the section in accordance with the design.

### What is a markup language?

A markup language is a system for annotating a document in a way that is syntactically distinguishable from the text. It uses tags to label pieces of content such as headings, paragraphs, and links, allowing devices to manipulate, and present the text. HTML is one of the most widely used markup languages for creating web pages and applications.

Throughout this project, HTML was used as the markup language to create the structure of the webpage defining headers, main content areas, and footers.

### What is DOM?

The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects. Programming languages like JavaScript can interact with the page.

In this project, when we structured the document with elements like `<header>`, `<section>`, and `<footer>`, the DOM turns each of these tags into nodes that can be accessed and manipulated via JavaScript.

### What is an element / tag?

In HTML, an **element** consists of a start tag, an end tag, the content in between, and the attributes of the tag. A **tag** is used to create an element and marks the start and end of an element content like `<h1>` to `</h1>`, indicating header text.

In **Task 2**, the `<header>` element contains several other elements such as `<nav>`, `<a>`, and `<img>`. Tags are used to create structured and nested elements.

### What is an attribute?

Attributes provide additional information about HTML elements. They are always specified in the start tag and usually consist of name/value pairs like name="value". Attributes are used for identifying unique elements, setting up links, adjusting images, etc.

In **Task 7**, `<img src="logo.png" alt="Smile logo">` uses src and alt attributes. The src attribute specifies the path to the image file, while the alt attribute provides alternative text describing the image.

### What is the purpose of each HTML tag?

Each HTML tag has a specific purpose, usually related to the structure or function of the content. Semantic tags, such as `<header>`, `<footer>`, `<article>`, and `<section>`, indicate the role of the content in the overall context of the document.

In **Task 6**, we created an FAQ section. The HTML tags used in this task and their specific purposes:

`<section>`: Groups related content, marking the FAQ area as a significant section of the webpage.

`<h1>`: Serves as the main title for the FAQ section.

`<div>`: Acts as a flexible container for structuring the FAQs into rows and individual items, important for layout organization.

`<h2>`: Indicates the question within each FAQ item, structuring the content hierarchically under the main section heading.

`<p>`: Provides the answers, detailing the information related to each question.

## Tasks

### Task 1
Create the basic structure of an HTML page and construct the header based on a provided wireframe.

![f08f357fc2c894d821a29b7f907f26089ec68d86](https://github.com/ThatsVie/atlas-web-development/assets/143755961/9ddd2b3c-4466-4759-9077-1de89bf2f256)


Start with the foundational HTML5 structure, which includes the `<!DOCTYPE html>` declaration, and the `<html>`, `<head>`, and `<body>` elements.

Within the `<body>`, insert the `<header>` tag.

The `<header>` contains:

A clickable logo using `<a>` and `<img>` tags.

Navigation links wrapped within a `<div>`

### Task 2
Enhance the header by adding a banner that includes multiple text and image elements. This task focuses on structuring content semantically within the header.

![d3f0dba16af368a681919fb44306fadfb2499b54](https://github.com/ThatsVie/atlas-web-development/assets/143755961/1fdec0cb-f874-4a54-b612-7899787acd99)

Insert a `<section>` within the `<header>` to delineate the banner area.

Add a `<div>` containing:

A `<h1>` heading for the main title.

A `<p>` tag for slogan.

A `<button>` for registration.

Secondary Content Block:

Use a `<h2>` heading for a secondary, supportive title.

Include a `<div>` that houses four smaller blocks. 

An `<img>` tag 

A `<h3>` heading for the title of the feature.

A `<p>` tag for a brief description

Below the `<header>`, insert a `<main>` element to separate the main content of the webpage from the header.

### Task 3
Incorporate a quote block below the banner within the `<main>` section of the webpage. 

![e898eac85272d52f5528ea81678000045a37017a](https://github.com/ThatsVie/atlas-web-development/assets/143755961/535e9584-e8d0-4274-a76e-03dae3fbf942)

Within the `<main>` element, add a new `<section>` tag for the quote.

Inside the `<section>`, place a `<div>` that will contain all elements related to the quote.

Add an `<img>` tag related to the quote.

Use a `<blockquote>` tag for encapsulating the quoted text.

Provide a text tag (`<p>`) for the quote's author.

Include additional descriptive text `<p>`


### Task 4
Create a section dedicated to a list of video tutorials. 

![a5712ac70330c6812c6aee2bf21efe7ac53d1397](https://github.com/ThatsVie/atlas-web-development/assets/143755961/2f826243-c955-4548-9af0-30b913f54d94)


Create a new `<section>` element within the `<main>` element to contain all video-related content.

Include a `<h1>` heading at the start of the section to serve as the title of the video list, "Most Popular Tutorials."

For each video, create an `<div>` element that encapsulates all the details of the video.

An `<img>` tag for the video's thumbnail, followed by a `<h2>` for the video's title.

Add a `<p>` tag for a description of the video content.

Below the video description provide author details:

Include an image of the author using an `<img>` tag.

Use a `<h3>` tag for the author's name.

Create a rating display using a series of `<img>` tags, each representing a star.

Each star image has an appropriate alt attribute for accessibility, "1 star", "2 stars", etc.

Include additional text `<p>`

### Task 5
Create a section showing membership options available at Smile School.

![1ddf18bc6d89725de2fde4881e8990fae6d89628](https://github.com/ThatsVie/atlas-web-development/assets/143755961/5896963c-bf54-4102-8663-09ddf818fd38)


After the videos list section in the `<main>` element, add a new `<section>` for memberships.

Include a `<h1>` heading at the start of this section to serve as the title, "Free Membership."

Within this section, create a `<div>` to serve as a container for individual membership blocks.

For each membership type, set up a `<div>` 

Add an `<img>` tag 

Use a `<h2> `for the title of the membership package.

Include a `<p>` tag for a description of what the membership offers.

Place a `<button>` for registering

### Task 6
Add a FAQ section towards the end of the webpage, just before the footer.  This section will be structured in a two-row format with each row containing two questions.

![e4b2806abe9edc126fa0d4155aaf5d7e7da479e4](https://github.com/ThatsVie/atlas-web-development/assets/143755961/9aef84ba-e4aa-4199-9773-30454d6c737d)


Add new `<section>` element within the `<main>` element of the webpage.

Include a `<h1>` tag at the beginning of this section to serve as the main heading, labeled "F.A.Q."

Add a container `<div>` within the section to hold all FAQ items.

Use two `<div>` elements with a class of "row" inside the container to represent each row of FAQs.

Within each row, place two `<div>` elements with a class of "item", each containing:

A `<h2>` for the question.

A `<p>` for the answer.

Note: CSS styling will be applied in the future to achieve the "row" layout visually. This task focuses on having the HTML structure in place for such styling.

### Task 7
Implement a footer for the webpage.

![7224527ac842981b3b387cd9d713b4a1b912a487](https://github.com/ThatsVie/atlas-web-development/assets/143755961/7d843275-8580-47ca-8cb7-32726b4924b8)

Place the `<footer>` element directly after the `<main>` tag to ensure it is at the bottom of the webpage.

Use a nested `<div>` structure within the footer to organize the content.

The first `<div>` acts as a container for all footer content, facilitating future centering with CSS.

Inside the container, include:

An image `<img>`

A block for social media icons, each wrapped in <a> tags for navigation.

A simple text element for copyright information. `<p>`

