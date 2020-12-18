# Python CI

In this text, I discuss CI in Python application development.

Python lint tools can be categorised to logical, stylistic and analytical linters. Some popular tools include Pylint (logical and stylistic) and Radon (analytical).

For testing, Python offers unittest in its standard library. There are also more versatile tools, such as nose2 and pytest.

Python is an interpreted language and does not need building to be executed. However, there are several build tools available for different purposes. For example, PyBuilder and doit offer tools for various automation purposes.

There are several popular alternatives to Jenkins and GitHub Actions. For example, CircleCI, GitLab CI/CD and Bamboo offer both self-hosted and cloud-based services. A purely self-hosted alternative is offered by TeamCity, whereas Travis CI is another cloud-based solution.

For this project, I think a cloud-based CI environment would be better. Setting up a self-hosted environment requires additional work that may not be possible due to the approaching release time and relatively small team. However, the nature of the project could affect the situation. For example, if the project requires a very custom CI pipeline or advanced resources, or if there is an existing CI environment in use in the company, a self-hosted solution could be more suitable.