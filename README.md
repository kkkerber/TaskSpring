This project is a simple Spring Boot web application.

When the application starts, Spring Boot launches an embedded web server and prepares the application context. After that, the server waits for HTTP requests from the browser.

The application uses Spring MVC. Incoming requests are handled by a controller class. The controller is responsible for receiving the request, processing input data, and returning a view name.

When a user opens the greeting page, the controller reads a request parameter called name. If the parameter is not provided, a default value is used. The controller then puts this value into the model so it can be used in the HTML page.

The HTML page is rendered using Thymeleaf. Thymeleaf takes the template file from the templates directory and replaces dynamic values with data from the model. As a result, the browser receives a ready HTML page with the greeting text.

Static files such as images are stored in the static directory. These files are served directly by Spring Boot without any controller logic. The HTML page can reference static resources like images using a relative path.

In the end, the user sees a rendered web page with dynamic text and a static image, generated on the server and delivered to the browser.

Screenshot of the project structure 
![telegram-cloud-photo-size-2-5422483128913170962-x](https://github.com/user-attachments/assets/671d8ab3-7388-4822-a716-7e5b95c7c201)


And localhost
![telegram-cloud-photo-size-2-5422483128913170960-x](https://github.com/user-attachments/assets/74609471-994d-4228-8357-29a79e825a14)
