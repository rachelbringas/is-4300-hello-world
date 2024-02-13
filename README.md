# Hello World Interface

This is a simple "Hello, World!" interface project created as a baseline for a development assignment.

## Table of Contents

- [Introduction](#introduction)
- [Setup and Run](#setup-and-run)
- [Design Choices](#design-choices)
- [Resources](#resources)

## Introduction

The project is a basic interface that displays the text "Hello, World!" This serves as a starting point for further development and ensures a working environment with the chosen technology.

## Setup and Run

1. **Clone the Repository:**
   - Clone this repository to your local machine using the following command:
     ```bash
     git clone https://github.com/rachelbringas/is-4300-hello-world.git
     ```

2. **Navigate to the Project Directory:**
   - Move into the project directory:
     ```bash
     cd hello-world-interface
     ```

3. **Open in a Web Browser:**
   - If you have Python installed, you can use a simple HTTP server:
     - For Python 2:
       ```bash
       python -m SimpleHTTPServer
       ```
     - For Python 3:
       ```bash
       python -m http.server
       ```
   - Or, if you have Node.js installed, you can use the `http-server` package:
     ```bash
     npm install -g http-server
     http-server
     ```
   - Open your browser and go to [http://localhost:8000](http://localhost:8000) (or another port if specified).

4. **Access the Interface:**
   - Open the `index.html` file in your browser.

## Design Choices

- **HTML and CSS:**
  - The interface is built using HTML for structure and CSS for basic styling.
- **Clean Layout:**
  - The layout is kept simple with a centered "Hello, World!" message.

### Explanation:

The design choices were kept minimal for the purpose of the assignment. The use of HTML and CSS ensures a straightforward structure and presentation. The clean layout with centered text provides a basic, visually appealing display.

## Resources

- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Python SimpleHTTPServer Documentation](https://docs.python.org/2/library/simplehttpserver.html)
- [Node.js http-server](https://www.npmjs.com/package/http-server)
- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
- [CSS-Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

