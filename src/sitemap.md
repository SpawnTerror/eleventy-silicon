---
layout: layouts/base.njk
title: "Site map"
permalink: /sitemap/
eleventyExcludeFromCollections: true
---

<h1 id="site-map"><a href="#site-map">Site map</a></h1>
<p class="page-lead">Complete directory of pages, system endpoints, topics, and all {{ collections.posts | length }} published notes.</p>

{# Add or edit manual pages and system endpoints here #}
{% set sitePages = [
  { name: "Home", path: "/" },
  { name: "Archive", path: "/archive/" },
  { name: "Topics", path: "/topics/" },
  { name: "About", path: "/about/" },
  { name: "Contact", path: "/contact/" },
  { name: "Privacy", path: "/privacy/" },
  { name: "Formatting Reference", path: "/formatting-reference-file/" },
  { name: "Humans", path: "/humans.txt" },
  { name: "Robots", path: "/robots.txt" },
  { name: "XML Sitemap", path: "/sitemap.xml" }
] %}

<h2>Pages &amp; endpoints</h2>
<div class="sitemap-grid">
{% for item in sitePages %}
  <a href="{{ item.path }}" class="sitemap-tile">
    <span class="sitemap-tile-name">{{ item.name }}</span>
    <span class="sitemap-tile-path">{{ item.path }}</span>
  </a>
{% endfor %}
</div>

<h2>Topics</h2>
{% set topicOrder = ["Coding", "Hardware", "Linux", "Automation", "Design", "Retro"] %}
<div class="sitemap-topics">
{% for t in topicOrder %}
  {% set tPosts = collections[t | lower] or collections[t] %}
  <a href="/tags/{{ t | lower }}/" class="sitemap-topic-pill">
    <span>{{ t }}</span>
    <span class="sitemap-topic-count">{{ tPosts | length if tPosts else 0 }}</span>
  </a>
{% endfor %}
</div>

<h2>Articles ({{ collections.posts | length }})</h2>
<ul class="sitemap-articles">
{% for post in collections.posts | sortByTitle %}
  <li>
    <a href="{{ post.url }}" class="sitemap-article-link">
      <span class="sitemap-article-title">{{ post.data.title }}</span>
      <span class="sitemap-article-date">{{ post.date | isoDate }}</span>
    </a>
  </li>
{% endfor %}
</ul>
