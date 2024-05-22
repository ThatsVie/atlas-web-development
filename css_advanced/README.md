# CSS Advanced
![Static Badge](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)

The CSS Advanced project is an extension of the previous HTML Advanced project. In this project, we add CSS to style and slightly modify the HTML template previously built, aiming to replicate the design provided in [Figma](https://www.figma.com/file/XrEAsu1vQj5fhVaNG38d2W/Homepage?type=design&node-id=0-1&mode=design&t=odbpkpcMXB66kvTC-0).

## Learning Objectives

### What is CSS
CSS (Cascading Style Sheets) is a stylesheet language used to describe the presentation of a document written in HTML. CSS controls the layout, colors, fonts, and overall visual styling of web pages.

In this project, we used CSS to style the Smile School website. The styles.css file contains rules that define the appearance of elements such as headers, menus, sections, and buttons.

### How to Add Style to an Element

To add style to an element, you can create CSS rules in an external stylesheet, an internal `<style>` tag within the HTML file, or directly inline using the style attribute.

Example from the project:

![image](https://github.com/ThatsVie/atlas-web-development/assets/143755961/1bb50032-8724-4eca-9225-6f4c910f109e)


In the styles.css file, the styling for the header element is defined:

![image](https://github.com/ThatsVie/atlas-web-development/assets/143755961/508444fb-08b2-4eca-a92f-f2a9f8022964)


### What is a Class

A class is a reusable style definition in CSS that can be applied to multiple HTML elements. Classes are defined with a . (dot) prefix and can be assigned to elements using the class attribute.

Example from the project:

![image](https://github.com/ThatsVie/atlas-web-development/assets/143755961/0e05c01f-ce66-403f-bb29-6f85feff6199)


In the styles.css file, the styling for the getSchooled class is defined:

![image](https://github.com/ThatsVie/atlas-web-development/assets/143755961/23389650-9a9c-45a7-b45a-1d9cb96fc959)


### What is a Selector

A selector in CSS is a pattern used to select elements on a web page that you want to style. There are various types of selectors, including element selectors, class selectors, ID selectors, and attribute selectors.

Example from the project:

![image](https://github.com/ThatsVie/atlas-web-development/assets/143755961/4d606e3c-0067-4093-861e-21ae90af2990)

### How to Compute CSS Specificity Value
CSS specificity determines which CSS rule is applied when multiple rules match the same element. Specificity is calculated based on the number and types of selectors used in the rule.

Example from the project:

![image](https://github.com/ThatsVie/atlas-web-development/assets/143755961/27c2975e-2ca2-4f02-b893-597e134f8cca)

The ID selector (#logo) has a higher specificity than the class selector (.menu a), so it will take precedence if there is a conflict.

### What are Box Properties in CSS

Box properties in CSS define the layout and spacing of elements. These properties include margin, padding, border, and content.

Example from the project:

![image](https://github.com/ThatsVie/atlas-web-development/assets/143755961/1c33947a-aa09-4dbd-8332-33ffbdc730c2)

In this example, the `tutorialItem` class has box properties such as height, width, background, box-shadow, and border-radius to define its layout and appearance.

### How Does the Browser Load a Webpage

The browser loads a webpage by performing several steps:

Resolves the domain name to an IP address.

Sends an HTTP request to the server hosting the webpage.

Downloads and parses the HTML document.

Downloads linked resources such as CSS, JavaScript, and images.

Parses CSS and applies styles to the HTML elements.

Constructs the DOM (Document Object Model) and CSSOM (CSS Object Model), then renders the webpage visually.


In this project, when the Smile School webpage is loaded, the browser requests and parses the index.html file, followed by fetching and applying the styles defined in styles.css, and renders the structured content with applied styles.
