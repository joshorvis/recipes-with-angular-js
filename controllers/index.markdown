---
layout: overview
chapter: controllers
title: Controllers
intro: true
---

Controllers in Angular provide the business logic to handle view behavior, for example responding to a user clicking a button or entering some text in a form. Additionally, controllers prepare the model for the view template.

As a general rule, a controller should not reference or manipulate the DOM directly. This has the benefit of simplifying unit testing controllers.

<h2>Table of Contents</h2>
<ol>
  {% sorted_for page in site.pages | sort_by:order %}
    {% if page.chapter == "controllers" %}
      <li>
        <a href="{{ site.baseurl }}{{page.url}}">{{page.title}}</a>
      </li>
    {% endif %}
  {% endsorted_for %}
</ol>