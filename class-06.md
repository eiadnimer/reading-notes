# Problem Domain, Objects, and the DOM
- Objects group together a set of variables and functions to create a model of something you would recognize from the real world. In an object, variables and functions take on new names.
**N AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES & FUNCTIONS BECOME KNOWN AS METHODS**
- Each node is an object with methods and properties. Scripts access and update this DOM tree (not the source HTML file). Any changes made to the DOM tree are reflected in the browser.
- Text nodes: Once you have accessed an element node, you can then reach the text within that element. This is stored in its own text node.
**Updating the DOM tree involves two steps:**
1- Locate the node that represents the element you want to work with.
2- Use its text content, child elements, and attributes.
- Methods that find elements in the DOM tree are called DOM queries. When you need to work with an element more than once, you should use a variable to store the result of this query.
- **DOM** queries may return one element, or they may return a Nodelist, which is a collection of nodes.
- The terms elements and element nodes are used interchangeably but when people say the DOM is working with an element, it is actually working with a node that represents that element.
- **FASTEST ROUTE:** Finding the quickest way to access an element within your web page will make the page seem faster and/or more responsive.
- **getElementByld()** and querySel ector( ) can both search an entire document and return individual elements. Both use a similar syntax. documant.getElementByld()
- **getElementByld()** allows you to select a single element node by specifying the value of its id attribute.
- There are two ways to select an element from a Nodelist:
1- The item() method 
2- array syntax
- When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM.
- parentNode: This property finds the element node for the containing (or parent) element in the HTML.
- previousSibling nextSibling: These properties find the previous or next sibling of a node if there are siblings.
- firstChild lastChild: These properties find the first or last child of the current element.
- textContent To collect the text from the <li> elements in our example (and ignore any markup inside the element) you can use the textContent property on the containing <li> element. In this case, it would return the value: fresh figs.
- Using the innerHTML property, you can access and amend the contents of an element, including any child elements.
- innerHTML When getting HTML from an element, the innerHTML property will get the content of an element and return it as one long string, including any markup that the element contains.
- DOM manipulation offers another technique to add new content to a page (rather than innerHTML). It involves three steps:
1- CREATE THE ELEMEN
2- GIVE IT CONTENT
3- ADD IT TO THE DOM
- Modern browsers come with tools that help you inspect the page loaded in the browser and understand the structure of the DOM tree.
- The browser represents the page using a DOM tree.
- DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.
- You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.