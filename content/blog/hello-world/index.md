---
title: <Insert Standard First Blog Post Title Here>
date: "2023-10-30"
description: "The write-up of how I made this blog right here, and how you too can (hopefully) do the same."
---

As with all dev/tech blogs, I have decided to create my first blog post be about
the process of creating said blog. Original, I know. If you want to skip to the
the technical stuff below, you can here.(Link to technical part below) If you
want to read more of my ramblings, than that is okay too.

First off, quick description on what we are creating. This is a blog using
Gatsby, and the gatsby-starter-blog starter. Gatsby has many tutorials on how to
get started, and it would be remiss of me to more or less tell you what has
already been written by better devs than me, so I will link you to them. 


The beginner guide [here](https://www.gatsbyjs.com/docs/tutorial/getting-started/)
and the intermediate/advanced quick start for gatsby
[here](https://www.gatsbyjs.com/docs/quick-start/). This write-up will most
definitely brush through some aspest that a beginner might not understand so I
highly recommend checking out the beginner guide if anything written here does
not make sense. Maybe in the future I will create more posts about those things
that are more beginner friendly but for now, I will assume some level of
technical knowledge.

## The Technical Bits

First off, I installed the gatsbi-cli tool very simply using npm...

```console
npm install -g gatsby-cli
```

Then created the blog using the gatsby-starter-blog, replacing the
gatsby-starter-blog with the name of the folder I wanted to store the blog in.
(I chose blog).

```console
npx gatsby new gatsby-starter-blog https://github.com/gatsbyjs/gatsby-starter-blog
```

Personally, I immediately started writing this post, and tinkering with the blog
lay out. You can start the dev server up simply with:

```console
gatsby develop
```

[salted duck eggs](https://en.wikipedia.org/wiki/Salted_duck_egg).

> A salted duck egg is a Chinese preserved food product made by soaking duck

You can also write code blocks here!

```js
const saltyDuckEgg = "chinese preserved food product"
```

| Number | Title                                    | Year |
| :----- | :--------------------------------------- | ---: |
| 1      | Harry Potter and the Philosopher’s Stone | 2001 |
| 2      | Harry Potter and the Chamber of Secrets  | 2002 |
| 3      | Harry Potter and the Prisoner of Azkaban | 2004 |

[View raw (TEST.md)](https://raw.github.com/adamschwartz/github-markdown-kitchen-sink/master/README.md)

This is a paragraph.

    This is a paragraph.

# Header 1

## Header 2

    Header 1
    ========

    Header 2
    --------

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6

    # Header 1
    ## Header 2
    ### Header 3
    #### Header 4
    ##### Header 5
    ###### Header 6

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6

    # Header 1 #
    ## Header 2 ##
    ### Header 3 ###
    #### Header 4 ####
    ##### Header 5 #####
    ###### Header 6 ######

> Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

    > Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> ## This is a header.
>
> 1. This is the first list item.
> 2. This is the second list item.
>
> Here's some example code:
>
>     Markdown.generate();

    > ## This is a header.
    > 1. This is the first list item.
    > 2. This is the second list item.
    >
    > Here's some example code:
    >
    >     Markdown.generate();

- Red
- Green
- Blue

* Red
* Green
* Blue

- Red
- Green
- Blue

```markdown
- Red
- Green
- Blue

* Red
* Green
* Blue

- Red
- Green
- Blue
```

- `code goes` here in this line
- **bold** goes here

```markdown
- `code goes` here in this line
- **bold** goes here
```

1. Buy flour and salt
1. Mix together with water
1. Bake

```markdown
1. Buy flour and salt
1. Mix together with water
1. Bake
```

1. `code goes` here in this line
1. **bold** goes here

```markdown
1. `code goes` here in this line
1. **bold** goes here
```

Paragraph:

    Code

<!-- -->

    Paragraph:

        Code

---

---

---

---

---

    * * *

    ***

    *****

    - - -

    ---------------------------------------

This is [an example](http://example.com "Example") link.

[This link](http://example.com) has no title attr.

This is [an example][id] reference-style link.

[id]: http://example.com "Optional Title"

    This is [an example](http://example.com "Example") link.

    [This link](http://example.com) has no title attr.

    This is [an example] [id] reference-style link.

    [id]: http://example.com "Optional Title"

_single asterisks_

_single underscores_

**double asterisks**

**double underscores**

    *single asterisks*

    _single underscores_

    **double asterisks**

    __double underscores__

This paragraph has some `code` in it.

    This paragraph has some `code` in it.

![Alt Text](https://via.placeholder.com/200x50 "Image Title")

    ![Alt Text](https://via.placeholder.com/200x50 "Image Title")
