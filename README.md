## Introduction

Hi, my name is Ricky Garcia. I am new to coding and am currently attending the CNM Ingenuity Deep Dive Java + Android Bootcamp. Looking to gain the knowledge and experience needed to start my career as a junior software developer. I am looking to apply my problem solving, critical thinking and team-work skills to find a good job or internship to improve my coding skills.

## Current projects

* [Wake the F up!!: Personal Android Capstone project](https://rickyg08.github.io/wake-up/) A productivity app to help improve the user be productive after a night with very little sleep.

  * [Repository](https://github.com/rickyG08/wake-up)

* [AlbuQuirky: Team Capstone project](https://github.com/albuquirky)

## Recently updated repositories

{% assign public_repositories = site.github.public_repositories | where: 'fork', false | sort: 'updated_at' | reverse %}
{% for repo in public_repositories limit: 10 %}
* [{{ repo.name }}]({{ repo.html_url }})
{% endfor %}

## Links

* [LinkedIn](https://www.linkedin.com/in/ricky-garcia-7443471b5/)
