Architecture

In this full stack project, frontend development was handled through a combination of traditional server-rendered HTML using Express, 
client-side JavaScript, and a single-page application (SPA) framework—Angular. Express HTML allowed us to serve static and dynamic content quickly with embedded JavaScript templates. 
It was useful for rendering simpler pages like the login screen or basic error views. JavaScript was then used to add interactivity to these pages—handling form validation, DOM manipulation, 
and asynchronous API requests. However, the SPA architecture took the front end a step further. By using Angular, we developed a more responsive and modular UI where routing, state management, 
and dynamic data rendering happened entirely in the browser without reloading the page. This resulted in faster user interactions and a more fluid experience.

On the backend, MongoDB was used because it fits naturally with the JavaScript ecosystem (via BSON/JSON), 
offers a schema-less design, and is excellent for handling unstructured or semi-structured data like trip listings. 
Its document-based model allowed us to iterate quickly during development and easily map frontend data structures to the backend, 
which is especially beneficial in agile, rapidly evolving applications.

Functionality

JSON (JavaScript Object Notation) is a lightweight data-interchange format, whereas JavaScript is a full-fledged programming language. 
JSON is used to represent and transfer structured data, often between frontend and backend systems. In this project, JSON served as the bridge: 
Angular sent and received JSON data from Express-based APIs, allowing both sides of the stack to communicate effectively in a format both understand natively.

During development, I refactored the trip listing component and admin form logic. Originally, repetitive HTML and duplicated validation code existed across multiple form views. 
By creating reusable UI components—such as a form input wrapper and a trip card component—I improved maintainability and consistency across the app. 
This modular approach meant future enhancements or styling changes could be made in one place and instantly reflected across the app, saving time and reducing the chance of introducing bugs.

Testing

API testing in this project involved validating endpoints using tools like Postman and writing unit/integration tests with frameworks like Mocha and Chai. 
Testing included CRUD operations—GET for fetching trips, POST for creating, PUT for updating, and DELETE for removing. With security added through JWT (JSON Web Tokens), 
it became essential to test both authenticated and unauthenticated access paths to ensure proper authorization middleware was working.

Each endpoint had to account for different HTTP methods and respond with appropriate status codes and messages. Security added complexity, as token validation had to be simulated or mocked in tests, 
and protected routes required additional headers or credentials. Thorough testing ensured both functionality and protection from unauthorized access, helping maintain data integrity and user trust.

Reflection

This course significantly helped me move closer to my professional goals of becoming a full stack developer. I gained practical, 
hands-on experience working with technologies widely used in the industry—Node.js, Express, Angular, and MongoDB. I developed skills in API design, 
data modeling, and frontend-backend integration using REST principles. Moreover, I learned to build secure applications, manage state in SPAs, and implement authentication.

What makes me more marketable now is the ability to build a complete, working application from scratch, follow modern design patterns, 
and troubleshoot across the full tech stack. The ability to reason about architectural decisions and build scalable, 
maintainable systems has enhanced my confidence as a developer and strengthened my portfolio for future job opportunities.
