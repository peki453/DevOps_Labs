# Python & Docker best practices

### Python best practices

- using Flask for Python web development, since it is established Python framework for web development
- try to keep code simple to avoid errors but complex enough to solve given task
- code documentation (given application is simple, so comments are enough)

### Docker best practices

First of all, it is important to avoid unnecessary complications by following established approaches due to lack of Docker experience.

Best practices that I have found exploring about Docker:

- include a health check
- using default and latest Python image
- don't run containers as root
- don’t run environment as root
- scan images locally during development
- update images frequently
- don't put credentials and secrets in Dockerfile instructions
- use labels
