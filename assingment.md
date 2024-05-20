# Assignment-2


# Differences Between Document and Window Objects in JavaScript


In JavaScript, two of the most fundamental objects are the document and window objects. They form the basis for interacting with the web page and the browser. Understanding the differences between these objects is essential for effective web development.

# 1. The Window Object
The window object represents the browser's window or the frame in which the web page is displayed. It is the global object in a web browser, meaning that all global variables and functions are members of the window object.

# Key Features of the Window Object:

# Global Scope: 
All global variables and functions are properties and methods of the window object. For example, window.alert() is the same as calling alert().

# Browser Window Management: 
It provides methods to control the browser window, such as opening and closing new windows (window.open(), window.close()), resizing the window (window.resizeTo()), and scrolling (window.scrollTo()).

# Timers:
It includes methods for executing code at specific intervals, such as setTimeout() and setInterval().

# Event Handling:
It handles global events like onload, onresize, and onscroll.



# 2. The Document Object
The document object represents the HTML document loaded in the browser window. It is a property of the window object (window.document), and it provides access to the content of the web page.

# Key Features of the Document Object:

# DOM Manipulation: 
It provides methods to create, access, and manipulate HTML elements. For example, document.getElementById(), document.createElement(), and document.querySelector().

# Content Access:
It allows you to read and modify the content of the HTML document. This includes getting and setting element attributes, inner text, and HTML content.

# Event Handling:
It provides methods to handle events on specific elements, such as addEventListener().

# Document Information:
It provides information about the document, such as document.title and document.URL.


# Key Differences between window and document :

# Scope: 
window is the global object encompassing everything, while document is a property of window focused on the content of the web page.

# Functionality:
window provides methods to interact with the browser window, manage global events, and handle timing events. document focuses on DOM manipulation, accessing and modifying web page content, and handling element-specific events.

# Usage:
Use window for tasks related to the browser environment (e.g., controlling the browser window, setting timers). Use document for tasks related to the HTML content (e.g., changing element content, creating new elements).



# Conclusion
Both the window and document objects are essential for web development, each serving distinct purposes. The window object manages the browser environment, while the document object provides control over the web page content. Understanding their roles and differences enables developers to effectively interact with and manipulate web pages, leading to more dynamic and responsive web applications.
