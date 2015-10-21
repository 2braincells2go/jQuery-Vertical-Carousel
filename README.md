# jQuery-Vertical-Carousel
A simple, easily customizable and lightweight vertical carousel plugin using jQuery

<h3>How to get the Vertical Carousel running in your application</h3>

<h6>Step 1: Include CSS in your header</h6>
<pre>&lt;link rel="stylesheet" href="jQuery.verticalCarousel.css" type="text/css" /&gt;</pre>

<h6>Step 2: Create HTML with the following structure.</h6>
<p>In the following HTML, you can</p>
<ul>
	<li>change the UL &amp; LI tags to any container tags</li>
	<li>use ID or Class to trigger the Carousel</li>
</ul>
<pre>
&lt;div class="<strong>yourClassName</strong>"&gt;
	&lt;a href="#" class="vc_goUp"&gt;Up&lt;/a&gt;
	&lt;ul class="vc_list"&gt;
		&lt;li&gt;..&lt;/li&gt;
		&lt;li&gt;..&lt;/li&gt;
		&lt;li&gt;..&lt;/li&gt;
		&lt;li&gt;..&lt;/li&gt;
		&lt;li&gt;..&lt;/li&gt;
	&lt;/ul&gt;
	&lt;a href="#" class="vc_goDown"&gt;Down&lt;/a&gt;
&lt;/div&gt;
</pre>

<h6>Step 3: Include following JS after including jQuery</h6>
<script type="text/javascript" src="jquery.verticalCarousel.min.js"></script>