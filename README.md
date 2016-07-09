This file is documentation of Shiva Blog & Portfolio Ghost Theme.

### Demo
http://shiva-malvouz.rhcloud.com/

### Description
This is for Ghost Theme platform. Ghost is a free and open source platform. You can download at https://ghost.org/download/ or asking your hosting provider if they support ghost platform or not.

### Installation
For installation for Ghost, please refer to http://support.ghost.org/installation/ Just to make sure Ghost need Node.js version 0.10.X. DO NOT download latest version of node.js, because it wont work.

For installing theme, copy download packet and paste into /content/themes/.


### Post Type
There are four (4) types of post:

1. Standard Post (ex: http://shiva-malvouz.rhcloud.com/i-got-all-i-need-when-i-got-you/)

2. Gallery Post (ex: http://shiva-malvouz.rhcloud.com/food-fest/)

3. Code Post (ex: http://shiva-malvouz.rhcloud.com/learnjqueryfrombasic/)


4. Quote Post (ex: http://shiva-malvouz.rhcloud.com/why-you-are-the-source-of-all-your-problems/)

### Standard Post

As usual, just write a blog without put featured image.

### Gallery Post Masonry

Put your featured image, image and post, and you will see a code like this

`![](/content/images/2016/06/13419257_1110618922336940_3767900202822738425_n.jpg)`

Added `<a></a>`

`<a href="/content/images/2016/06/13419257_1110618922336940_3767900202822738425_n.jpg" title="Me with Leaf"></a>`

Finish Code

`<a href="/content/images/2016/06/13419257_1110618922336940_3767900202822738425_n.jpg" title="Me with Leaf">![](/content/images/2016/06/13419257_1110618922336940_3767900202822738425_n.jpg)</a>`

Just copy as many as you want.

### Code Post

Put  `<pre class="line-numbers"><code class="language-javascript">` before your code.

```
<pre class="line-numbers"><code class="language-javascript">// jQuery
$(document).ready(function(){

  // Masonry
  $('.content').masonry({
  // options
  itemSelector: '.grid'
});

  // Menu
  $( ".hamburger" ).click(function() {
  $( ".menu" ).toggle();
});

}); //jQuery ready
</code></pre>
```

### Quote Post

```
>He who is not courageous enough to take risks will accomplish nothing in life.

== Muhammad Ali ==
```
