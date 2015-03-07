# Matics Barcelona website

## How to add my artist profile?

* First send your github username to the mailing list or google group or facebook and we will add to the organization in order to have the rights to edit the Matics web page. You can also open an issue here, on github, to request the access.
* Second follow the tutorial from https://docs.google.com/document/d/1VQPeZa8nHfqGQ8f3Dbq3SSFbVp3EzcxogMwB9gPcRb4/edit?usp=sharing or watch the screencasts below

### Add Artist

![Add Artist](https://raw.githubusercontent.com/MaticsBarcelona/MaticsBarcelona.github.io/master/tutorials/add_artist.gif)

### Add Profile

![Add Profile](https://raw.githubusercontent.com/MaticsBarcelona/MaticsBarcelona.github.io/master/tutorials/add_profile.gif)

### Edit Profile

![Edit Profile](https://raw.githubusercontent.com/MaticsBarcelona/MaticsBarcelona.github.io/master/tutorials/edit_profile.gif)

### The header of a post

All the posts should start with the following header format
```
---
layout: post
title: "Francesc Benlliure"
author: francesc
excerpt: "Gestor Cultural"
category: artists
tags: [Comunicacion, Video]
comments: false
---
```

* layout: all the time shall be post
* title: is the title of the post
* author: the person that wrote the post, for the artist profiles categories each author should have only one post (each author should post his own profile). ***The author string shall be the same as the one defined in the file*** https://github.com/MaticsBarcelona/MaticsBarcelona.github.io/blob/master/_data/authors.yml
* excerpt: write here the excerpt of your post
* categories: this field defines in what page the post will be published. ***For the moment we have 2 categories artists and blog***
* tages: you can write here any tag you want, separated by comma
* comments: if set to false disables the comments for the post if set to true will enable the comments for the post. The comments implementation is using the disquss platform

###Markdown

Markdown is the sytax used to write the posts, it allows us to format the text, insert links, images, videos.

Here are some usefull links in which this syntax is explained:

- https://help.github.com/articles/markdown-basics/
- https://help.github.com/articles/writing-on-github/
- https://help.github.com/articles/github-flavored-markdown/
- https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
- https://guides.github.com/features/mastering-markdown/


## Todo List
- [ ] Editar Valores, descripcion
- [ ] Logo
- [ ] Imagen grande para la pag. about
- [ ] Layout Pagina Artist tipo: https://mademistakes.com/paperfaces/
