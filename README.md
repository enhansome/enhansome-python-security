<br/>
<div align="center">

A curated list of awesome Python security related resources.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

*List inspired by the [awesome](https://github.com/sindresorhus/awesome) ⭐ 495,126 | 🐛 100 | 📅 2026-06-30 list thing.*

Supported by: [GuardRails.io](https://www.guardrails.io)

</div>
<br/>

# Contents

* [Tools](#tools)
* [Educational](#educational)
* [Companies](#companies)
* [Other](#other)
* [Contributing](#contributing)

# Tools

## Web Framework Hardening

* [Flask-HTTPAuth](https://github.com/miguelgrinberg/flask-httpauth/) ⭐ 1,288 | 🐛 10 | 🌐 Python | 📅 2026-05-14 - Simple extension that provides Basic, Digest and Token HTTP authentication for Flask routes.
* [Secure.py](https://github.com/cakinney/secure.py) ⭐ 1,049 | 🐛 9 | 🌐 Python | 📅 2026-07-23 - secure.py 🔒 is a lightweight package that adds optional security headers and cookie attributes for Python web frameworks.
* [Flask Talisman](https://github.com/GoogleCloudPlatform/flask-talisman) ⚠️ Archived - Talisman is a small Flask extension that handles setting HTTP headers that can help protect against a few common web application security issues.
* [Django Session CSRF](https://github.com/mozilla/django-session-csrf) ⭐ 111 | 🐛 14 | 🌐 Python | 📅 2019-03-28 - CSRF protection for Django without cookies.
* [Django deployment checklist](https://docs.djangoproject.com/en/dev/howto/deployment/checklist/) - Web framework Django has built-in feature to check for security configurations: run this command `manage.py check --deploy`. It's really helpful as it already included in the framework.

## Multi tools

* [Hubble](https://github.com/hubblestack/hubble) ⭐ 386 | 🐛 3 | 🌐 Python | 📅 2023-07-07 - Hubble is a modular, open-source security compliance framework.
* [hawkeye](https://github.com/hawkeyesec/scanner-cli) ⚠️ Archived - Multi purpose security/vulnerability/risk scanning tool supporting Ruby, Node.js, Python, PHP and Java.
* [Salus](https://github.com/coinbase/salus) ⭐ 31 | 🐛 42 | 🌐 HTML | 📅 2025-06-12 - Multi purpose security scanning tool supporting Ruby, Node, Python and Go.
* [GuardRails](https://github.com/apps/guardrails) - A GitHub App that gives you instant security feedback in your Pull Requests.

## Static Code Analysis

* [Bandit](https://github.com/PyCQA/bandit) ⭐ 8,208 | 🐛 258 | 🌐 Python | 📅 2026-08-04 - Bandit is a tool designed to find common security issues in Python code.
* [Pyt](https://github.com/python-security/pyt) ⭐ 2,201 | 🐛 28 | 🌐 Python | 📅 2020-12-25 - A Static Analysis Tool for Detecting Security Vulnerabilities in Python Web Applications.
* [Detect Secrets](https://libraries.io/pypi/detect-secrets) - An enterprise friendly way of detecting and preventing secrets in code.

## Vulnerabilities and Security Advisories

* [Safety](https://github.com/pyupio/safety) ⭐ 1,995 | 🐛 88 | 🌐 Python | 📅 2026-07-21 - Safety checks your installed dependencies for known security vulnerabilities.
* [snyk Vulnerability DB](https://snyk.io/vuln?type=pip) - Commercial but free listing of known vulnerabilities in libraries.
* [Common Vulnerabilities and Exposures](https://www.cvedetails.com/vulnerability-list/vendor_id-10210/product_id-18230/Python-Python.html) - Vulnerabilities that were assigned a CVE. Covers the language and packages.
* [National Vulnerability Database](https://nvd.nist.gov/vuln/search/results?form_type=Basic\&results_type=overview\&query=python\&search_type=all) - Python known vulnerabilities in the National Vulnerability Database.

## Penetration Testing

* [sqlmap](https://github.com/sqlmapproject/sqlmap) ⭐ 38,170 | 🐛 32 | 🌐 Python | 📅 2026-08-11 - Automatic SQL injection and database takeover tool
* [EvilTwinFramework](https://github.com/Esser420/EvilTwinFramework) ⭐ 357 | 🐛 8 | 🌐 Python | 📅 2024-08-01 - A framework for pentesters that facilitates evil twin attacks as well as exploiting other wifi vulnerabilities.

## Cryptography

* [Passlib](https://bitbucket.org/ecollins/passlib) - Secure password storage/hashing library, very high level.
* [PyNacl](https://github.com/pyca/pynacl) ⭐ 1,204 | 🐛 56 | 🌐 C | 📅 2026-07-30 - Python binding to the Networking and Cryptography (NaCl) library.

## Application Templates

* [wemake-django-template](https://github.com/wemake-services/wemake-django-template) ⭐ 2,267 | 🐛 22 | 🌐 Python | 📅 2026-08-10 - Bleeding edge `django` template focused on code quality and security.

# Awesome Educational with stars

## Hacking Playground

* [DSVW](https://github.com/stamparm/DSVW) ⭐ 880 | 🐛 1 | 🌐 Python | 📅 2026-08-11 - Damn Small Vulnerable Web (DSVW) is a deliberately vulnerable web application written in under 100 lines of code, created for educational purposes.
* [django.nV](https://github.com/nVisium/django.nV) ⚠️ Archived - django.nV is a purposefully vulnerable Django application provided by nVisium.
* [DVPWA](https://github.com/anxolerd/dvpwa) ⭐ 191 | 🐛 12 | 🌐 Python | 📅 2024-05-21 - Damn Vulnerable Python Web Application was inspired by famous dvwa project and bobby-tables xkcd comics.
* [Let's be bad Guys](https://github.com/mpirnat/lets-be-bad-guys) ⭐ 189 | 🐛 1 | 🌐 HTML | 📅 2024-07-18 - Shiny, Let's Be Bad Guys: Exploiting and Mitigating the Top 10 Web App Vulnerabilities.

## Books

* [Full Stack Python Security](https://www.manning.com/books/full-stack-python-security) - A comprehensive look at cybersecurity for Python developers

## Articles, Guides & Talks

* [cryptography](https://cryptography.io/en/latest/) - A package designed to expose cryptographic primitives and recipes to Python developers.
* [10 Common Security Gotchas in Python](https://hackernoon.com/10-common-security-gotchas-in-python-and-how-to-avoid-them-e19fbe265e03) - 10 common security gotchas in Python and how to avoid them.
* [OWASP Python Security](http://www.pythonsecurity.org/) - Aims at creating a hardened version of python that makes it easier for developers to write applications more resilient to attacks and manipulations.
* [Django Security](https://docs.djangoproject.com/en/2.1/topics/security/) - Overview of Django’s security features includes advice on securing a Django-powered site.

# Companies

* [GuardRails](https://www.guardrails.io) - A GitHub App that gives you instant security feedback in your Pull Requests.
* [Snyk](https://snyk.io) - A developer-first solution that automates finding & fixing known vulnerabilities in your dependencies.

# Other

## Reporting Bugs

* [Python Security Reporting](https://www.python.org/news/security/)

# Contributing

Found an awesome project, package, article, or another type of resources related to Python Security? Send me a pull request!
Just follow the [guidelines](/CONTRIBUTING.md). Thank you!

***

say *hi* on [Twitter](https://twitter.com/s_streichsbier)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
