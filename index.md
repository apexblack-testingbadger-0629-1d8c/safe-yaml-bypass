---
layout: null
---
# Site Variable Enumeration

## site.*
site.time: {{ site.time }}
site.pages: {{ site.pages | jsonify }}
site.posts: {{ site.posts | jsonify }}
site.static_files: {{ site.static_files | jsonify }}
site.html_pages: {{ site.html_pages | jsonify }}
site.collections: {{ site.collections | jsonify }}
site.data: {{ site.data | jsonify }}
site.documents: {{ site.documents | jsonify }}
site.tags: {{ site.tags | jsonify }}
site.categories: {{ site.categories | jsonify }}

## jekyll.*
jekyll.version: {{ jekyll.version }}
jekyll.environment: {{ jekyll.environment }}

## ENV dump
ENV KEYS: {{ site.github | jsonify }}
