---
layout: home
title: Home
---

<div id="intro-wrapper" class="l-text">
	<div id="intro-title-wrapper">
		<div id="intro-image-wrapper">
			<img id="intro-image" src="/images/portrait.jpg"></div>
		<div id="intro-title-text-wrapper">
			<h1 id="intro-title">Hi, I'm Giacomo Ruvolo</h1>
			<div id="intro-subtitle">I’m currently pursuing a Master’s degree in Computer Science and Engineering at Politecnico di Milano, with a focus on ICT Engineering, Business, and Innovation</div>
			<div id="intro-subtitle"></div>
			<div id="intro-title-socials">
				{% for link in site.data.social-links %}
					{% if link.on-homepage == true %}
						{% include social-link.html link=link %}
					{% endif %}
				{% endfor %}
			</div>
		</div>
	</div>
	<!-- <hr class="l-middle home-hr"> -->
	<div id="everything-else" class="l-middle">
		<a href="/cv.pdf"><div><i class="fa fa-portrait icon icon-right-space"></i>CV</div></a>
		<!-- <a href="{{ site.url }}/projects"><div><i class="fa fa-shapes icon icon-right-space"></i>Projects</div></a>-->
		<a href="https://www.google.com/search?q=Do+a+barrel+roll"><div><i class="fa fa-list-ul icon icon-right-space"></i>Everything Else</div></a>
	</div>
	<div>
		"Why couldn't the programmer dance to the song?<br>
		Because he didn't get the... Algo-rhythm..."<br>
		<strong>Maybe this is the reason why I can't be a dancer but can be a developer!</strong>
	</div>
	<div style="height: 1rem"></div>
	<div>I am a Computer Engineer currently living in Milan. I hold a Bachelor’s degree in Computer Engineering and I’m currently pursuing a Master’s degree in Computer Science and Engineering at Politecnico di Milano, with a focus on ICT Engineering, Business, and Innovation.

Originally from Sicily, I have always been passionate about innovation, new technologies, and entrepreneurship. My technical background is rooted in web development (HTML, CSS, PHP, GitHub), and I also have experience in IT consulting for PMI and business management.

In addition to my academic path, I am the CEO of my family business, Parafarmacia Naxos, where I oversee accounting, economic planning, and financial management.</div>
	<div style="height: 1rem"></div>
	<div>
		I am a motorbike fanatic. I am a member of <a href="https://www.etnachapter.it/"> Etna Chapter Italy #7292</a>, Catania's official Harley-Davidson motorbike club, where I serve as Webmaster and Road Captain.
		I am an insatiable explorer, always eager to get my hands dirty! Let's get started!
	</div>
</div>

<!-- 
<hr class="l-middle home-hr">


<h2 class="feature-title">Featured <a href="/cv/#publications">Research Publications</a></h2>

<p class="feature-text">
	Latest research for fans of human-computer interaction, data visualization, and machine learning.
</p>

<div class="cover-wrapper cover-wrapper-3-col l-page">
	{% comment %}
	{% assign sortedPublications = site.categories.papers | sort: 'feature-order' %}
	{% for feature in sortedPublications %}
		{% if feature.featured == true %}
			{% include feature.html feature=feature %}
		{% endif %}
	{% endfor %}
	{% endcomment %}
</div>


<br>
<h2 class="feature-title">Featured <a href="/dissertation">Dissertation Publications</a></h2>

<p class="feature-text">
	My dissertation contributed interactive interfaces to enable machine learning interpretability at scale and for everyone.
</p>

<div class="cover-wrapper cover-wrapper-1-col l-text">
	{% comment %}	
	{% include dissertation/document.html details=false location=home %}
	{% endcomment %}
</div>

<div class="cover-wrapper cover-wrapper-3-col l-page">
	{% comment %}
	{% assign sortedPublications = site.categories.papers | sort: 'feature-order' %}
	{% for feature in sortedPublications %}
		{% if feature.dissertation == true %}
			{% include feature.html feature=feature %}
		{% endif %}
	{% endfor %}
	{% endcomment %}
</div>

<br>
<h2 class="feature-title">Apple <a href="https://developer.apple.com/design/human-interface-guidelines/">Chart Design Guidelines</a></h2>

<p class="feature-text">
	Guidance and best practices to help designers and developers create the best charts for Apple platforms.
</p>

<div class="cover-wrapper cover-wrapper-2-col l-middle">
	{% comment %}
	{% for feature in site.data.designs %}
		{% if feature.featured == true %}
			{% include feature.html feature=feature %}
		{% endif %}
	{% endfor %}
	{% endcomment %}
</div>

<br>
<h2 class="feature-title">Featured <a href="/cv/#interactive-articles">Interactive Articles</a></h2>

<p class="feature-text">
	Enhanced reading experiences that demonstrate what's possible when dynamic media are effectively combined.
 
</p>

<div class="cover-wrapper cover-wrapper-3-col l-page">
	{% comment %}
	{% assign sortedArticles = site.data.articles | where: "featured", true %}
	{% assign ia = site.categories.papers | where:"permalink", "papers/interactive-articles" %}

	{% assign feature = sortedArticles[1] %}
	{% include feature.html feature=feature %}

	{% assign feature = sortedArticles[0] %}
	{% include feature.html feature=feature %}

	{% assign feature = ia[0] %}
	{% include feature.html feature=feature %}
	{% endcomment %}
</div>

<br>
<h2 class="feature-title"><a href="https://parametric.press/about">Parametric Press</a></h2>

<p class="feature-text">
	A born-digital, experimental magazine dedicated to showcasing the expository power of the web.
</p>

<div class="cover-wrapper cover-wrapper-2-col l-middle">
	{% comment %}
	{% assign parametric = site.data.articles | where: "parametric-issue", true %}
	{% for feature in parametric %}
		{% include feature.html feature=feature %}
	{% endfor %}
	{% endcomment %}
</div>

-->


[cv]: {{ site.url }}/cv
