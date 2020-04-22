---
title: "How to Write Reports for Research Hotspot"
header:
  teaser: /assets/images/teaser.png
  overlay_image: /assets/images/overlay.png
last_modified_at: 2020-04-22
categories:
  - Report
  - Thought Piece
tags:
  - Amazon
  - Oil
  - Stonks
---

A sample article tutorial by Jason Tian

### HOW TO FILL IN THE ARTICLE METADATA

**Keep indentation the way it is. Also, it is case-sensitive.**

**title:** title of the article lol, duh.

**header:** Send me ONE image for the article header

**last_modified_at:** article publication date (yyyy-mm-dd) for consistency

**categories:** please have either 'Report' or 'Thought Piece'. I included both for testing lol.

**tags:** please have topics related to article. Choose a **MAXIMUM OF FIVE**, one per line



**Please refer below for stuff you can copy when writing your own article (and replace it with your own text ofc)**:



## Subtitle

^ You should have a few of these per article



### THIS IS A SUB-SUBTITLE

^ Be sure to divide each subtitle into sub-subtitles where appropriate. This makes it easier to include a table of contents.

### Ordered Lists

1. ordered item
2. ordered item 
  * **unordered**
  * **unordered** 
    1. ordered item
    2. ordered item

  * **unordered**
  * **unordered** 
    * unordered item
    * unordered item
### Checkboxes

- [x] Finish this template post
  - [ ] Wow! A sub-task!
  - [x] Make a cool website



### Code Snippet

```css
-ms-word-wrap: break-word;
word-wrap: break-word;
```



### Notices

**Info Notice:** Lorem ipsum dolor sit amet, [consectetur adipiscing elit](#). Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet.
{: .notice--info}

**Warning Notice:** Lorem ipsum dolor sit amet, consectetur adipiscing elit. [Integer nec odio](#). Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet.
{: .notice--warning}

**Danger Notice:** Lorem ipsum dolor sit amet, [consectetur adipiscing](#) elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet.
{: .notice--danger}

**Success Notice:** Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at [nibh elementum](#) imperdiet.
{: .notice--success}



### Quotes

> Only one thing is impossible for God: To find any sense in any copyright law on the planet.

> <cite><a href="http://www.brainyquote.com/quotes/quotes/m/marktwain163473.html">Mark Twain</a></cite>



### Links

Some [links](http://www.google.ca) can also be shown. Go to source code mode to change this



### Embed YouTube Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/fMjIG1HYvHM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



### Image with Caption

fill in the image below (i.e. replace test.png) and the image caption. Send the image to me with the article too.

{% capture fig_img %}
![Foo]({{ '/assets/images/test.png' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>{YOUR IMAGE CAPTION}</figcaption>
</figure>


### Linked Image with Caption (Preferred Method)

Replace image URL and caption below!

{% capture fig_img %}
[![Foo](https://images.unsplash.com/photo-1541943869728-4bd4f450c8f5?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=800&fit=max&ixid=eyJhcHBfaWQiOjF9)](https://unsplash.com/)
{% endcapture %}

{% capture fig_caption %}
This is a caption about the teapots
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>{{ fig_caption | markdownify | remove: "<p>" | remove: "</p>" }}</figcaption>
</figure>