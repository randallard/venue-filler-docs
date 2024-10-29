---
layout: default
title: Welcome to Venue Filler Documentation
---

# Welcome to Venue Filler Documentation

## Navigation

{% for item in site.nav %}
- [{{ item.name }}]({{ site.baseurl }}{{ item.link }})
{% endfor %}

## Introduction

Venue Filler is an application that subscribes interested people to a service that holds frequent secret events, and looks to fill venues with interested people, chosen randomly, with verified interest.

## Quick Start

- [Installation Guide]({{ site.baseurl }}{{ site.nav | where: "name", "Installation" | map: "link" | first }})
- [User Guide]({{ site.baseurl }}{{ site.nav | where: "name", "User Guide" | map: "link" | first }})
- [Development Guide]({{ site.baseurl }}{{ site.nav | where: "name", "Development Guide" | map: "link" | first }})


