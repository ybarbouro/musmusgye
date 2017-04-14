---
layout: post
title: "Sitio Web Con Jekyll"
date: 2016-02-18 23:01:31 -05:00
---

<figure class="fullwidth"><img src="/Pics/cli.jpg"/></figure>Para probar la presentación con líneas de código... el ejemplo para la Terminal:

{% highlight css %}
pre .gd:after,
pre .gd .x:after,
pre .gi:after,
pre .gi .x:after {
    content: "";
    position: absolute;
    z-index: -1;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0
}
.code-highlight-pre {
    background: #002731
}
.code-highlight-row.numbered:before {
    color: #586e75;
    background: #073642;
    border-right: 1px solid #00232c;
    box-shadow: #083e4b -1px 0 inset;
    text-shadow: #021014 0 -1px
}
.marked-line .code-highlight-line:before {
    background: rgba(0, 186, 255, 0.13)
}
.marked-line.numbered:before {
    background: rgba(0, 186, 255, 0.13);
    border-right-color: rgba(0, 112, 153, 0.13)
}
{% endhighlight %}

Y ahora un Gist:

<script src="https://gist.github.com/fernanz/f93d8c39ab0b37070737.js"></script>
