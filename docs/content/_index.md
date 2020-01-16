---
title: Documentation
---

[![Build Status](https://cloud.drone.io/api/badges/xoxys/ansible-doctor/status.svg)](https://cloud.drone.io/xoxys/ansible-doctor)
[![](https://img.shields.io/pypi/pyversions/ansible-doctor.svg)](https://pypi.org/project/ansible-doctor/)
[![](https://img.shields.io/pypi/status/ansible-doctor.svg)](https://pypi.org/project/ansible-doctor/)
[![](https://img.shields.io/pypi/v/ansible-doctor.svg)](https://pypi.org/project/ansible-doctor/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

This project is based on the idea (and at some parts on the code) of [ansible-autodoc](https://github.com/AndresBott/ansible-autodoc) by Andres Bott so credits goes to him for his work.

*ansible-doctor* is a simple annotation like documentation generator based on Jinja2 templates. While *ansible-doctor* comes with a default template called `readme`, it is also possible to write your own templates. This gives you the ability to customize the output and render the data to every format you like (e.g. html or xml).

*ansible-doctor* is designed to work within your CI pipeline to complete your testing and deployment workflow. Releases are available as Python Packages at [GitHub](https://github.com/xoxys/ansible-doctor/releases) or [PyPI](https://pypi.org/project/ansible-doctor/) and as Docker Image at [DockerHub](https://hub.docker.com/r/xoxys/ansible-doctor).

You can find the full documentation at [ansible-doctor.geekdocs.de](https://ansible-doctor.geekdocs.de).