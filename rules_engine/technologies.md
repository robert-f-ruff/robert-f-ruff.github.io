---
layout: default
---

# Technologies

## Programming Languages
- [Java](https://www.oracle.com/java/): powers the backend engine, evaluating the criteria set against received data and executing actions when a rule is deemed applicable
- [Python](https://www.python.org): serves the frontend interface to the user who manages the rule set
- [JavaScript](https://ecma-international.org/publications-and-standards/standards/ecma-262/): creates a dynamic frontend experience, updating portions of the web page in response to user actions
- Shell Scripting: automate tedious developer tasks and ensure Docker containers run securely and consistently

## Environment
- [Docker](https://www.docker.com/): containers host the frontend, backend, and supporting services, while Docker Compose orchestrates the containers into a functioning system.
- [MySQL](https://dev.mysql.com/): database server that stores the ruleset, which is managed by the frontend and used by the backend.
- [nginx](https://nginx.org/en/): an HTTP proxy server delivering static content for the frontend and providing access to the frontend application container.
- [Gunicorn](https://docs.gunicorn.org/en/latest/index.html): a web server gateway interface (WSGI) providing communication between the nginx proxy server and the Django frontend application
- [GreenMail](https://greenmail-mail-test.github.io/greenmail/#): an email platform, providing a window to view the final outcome of the engine's evaluation when applicable.
- [WildFly](https://www.wildfly.org/): Java application server that runs the backend application

## Frameworks and Tools
- [Jakarta EE](https://jakarta.ee/): Java framework specifications for dependency injection, REST services, and email
- [Maven](https://maven.apache.org/): project management tool used to build the backend
- [JUnit 5](https://junit.org/junit5/): Java testing framework
- [Mockito](https://site.mockito.org/): mocking framework for Java unit tests
- [Testcontainers](https://testcontainers.com/): provides a MySQL instance for testing the frontend consistently and provides the environment for the backend integration tests
- [Django](https://www.djangoproject.com/): web framework powering the frontend, collecting input from the user and updating the database as needed
- [Selenium](https://www.selenium.dev/): automates frontend testing of the user interface via a web browser
- [Bootstrap](https://getbootstrap.com/): styles the frontend web pages via Cascading Style Sheets (CSS), ensuring a consistent layout and appearance regardless of the user's web browser
- [requests-mock](requests-mock): transport adapter used during frontend testing to mock the backend REST API

[back](./)
