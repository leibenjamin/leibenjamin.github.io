Ben’s Stream
============

Embedding Content
-----------------

This nanoblog has been customized with a special options for embedding links,
images, and videos. Only one image or video can be embedded per post.

To embed a link in the title of the post:

    ---
    layout: post
    title:  Hello, World!
    link:   http://www.example.org/
    ---

To embed an image just below the title of the post:

    ---
    layout: post
    title:  Hello, World!
    link:   http://www.example.org/
    image:  http://www.example.org/image.png
    ---

To embed a YouTube video just below the title of the post:

    ---
    layout:  post
    title:   Hello, World!
    link:    https://www.youtube.com/watch?v=abcdefghijk#t=1m30s
    youtube: abcdefghijk?start=90
    ---

To embed a Vimeo video just below the title of the post:

    ---
    layout:  post
    title:   Hello, World!
    link:    https://vimeo.com/12345678
    vimeo:   12345678
    ---

Tags
----

To add tags:

    ---
    layout: post
    title:  Hello, World!
    link:   http://www.example.org/
    tags:
    - Welcome
    - HelloWorld
    ---

Tags require JavaScript and IE9+.
