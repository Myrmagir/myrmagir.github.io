---
layout: archive
title: "Search"
permalink: /search/
author_profile: false
sidebar:
  nav: "search-sidebar"
---

<form id="site_search" onsubmit="return false;">
	<left>
	  <input type="text" placeholder="Search" id="search_box">
	</left>
</form>


## Results

<article>
	<section>
		<ul id="search_results"></ul>
	</section>
</article>

<script src="/assets/js/lunr.min.js"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script src="/assets/js/search.js"></script>