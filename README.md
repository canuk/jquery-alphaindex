jquery-alphaindex
=================
https://github.com/idlesign/jquery-alphaindex

[![npm](https://img.shields.io/npm/v/jquery-alphaindex.svg)]() [![npm](https://img.shields.io/npm/dt/jquery-alphaindex.svg)]()

Description
-----------

*jQuery plugin to create alphabetical indexes for your lists.*

An alphabetical index may help your users to navigate through a long list of items.


Usage
-----

Make a list:

```html
    <ul id="my-list">
        <li>Joker James</li>
        <li>Anderson Ann</li>
        <li>Johnson John</li>
    </ul>
```

Initialize an index:

```javascript
    var myIndex = $('#my-list').makeAlphaIndex(),
        indexBar = myIndex.alphaIndexBar;
```

Demo
----

* Demo page is available in sources: demo/demo.html.
* Hosted demo: https://idlesign.github.io/jquery-alphaindex/demo/demo.html


Styling
-------

* List is marked with ``.alpha-index-list``.
* Index bar is marked with ``.alpha-index-bar``.
* Index bar current item is marked with ``.current``.