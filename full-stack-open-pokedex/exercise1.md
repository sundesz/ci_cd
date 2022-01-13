# Python CI/CD

## Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by google.

<br>

- **Linting**

  <https://flake8.pycqa.org/en/latest/>

  flake8 is commonly used to check the code conforms to the standard Python coding style.

  <https://pypi.org/project/pylint/>

  Pylint is a Python static code analysis tool which looks for programming errors, helps enforcing a coding standard, sniffs for code smells and offers simple refactoring suggestions.

<br>

- **Testing**

  <https://docs.pytest.org/en/latest/>

  pytest makes it easy to write small tests, yet scales to support complex functional testing for applications and libraries.

<br>

- **Building**

  <https://www.heroku.com/>

  Heroku is a cloud platform that lets companies build, deliver, monitor and scale apps — we're the fastest way to go from idea to URL, bypassing all those infrastructure headaches

<br>
<br>
<br>
<br>

## What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask google!

<br>

- **GitLab**

  - GitLab CI/CD tool is a part of GitLab and a powerful alternative to Jenkins. It is an open-source web interface that can be used to apply all the continuous methods like integration, delivery, and deployment to your project without any third-party application. It provides a user-friendly interface along with distributed version control services.

<br>

- **Atlassian Bamboo**

  - It’s a useful tool for continuous integration, development, and deployment. It runs builds and tests and efficiently integrates with JIRA to update issues and commits and connect test results for an end to end visibility within the team. It supports multiple technologies like AWS, Amazon S3 buckets, Git, SVN, Mercurial, etc.

<br>

- **Circle CI**

  - CircleCI is a flexible tool with easy maintenance and can run in almost any environment. Every commit leads to automatic build execution. To add to it, if any new build is triggered, any queued or running build is automatically canceled.

<br>

- **TeamCity**

  - TeamCity is also known as the “Intelligent CI Server” because of its ease of use and integration. It offers different installation packages for different operating systems. It is a powerful tool developed from JetBrains, which allows building, and running tests even before changes are committed, hence keeping the code clean.

<br>

- **Travis CI**

  - Travis CI is a continuous integration and testing CI/CD tool. It is free of cost for open source projects and provides seamless integration with GitHub. It supports more than 20 languages, like Node.js, PHP, Python, etc. along with Docker.

<br>
<br>
<br>
<br>

## Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

<br>

### This depends upon the company situation, resources and project type. If its big project than its good to have a self-hosted setup. This required extra resources and space to setup the server and look after it.

### And for small projects its good to have a cloud-based environment. As this will save the resources and space.
