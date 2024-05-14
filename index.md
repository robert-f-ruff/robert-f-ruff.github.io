---
layout: default
---

# Introduction

The Rules Engine evaluates a series of rules against a set of data. Each rule has a set of criteria, that defines when a rule is applicable, and a series of actions, that define what the engine should do when the associated rule is applicable. The engine receives data via a REST API, evaluates the criteria against that data, and then executes the appropriate actions.

The goal of this project is to demonstrate my knowledge of modern programming languages and system design. Reading a book and completing an online certification gave me a good starting point on my reskilling journey, but creating a system from scratch has locked that knowledge in and exposed me to problems and issues that never came up while completing fill-in-the-blank assignments.

This site describes the engine: the [technologies](./technologies.html) used to construct it, how those technologies were brought together in the [system's design](./system_design.html), and how the various components and classes [interact with each other](./class_diagram).

Additionally, the following code coverage reports are available:
- [Frontend](./coverage/htmlcov/index.html)
- [Backend](./coverage/jacoco/index.html)

Finally, the backend [JavaDoc class documentation](./javadoc/index.html) is also available for reference.