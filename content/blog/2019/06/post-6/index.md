---
title: "Post 6 with its UNIQUE title" # Quotation marks allow colons, semicolons, etc.
description: "The UNIQUE description for Post 6." # Quotation marks allow colons, semicolons, etc.
date: 2019-06-08T15:25:00-05:00 # This would be 8:25 PM (2025) UTC on June 8, 2019
updated: 2019-07-25T14:05:00-05:00 # Comment-out this line with a # if content is unchanged
draft: false # Make it "true" if you don't want Zola to "publish" yet
template: blogPage.html
taxonomies:
  categories:
    - Foundation
  tags: [threefold_grid, community, farming, interview, update]

extra:
  subtitle: "The UNIQUE Post 6 subtitle" # Quotation marks allow colons, semicolons, etc.
  author: Your name goes here
  authorImg: /images/people/hannah_cordes.jpg
  category: "Engineering"
  imgPath: images/threefold_blog2.png
  date: 2018-10-17T14:40:00-05:00
---

Your opening text goes here.

## In-article heading --- it's an H2 because your title is the H1

And after another paragraph or two or three, you may want to add a subheading, which would be an H3, so it would be like the following.

### Subheading (H3)

Text here.

Maybe you want a code block to illustrate something. Here's one:

```js
/* =========
This is some simple JavaScript, just so 
you can see how Zola handles a code block.
It doesn't **do** anything in Zola, of course. 
Helpful on a dev blog, eh?
========= */

var i, j;
for (i = 0; i < 10; i++) {
  j = i;
  console.log(j);
}

/* ========= 
When run, the above would output:

0
1
2
3
4
5
6
7
8
9
========= */
```

Closing text. That ends Post 6! One more to go in this starter set.
