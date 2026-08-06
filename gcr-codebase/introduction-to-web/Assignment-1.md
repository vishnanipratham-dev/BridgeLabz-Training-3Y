# Assignment 1 - Introduction to Web Development

**Name:** Pratham Vishnani  
**Class:** 3rd Year B.Tech CSE (Cyber Security)  
**Subject:** Introduction to Web Development  

---

# 1. Explain the difference between frontend, backend, and full-stack development with suitable real-world examples.

## Frontend Development
Frontend development is the part of web development that users interact with directly. It focuses on designing the user interface and improving user experience using HTML, CSS, and JavaScript.

**Technologies:**
- HTML
- CSS
- JavaScript
- React
- Angular
- Vue.js

**Example:**
On Amazon, the product images, buttons, menus, and search bar are all part of the frontend.

---

## Backend Development

Backend development manages the server, business logic, authentication, and database operations. It processes user requests and sends the required data to the frontend.

**Technologies:**
- Node.js
- Java
- Python
- PHP
- Express.js
- Spring Boot

**Example:**
When a user logs into Amazon, the backend verifies the username and password using the database.

---

## Full Stack Development

A Full Stack Developer works on both frontend and backend.

They can:
- Design webpages
- Develop APIs
- Connect databases
- Deploy applications

**Example:**
A Full Stack Developer can build an entire e-commerce website from scratch.

---

# 2. Create a simple diagram showing how the client-server model works in web architecture.

```
+------------+           HTTP Request            +------------+
|   Client   | -------------------------------> |   Server   |
| (Browser)  |                                  |            |
|            | <------------------------------- |            |
+------------+           HTTP Response           +------------+
```

**Explanation:**

1. User enters a website URL.
2. Browser sends an HTTP request.
3. Server processes the request.
4. Server returns an HTTP response.
5. Browser displays the webpage.

---

# 3. Describe how a browser requests and displays a web page from a web server.

The process consists of the following steps:

1. The user enters a website URL.
2. DNS converts the domain name into an IP address.
3. The browser sends an HTTP request to the web server.
4. The server processes the request.
5. The server returns HTML, CSS, JavaScript, and other resources.
6. The browser downloads these files.
7. The browser renders the webpage and displays it to the user.

---

# 4. Identify and list the tools required to set up a web development environment. Explain the purpose of each.

| Tool | Purpose |
|------|----------|
| Visual Studio Code | Source code editor |
| Google Chrome | Test and debug web pages |
| Git | Version control |
| GitHub | Store and manage code online |
| Node.js | JavaScript runtime environment |
| Live Server Extension | Runs HTML pages locally with auto refresh |
| Terminal / Command Prompt | Execute development commands |

---

# 5. Explain what a web server is and give examples of commonly used servers.

A web server is software or hardware that receives HTTP requests from clients and sends the requested web pages or data back to them.

### Examples

- Apache HTTP Server
- Nginx
- Microsoft IIS
- LiteSpeed
- Node.js HTTP Server

**Example:**

When a user visits www.google.com, Google's web server processes the request and sends the webpage to the browser.

---

# 6. Define the roles of a frontend developer, backend developer, and database administrator in a project.

## Frontend Developer

Responsibilities:
- Design web pages
- Improve user experience
- Create responsive layouts
- Develop interfaces using HTML, CSS, and JavaScript

---

## Backend Developer

Responsibilities:
- Develop APIs
- Implement business logic
- Handle authentication
- Connect with databases
- Process client requests

---

## Database Administrator (DBA)

Responsibilities:
- Design databases
- Store and organize data
- Backup and recover data
- Improve database performance
- Ensure data security

---

# 7. Install VS Code and configure it for HTML, CSS, and JavaScript development. Take a screenshot of the setup.

## Installed Software

- Visual Studio Code
- Google Chrome
- Git
- Node.js

## Installed Extensions

- Live Server
- Prettier
- HTML CSS Support
- Auto Rename Tag
- Auto Close Tag
- JavaScript (ES6) Snippets

**Screenshot:** *(Insert your VS Code setup screenshot here.)*

---

# 8. Explain the difference between static and dynamic websites. Provide an example of each.

| Static Website | Dynamic Website |
|---------------|-----------------|
| Fixed content | Content changes dynamically |
| No database | Uses database |
| Faster loading | Slightly slower |
| Easier to host | Requires backend |
| Built using HTML/CSS | Uses HTML, CSS, JavaScript, Backend |

### Examples

**Static Website**
- Portfolio Website
- Resume Website

**Dynamic Website**
- Facebook
- Amazon
- Instagram
- YouTube

---

# 9. Research and list five web browsers. Explain how rendering engines differ between them.

| Browser | Rendering Engine |
|----------|------------------|
| Google Chrome | Blink |
| Microsoft Edge | Blink |
| Mozilla Firefox | Gecko |
| Apple Safari | WebKit |
| Opera | Blink |

### Rendering Engines

- **Blink:** Fast and widely used in Chrome, Edge, and Opera.
- **Gecko:** Used by Firefox, focuses on web standards and privacy.
- **WebKit:** Used by Safari and optimized for Apple devices.

Rendering engines read HTML, CSS, and JavaScript, then display the webpage on the screen.

---

# 10. Draw a labeled diagram showing the basic web architecture flow — client, server, database, and APIs.

```
                   User
                    |
                    v
            +----------------+
            | Web Browser    |
            | (Client)       |
            +----------------+
                    |
              HTTP Request
                    |
                    v
            +----------------+
            | Web Server     |
            +----------------+
                    |
            API Calls / Logic
                    |
          --------------------
          |                  |
          v                  v
   +--------------+   +--------------+
   | Database     |   | External API |
   +--------------+   +--------------+
          |
          |
          v
    HTTP Response
          |
          v
+---------------------+
| Browser Displays    |
| Web Page            |
+---------------------+
```

**Explanation**

1. The user sends a request through a web browser.
2. The request reaches the web server.
3. The server processes the request.
4. The server retrieves data from the database or external APIs.
5. The server sends the response back to the browser.
6. The browser renders and displays the webpage.

---

# Conclusion

Web development involves multiple components working together, including the frontend, backend, web server, APIs, and databases. Understanding these concepts provides a strong foundation for building modern web applications.