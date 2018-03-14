---
layout: post
cover: 'assets/images/402846137-flat-wallpapers.jpg'
title: Plugin Jquery Select com Search
date:   2018-03-13 23:45:00
tags: Javascript, Jquery
subclass: 'post tag-test tag-content'
categories: 'Jeff'
navigation: True
logo: 'assets/images/logo.png'
---




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

<p data-height="657" data-theme-id="dark" data-slug-hash="dmGeGJ" data-default-tab="result" data-user="jeffersonRibeiro" data-embed-version="2" data-pen-title="dmGeGJ" class="codepen">See the Pen <a href="https://codepen.io/jeffersonRibeiro/pen/dmGeGJ/">dmGeGJ</a> by Jefferson Ribeiro (<a href="https://codepen.io/jeffersonRibeiro">@jeffersonRibeiro</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>
