## Introduction

I'm a quick learner that is very motivated to start a new career, currently attending the Deep Dive Coding Java + Android Bootcamp. My plan after graduation is to look for employment or contract work in Android app development.

## Current projects

* [Hello World: Java console application](https://github.com/rickyG08/deep-dive-hello-world-ij)

* [Hello World: Android app](https://github.com/rickyG08/android-hello-world)

## Recently updated repositories

{% assign public_repositories = site.github.public_repositories | where: 'fork', false | sort: 'updated_at' | reverse %}
{% for repo in public_repositories limit: 10 %}
* [{{ repo.name }}]({{ repo.html_url }})
{% endfor %}

## Links

* [LinkedIn](https://www.linkedin.com/in/ricky-garcia-7443471b5/)
