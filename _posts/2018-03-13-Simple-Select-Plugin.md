---
layout: post
cover: 'assets/images/hello-world.jpg'
title: Plugin Jquery Select com Search
date:   2018-03-13 23:45:00
tags: Javascript, Jquery
subclass: 'post tag-test tag-content'
categories: 'Jeff'
navigation: True
logo: 'assets/images/logo.png'
---



SimpleSelect jQuery Plugin

HTML:
~~~html

<select id="segment" name="segmentation"></select>

~~~

JavaScript
~~~javascript

var options = {
    terms: [
        'RESTAURANTE',
        'PADARIA',
        'PIZZARIA',
        'HAMBURGUERIA',
        'CHURRASCARIA',
        'COZINHA',
        'INDUSTRIAL',
        'TESTE',
        'JAVASCRIPT',
        'PHP',
        'BRAZIL',
        'CANADA',
        'MEAN'
    ]
}

$('#segment').simpleSelect(options);

~~~
