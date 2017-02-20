---
layout: default
---

# How to submit to Enginerdery

coming soon.

# Description of Enginerdery template
This section describes the features and components of the Markdown template for use on Enginerdery. A template file can be copied or downloaded for modification [here](../enginerdery-template).

The first thing that needs to be included in the template is the YAML frontmatter as shown below. This block of code contains the title information, tags, categories, the permalink, and author name and URL.
* title: This can be the same as the published paper you are writing about or might be simplified if the original paper title is not easily understandable.
* tags: Tags should be included that reflect the content of the paper.
* category: Choose from `journal-article`, `conference-paper`, or `thesis`.
* permalink: Should be of the format `YYYY/MM/short-title-description`
* post_author: Include your name in the format in which you would like it displayed. Authorship should include only those authors contributing to the blog post, not necessarily all of the paper authors. If more than one author is contributing to the blog post, additional fields may be included of the form `post_author2` and `author_url2` up to five total blog post authors.
* layout and comments: These fields should be left untouched.

```
---
title: "Simplified title goes here"
tags: relevant, tags
category: journal-article
permalink: 2017/01/URL-slug
post_author: Jill J. Jones
author_url: http://www.example.com
layout: post
comments: true
---
```

Next, include the details of your paper as follows:
## Paper title: Title of the paper
### DOI: [10.1063/1.3050881](http://doi.org/10.1063/1.3050881)
### Citation:
```
@article{articleID,
  author  = {Jill J. Jones}, 
  title   = {The title of the work},
  journal = {The name of the journal},
  year    = 1993,
  volume  = 4
  number  = 2,
  pages   = {201-213},
  month   = 7,
  note    = {An optional note},
  doi     = {10.1111/123456789},
  url     = {http://www.example.com/article-url}
}
```

Finally, the content of your blog post. Remember that you are writing for a general audience so please try to avoid jargon or words for which the common definition is not widely known. You should also attempt to avoid the use of any equations as well as any graphics that may not be clear to a non-engineer. You may use any [Markdown formatting](https://guides.github.com/features/mastering-markdown/) you desire.

Images may be included and should be submitted as part of your pull request to the `/images` folder with a file name such as `YYYY-MM-URL-slug-filename.png`.

The [Enginerdery template](https://github.com/OpenEngr/enginerdery/raw/master/enginerdery-template.md) may be downloaded to give you a starting point. Please save your file with a file name of the format `YYYY-MM-URL-slug.md` prior to submitting a pull request.