---
title: Ecotechnologies
layout: default
---
 
# Ecotechnologies

This website was set up by a group of friends to share information about technology.

By technology we do not mean  the complex, resource intensive and often extremely expensive 
developments that are promoted in the 'tech' pages of mainstream media outlets
such as the [BBC](http://www.bbc.co.uk/news/technology/) and 
such as [MIT's Technology Review site](http://www.technologyreview.com/).

We are interested in simple technologies that are accessible and empowering,
affordable and fixable, and of use to people worldwide. In other words this 
is a website about *appropriate technology*. Specifically, we are interested 
in solutions that meet the following four criteria, set out by John Michael Greer.
Ecotechnologies must be:

 - **Simple** so they are resilient and can be fixed when they break 
 - **Scalable** with the potential of being replicated around the world
 - **Modular** such that their component parts are multi-purpose
 - **Open source** so other people can build on the work of others

Based on these ideal, this website is built in a way that is simple, scalable, modular and open source.
Without going into the details of it, all the code underlying this site is available online.
Please fork the project, or, even better, request to join the ecotechnologies team on GitHub 
if you are interested in getting involved.  

# 5 most recent posts

{% for post in site.posts limit:2 %}
                <h2><a href="{{ post.url }}">{{ post.title }} </a></h2>
                <h4>Article of {{ post.content | number_of_words}} words, published {{ post.date | date: "%-d %B %Y" }}</h4>
        <p>{{ post.excerpt }}</p>
  {% endfor %}
