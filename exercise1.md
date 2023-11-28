### Exercise 1

Suppose we are in a hypothetical situation where we have an application being actively developed by a team of 6 people using Python as the primary programming language.

In order to integrate works of the team, some automated test needs to be performed to avoid introducing bugs and to make sure that everything still works after integration in an efficient manner. Common steps of a CI setup include linting, testing and building before merging into the main code of the project.

For linting, a widely used tool for code quality check in Python is Pylint. It offers extensive customization options and comprehensive reports. A lighter popular alternative is flake8. To check if the code works as expected, pytest can be used for unit tests, integration tests and end to end tests.
Besides Jenkins and GitHub Actions, there are many alternatives to set up a CI: to name some we have: Travis CI, GitLab CI/CD, CircleCI, Atlassian Bamboo, Team City, Azure Pipelines, and a lot more.

Criteria to consider for determining if a setup is better self-hosted or cloud-based are the size of the project, the number of people involved in the project and the complexity of the functionalities of the application. For example, if tests require GPUs to run or if the application is huge and there are a lot of engineers involved in the development, a self-hosted and highly customizable solution would be more appropriate. Alternatively, a simpler project involving, as in our example only 6 people, a cloud-based environment would be sufficient. Configuration is simpler and the solution cheaper.