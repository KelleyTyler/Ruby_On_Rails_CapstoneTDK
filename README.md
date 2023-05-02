# Capstone

### Objectives

The associate will experience working in a large team environment and practicing Agile methodologies while building a blogging application. The following subjects are of primary importance

- Implementing Scrum practices

- Continuous Integration

- Following good Github branching strategies

- Documenting work progress using appropriate software

### Environment

- Backend will be deployed on an EC2 using Ruby on Rails

- Data will be persisted in a Postgres RDS database and managed by Active Record

- Front end will be hosted in an S3 bucket using React

### Rubric
While this project will not be graded like previous ones, your project showcase will be open to Revature at large: it is not uncommon for trainers to have their cohorts sit in a showcase, so there is a chance you will be presenting your project to your peers in other trainings, not to mention the internal Revature staff that come to watch. We have also had clients send representatives to watch the showcase to see what you all have accomplished, so a high level of excellence in coding practices, organization, and presentation are expected of you. In order to assist with this goal, a rubric that combines the previous project requirements has been provided to remind you of the various practices, requirements, and expectations that will help you to present a well crafted application in your project showcase. Use this rubric as a guide for determining work that needs to be done and for determining what should be focused on while working on your application.

| Points               | 1                    | 1                             | 1                | 1       | 1        |
| -------------------- | -------------------- | ----------------------------- | ---------------- | ------- | -------- |
| SOLID/OOD         | Multiple classes               | Separation of concerns  | Defined class domains                        | Abstraction        | Dependency Injection   |
| Structure         | Package separation             | Dependency management   |                                              |                    |                        |
| Observability     | Use logging package            | Logger configuration    | Use appropriate logging levels               |                    |                        |
| DBMS              | ERD                            | Schema creation         | Relationship management                      | DAO separation     | Transaction management |
| API Design        | HTTP request/response handling | Resource addressability | Use appropriate data format and status codes | Session management | API Documentation      |
| Distribute applications | Client-side application | Server-side application | Client/Server communication |                           |          |
| REST                    | Resource addresability  | Dynamic Paths           | Caching                     | Defined uniform interface |          |
| CI/CD pipeline               | Repository integration        | Automated testing | Artifact archiving | Deployment |     |
| Testing              | 10%-24% coverage     | 25% or greater coverage       | Resource Mocking |         |          |
| Clientside Rendering | Interactive Web pages| React integrated in web pages |                  |         |          |

# Revature-Blogger

### Description

Revature Blogger is a site where individuals can create accounts and share their blogs with the public at large. This is the first Spring of building the application, so MVP requirements are focused on getting the site up and running, with a few stretch goals provided should time permit.

### User-Stories

| As an user I can….          |
| :-------------------------- |
| create an account           |
| securely access my account  |
| create a blog               |
| edit a blog                 |
| delete a blog               |
| view my blogs               |
| view others' blogs          |
| filter the blogs I see      |

### Stretch-Goals
| As an user I can….          |
| :-------------------------- |
| react to others' blogs      |
| view statistics about my blogs |
| choose between light and dark mode when reading blogs |