---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

Education
=========

* Ph.D in Dept. of AI Convergence, 2025.09 ~
* M.S. in Dept. of AI Convergence, Chonnam National University, 2025.08
* B.S. in Dept. of Software Engineering, Chonnam National University, 2024.02

Work experience
===============

* Spring 2024: Academic Pages Collaborator

  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users
* Fall 2015: Research Assistant

  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
* Summer 2015: Research Assistant

  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

Skills
======

* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
============

<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Invited Talks
=============

<ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
========

<ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
