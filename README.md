BootstrapCDN
Skip the download with BootstrapCDN to deliver cached version of Bootstrap's compiled CSS and JS to your project.

{% highlight html %}

<script src="{{ site.cdn.js }}" integrity="{{ site.cdn.js_hash }}" crossorigin="anonymous"></script> {% endhighlight %}
If you're using our compiled JavaScript, don't forget to include CDN versions of jQuery and Popper.js before it.

{% highlight html %}

<script src="{{ site.cdn.jquery }}" integrity="{{ site.cdn.jquery_hash }}" crossorigin="anonymous"></script> <script src="{{ site.cdn.popper }}" integrity="{{ site.cdn.popper_hash }}" crossorigin="anonymous"></script>
{% endhighlight %}
