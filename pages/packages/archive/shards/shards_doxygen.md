---
title: Shards Doxygen
permalink: shards_doxygen.html
folder: archive
show_sidebar: true
contact: hcedwar@sandia.gov
package: shards
doxygen: true
---

Development Doxygen for Shards is available [Here](http://trilinos.org/docs/dev/packages/shards/doc/html/index.html)  
Links to all available Trilinos release Doxygen collections for Shards are listed below.  
Trilinos Version: 

{% for trilinos_version in site.trilinos_versions %}
[{{ trilinos_version }}]({{ "http://trilinos.org/docs/r" | append: trilinos_version | append: "/packages/" | append: page.package | append: "/doc/html/index.html" }}),{% endfor %}
