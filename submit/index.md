---
layout: default
---

# How to submit to Enginerdery

The process for submitting to Enginerdery is relatively straightforward.
1. Have a recently published work that you would like to write about.
2. Download the [Enginerdery blog post template](https://github.com/OpenEngr/enginerdery/raw/master/enginerdery-template.md) (described further below).
3. Use the template to fill in the details about your work and author your post in [Markdown](https://guides.github.com/features/mastering-markdown/). Be sure to focus on using simple language and avoid unnecessary jargon. Remember that this blog post is intended for a general audience. While the typical research paper starts with an introduction, describes the methods, and finishes with the conclusions, a blog post for the general public should instead lead with the key findings and follow it up by answering the question, _why should I care?_ In general you can leave out the methods; the interested reader can click through to your full paper.
4. Fork the [Enginerdery Github repo](https://github.com/OpenEngr/enginerdery).*
5. Save your authored post to the `_posts` folder using the `YYYY-MM-URL-slug.md` file naming format.
6. Add any images to the `/images` folder with a file name such as `YYYY-MM-URL-slug-filename.png`.
7. [Submit a pull request](https://github.com/OpenEngr/enginerdery/pulls) with your additions.
8. If any corrections are needed prior to posting, you will be notified via a comment on your pull request.

\* Alternatively you can navigate to the [_posts](https://github.com/OpenEngr/enginerdery/tree/master/_posts) folder in the Github repo and click `Create new file` or `Upload files` to simultaneously create a fork and submit a pull request.


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
tags: [relevant, tags]
category: journal-article
permalink: 2017/01/URL-slug
post_author: Jill J. Jones
author_url: http://www.example.com
layout: post
comments: true
---
```

Next, include the details of your paper as follows:
**Paper title: Title of the paper**
**DOI: [10.1063/1.3050881](http://doi.org/10.1063/1.3050881)**
If the paper is locked behind a paywall, you are __encouraged__ to provide a link to an accessible (preprint, repository, self-hosted) version here.

Finally, the content of your blog post. Remember that you are writing for a general audience so please try to avoid jargon or words for which the common definition is not widely known. You should also attempt to avoid the use of any equations as well as any graphics that may not be clear to a non-engineer. You may use any [Markdown formatting](https://guides.github.com/features/mastering-markdown/) you desire.

Finally, the Bibtex citation for your paper can be included at the bottom as below.
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

Images may be included and should be submitted as part of your pull request to the `/images` folder with a file name such as `YYYY-MM-URL-slug-filename.png`.

The [Enginerdery template](https://github.com/OpenEngr/enginerdery/raw/master/enginerdery-template.md) may be downloaded to give you a starting point. Please save your file with a file name of the format `YYYY-MM-URL-slug.md` prior to [submitting a pull request](https://github.com/OpenEngr/enginerdery/pulls).

<div style="font-size: 50px; text-align: center;"><a href="https://github.com/OpenEngr/enginerdery/raw/master/enginerdery-template.md">Download the Template</a></div>