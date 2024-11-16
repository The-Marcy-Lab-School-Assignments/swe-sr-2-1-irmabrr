# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/fullstack-curriculum/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

Do some research on semantic and non-semantic elements and share your findings. Your response should include:
* Examples of semantic and non-semantic tags
* The differences between semantic and non-semantic tags
* The benefits of using semantic tags (when possible)

### Response 1
Semantic elements describe their meanings in the brower and in the developer. An example is tags like <table>, <main> and <summary>.
Some of the benefits are that if we need to find certain tags quickly we will simply have to look for what they hold and not go through every tag trying to figure it out. 
Non-semantic elements are tags that tell us nothing about the content inside, examples are <div> and <span>. 

## Prompt 2

Do some research on accessibility. What are some ways to make your website more accessible? Explain why it is important for developers to create websites that meet accessibility standards.

### Response 2

Some ways to make our website more accessible:
- detailed navigational elements 
- alt text for images for screen readers
- tabbing through website content, using it without a mouse 
- creating a website that gives enough time to navigate websites and complete tasks 
- captions!!!

It is important for developers to create websites that meet accessibility standards because it creates a wider audience and promotes inclusivity for folks with disabilities. 


## Prompt 3

It is possible to add "inline" CSS styles to our html elements using the `style` attribute like so:

```html```
<p style="color: red;" >hello world</p>
```

While this is possible, it is a best practice to instead write styles in a separate CSS file. Provide at least one argument for why it _might_ be considered useful to write inline styles, and then provide a more compelling argument for writing styles in a separate CSS file.

### Response 3
A reason it is good to write inline styles is when supporting older websites, HTML e-mails and dynamic websites that use JavaScript.
But it is better to write styles in a seperate CSS file because "HTML is meant for conveying structured information. CSS is built to style that structured information." 
We don't want to be writing double code, it may cross each other so it is always better to be careful. It also makes our code easier to read and more organized. If we do it inline we will have to rewrite our styles every time instead of just having them accessible to use. 


## Prompt 4

Imagine you are teaching a brand new programmer a brief lesson about the `class` and `id` attributes in HTML as well as how to use them to style elements using CSS. Your lesson should have the following components:

* An explanation of the concept of "classes" and "ids" with an analogy.
* An example of the usage using an HTML code block and a CSS code block.
* An explanation of the syntax using the terms: **attribute**, **selector** 

### Response 4
Classes are able to be applied to multiple elements, often used for styling group elements. A way I think about it is like when people sign up for banks, some people have access to multiple classes or just one class(chase, wells fargo, citi bank).

ex:
```html```
<p class="new"> our attribute is whatever</p>
<p class="new">is inside the </> <P>
<p class="new">like size, color, font and others!</p>
```

Ids are unique to one element and often used to identify specific page elements. I think of this as an actual bank account or credit card information, no one can have your bank details or card information *unless* it is you, and only YOU have access to the details held in there. 

ex:
```html```
<p id="only">Our ids are specific</P>
<p id="can-have">Unlike class we can't share</p>
<p id="one">Think about your own ID!</p>
```

## Prompt 5

The Document Object Model (DOM) API provides functions for manipulating HTML documents. It is possible to build an entire website using only JavaScript and the DOM API, however is that the best practice?

When building a website, how can I decide which content I should write using HTML/CSS and which content I should create using the JavaScript and the DOM API?

### Response 5
Creating a website only using JavaScript and the DOM is not the best practice because we want to have a difference in our pages, as we have read its important to have different files for our HTML, CSS, and JS just incase we have a small bug it will be easier to identify its location instead of having to search through our JS file to find the issue. 
You can decide which content you should write using HTML/CSS by knowing if its a style (CSS) or if it is going to be just basic structure of our website (HTML). If it's going to be about the way our website looks we will need to use CSS. If it will be about what information our website will hold we will need to use HTML. 
The content you should create using JavaScript and the DOM API has to do with the way we want our website to act. Do we want and how we want our users will interact with the website. 
