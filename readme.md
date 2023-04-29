## Introduction

We will assign seven issues to our teammates, set up a project board, write
the readme file, setup workflows to run C programs, get a status badge for our
project, write a github page for listing all the contributors and promote this
project in CSCI3251-2023 organization!

## Code

## Contributors

{% for student in site.stu %}
![{{ student.name }}]({{ student.image }})
- User: [@{{ student.user }}](https://github.com/{{ student.user }})
- Name: {{ student.name }}
- Content: {{ student.content }}
{% endfor %}
