# drupaldiversity.github.io
Public website for the Drupal Diversity project

# DrupalDiversity.github.io Contributor's Guide

When adding documents, be sure to use [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/ "GitHub Flavored Markdown").

### Technical Team

- cleverington
- seanr
- justachris
- justafish
- sugaroverflow
- zombree

### Editing

Editing current pages can be done using MarkDown via GitHub or Git by submitting Pull Requests.

Please create new branches when submitting Pull Requests.

![Contribution Edit Link](https://github.com/drupaldiversity/event-organizer-packet/blob/master/images/contribution-edit-link.png?raw=true "Contribution Edit Link")

### Creating Posts

Posts are created and loaded based on time-stamp order with paths (urls) based on the categories.

Refer to existing pages for examples, but all pages should have (at least) the following for creation:

```
---
layout: post
title:  "title in quotes"
date:   YYYY-MM-DD HH:MM:SS
published: true
categories:
    Category 1
    Category 2
    Category 3
---

# Content Goes here

For Accessibility and screen-reader goodness, don't forget to use Headers!

Headers in Markdown use # for h1, # for h2, and so-on.
```

**Note** - `categories` can instead be a single-line and single-item of `category: item`.

**Note** - Additional posts will be reviewed by the Content Team prior to approval.

### Creating Pages

Adding pages is almost completely identical to adding posts, but instead of using the 'Categories' to create the paths (urls), they are instead explicitly defined using the `permalink` attribute.

```
---
layout: page
title: Initiatives & Get Involved
permalink: /get-involved/
---

# Content Goes here

For Accessibility and screen-reader goodness, don't forget to use Headers!

Headers in Markdown use # for h1, # for h2, and so-on.
```

**Note** - Additional pages will be reviewed by the Content Team prior to approval.

### Creating Links
```
[https://www.drupal.org/community](https://www.drupal.org/community "Title Text")
```

### Adding Images
```
![Druplicon](https://github.com/drupaldiversity/event-organizer-packet/blob/master/images/druplicon-small.png?raw=true "Druplicon")
```

If the images are in a directory, add the directory:

At times, the image may fail to load, even if deployed properly. Simply submit an issue requesting image correction and we can help link it.

```
![Druplicon](../images/random-directory/druplicon-small.png "Druplicon")
```

Be Accessible. Remember the Alt-Text!

