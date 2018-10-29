---
title: "API: Documentation V.2"
output: 
  html_document:
    keep_md: true
---



### About this documentation

The documentation in this section, the contents of which you can see to the right side of the page, explains the different types of call that can be made to the V2 API.  It also explains each call's purpose, how to structure a specific call, what the response looks like, and provides examples. 

### How to use the V2 API

API queries can be constructed by combining calls and query strings is explained below.

To use the V2 API, you must place v2 in the call.  For example:

http://api.worldbank.org/v2/countries/all/indicators/SP.POP.TOTL

The pages listed on the right hand side of this page describe the different types of requests you can make to the V2 API. Besides making calls to the API using an application or custom program, you can also put the "Example calls" URLs listed in the documentation or your own custom calls into a web browser and view the results. If you choose to receive the result in JSON format you can use the <a href="https://addons.mozilla.org/en-US/firefox/addon/10869/">JSON View</a> Firefox plugin for easily viewing JSON results directly in Firefox.

There are also third party applications and libraries that can make using the API easier depending on your objectives. See <a href="http://data.worldbank.org/developers/application-showcase">Application Showcase
</a> for more details.


### API Access / Authentication

Until recently it was necessary to use an API key to make calls to the API. This has changed. You no longer need an API key.
