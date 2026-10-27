# Assignment 1: What Happens Between Typing a URL and Seeing the Page?

## Introduction

When we type a URL (Uniform Resource Locator) into a web browser and press Enter, several steps take place before the webpage appears on the screen.

## Steps Involved

### 1. URL Entered
The user types a website URL, such as `https://example.com`, into the browser and presses Enter.

### 2. Browser Checks Cache
The browser checks its cache to see whether it already has some of the required resources stored locally.

### 3. DNS Lookup
The browser uses the Domain Name System (DNS) to translate the domain name into an IP address.

### 4. Connection Establishment
The browser establishes a connection with the web server. For HTTPS websites, it typically uses TCP with TLS or QUIC with TLS, depending on the protocol.

### 5. HTTP Request
The browser sends an HTTP request to the server, such as `GET /index.html`, to request the webpage.

### 6. Server Response
The server processes the request and sends an HTTP response containing a status code, headers, and the requested content. For example, `200 OK` indicates a successful request.

### 7. HTML Parsing
The browser receives the HTML document and parses it to create the Document Object Model (DOM).

### 8. CSS and JavaScript Loading
The browser discovers and downloads additional resources, such as CSS stylesheets, JavaScript files, images, and fonts.

### 9. Render Tree Creation
The browser builds the CSS Object Model (CSSOM) from CSS and combines it with the DOM to create the render tree.

### 10. Layout and Painting
The browser calculates the size and position of elements on the page and paints them onto the screen.

### 11. JavaScript Execution
The browser executes JavaScript, which can make the webpage interactive or update its content dynamically.

## Conclusion

When we enter a URL and press Enter, the browser performs several steps, including DNS lookup, connection establishment, HTTP communication, HTML parsing, styling, layout, and painting. These processes work together to display the webpage to the user.