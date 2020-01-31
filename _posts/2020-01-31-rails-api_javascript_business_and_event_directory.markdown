---
layout: post
title:      "Rails-API/Javascript Business and Event Directory"
date:       2020-01-31 21:11:17 +0000
permalink:  rails-api_javascript_business_and_event_directory
---

Thisis a single page application that displays organizations, events, categories and tags from JSON objects created from a rails backend API.  CRUD actions include a create action that creats new organizations, events and their related categories and tags.  Additionally, each organization, event, category and tag object has a rank attribute that is incremented through an update CRUD action.  These CRUD actions are updated using an AJAX technique so no browser refresh is necessary.

The DOM is built out entirely though javascript.  Javascript objects are created through classes by iterating through JSON objects and pushing them into an array.  Data is dispalyed on the user interface by creating elements and listener events via javascript.  These events trigger the CRUD actions using an AJAX technique metioned above.
