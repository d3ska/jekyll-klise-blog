---
layout: page
title: Search
---

<form action="{{ site.baseurl }}/search" method="get">
  <label for="search-query">Search:</label>
  <input type="text" id="search-query" name="q" placeholder="Type your search query...">
  <input type="hidden" name="type" value="tag,title">
  <button type="submit">Search</button>
</form>
