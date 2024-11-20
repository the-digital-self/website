---
layout: page
title: Style Guide
permalink: /styleguide/
image: '/images/26.jpg'
---

A paragraph looks like this — In qua quid est boni praeter summam voluptatem, et eam sempiternam? Cur post Tarentum ad Archytam? Qua ex cognitione facilior facta est investigatio rerum occultissimarum. Negat enim tenuissimo victu, id est contemptissimis escis et potionibus, minorem voluptatem percipi quam rebus exquisitissimis ad epulandum. Non enim iam stirpis bonum quaeret, sed animalis. Qui autem esse poteris, nisi te amor ipse ceperit? Sic igitur in homine perfectio ista in eo potissimum, quod est optimum, id est in virtute, laudatur.

***

## Headings by default:

# H1 For example
## H2 For example
### H3 For example
#### H4 For example
##### H5 For example
###### H6 For example

***

## Lists

#### Ordered list example:

1. Poutine drinking vinegar bitters.
2. Coloring book distillery fanny pack.
3. Venmo biodiesel gentrify enamel pin meditation.
4. Jean shorts shaman listicle pickled portland.
5. Salvia mumblecore brunch iPhone migas.

***

#### Unordered list example:

* Bitters semiotics vice thundercats synth.
* Literally cred narwhal bitters wayfarers.
* Kale chips chartreuse paleo tbh street art marfa.
* Mlkshk polaroid sriracha brooklyn.
* Pug you probably haven't heard of them air plant man bun.

***

## Table

<div class="table-container">
  <table>
    <tr><th>Header 1</th><th>Header 2</th><th>Header 3</th><th>Header 4</th><th>Header 5</th></tr>
    <tr><td>Row:1 Cell:1</td><td>Row:1 Cell:2</td><td>Row:1 Cell:3</td><td>Row:1 Cell:4</td><td>Row:1 Cell:5</td></tr>
    <tr><td>Row:2 Cell:1</td><td>Row:2 Cell:2</td><td>Row:2 Cell:3</td><td>Row:2 Cell:4</td><td>Row:2 Cell:5</td></tr>
    <tr><td>Row:3 Cell:1</td><td>Row:3 Cell:2</td><td>Row:3 Cell:3</td><td>Row:3 Cell:4</td><td>Row:3 Cell:5</td></tr>
    <tr><td>Row:4 Cell:1</td><td>Row:4 Cell:2</td><td>Row:4 Cell:3</td><td>Row:4 Cell:4</td><td>Row:4 Cell:5</td></tr>
    <tr><td>Row:5 Cell:1</td><td>Row:5 Cell:2</td><td>Row:5 Cell:3</td><td>Row:5 Cell:4</td><td>Row:5 Cell:5</td></tr>
    <tr><td>Row:6 Cell:1</td><td>Row:6 Cell:2</td><td>Row:6 Cell:3</td><td>Row:6 Cell:4</td><td>Row:6 Cell:5</td></tr>
  </table>
</div>

***

## Quotes

#### A quote looks like this:

> The longer I live, the more I realize that I am never wrong about anything, and that all the pains I have so humbly taken to verify my notions have only wasted my time!
>
> <cite>George Bernard Shaw</cite>

{% highlight html %}
> The longer I live, the more I realize that I am never wrong about anything, and that all the pains I have so humbly taken to verify my notions have only wasted my time!
>
> <cite>George Bernard Shaw</cite>
{% endhighlight %}

***



## Syntax Highlighter

{% highlight js %}
  $('.top').click(function () {
    $('html, body').stop().animate({ scrollTop: 0 }, 'slow', 'swing');
  });
  $(window).scroll(function () {
    if ($(this).scrollTop() > $(window).height()) {
      $('.top').addClass("top-active");
    } else {
      $('.top').removeClass("top-active");
    };
  });
{% endhighlight %}

***

## Videos

<p><iframe src="https://www.youtube.com/embed/iWowJBRMtpc" frameborder="0" allowfullscreen></iframe></p>

***

## Images

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/04.jpg">
    <img src="/images/06.jpg">
    <img src="/images/05.jpg">
    <img src="/images/07.jpg">
    <img src="/images/08.jpg">
    <img src="/images/09.jpg">
  </div>
  <em>Gallery / <a href="https://unsplash.com/" target="_blank">Unsplash</a></em>
</div>

![]({{site.baseurl}}/images/25.jpg)
*Beautiful place / [Unsplash](https://unsplash.com/)*