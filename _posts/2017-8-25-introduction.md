---
layout: post
title: Introduction
description: About Sakila and this project
image: assets/images/pic01.jpg
nav-menu: true
---
## About this project

This project aims to demonstrate the use of SQL to answer hypothetical marketing-related questions about a DVD rental store with a MySQL database named Sakila.

I run Debian Linux (version 9, "Stretch") on my laptop, so I have used the default MySQL server for this operating system, [MariaDB 10.1](https://en.wikipedia.org/wiki/MariaDB). This report was generated using [Markdown](https://guides.github.com/features/mastering-markdown/), [Liquid templates](https://shopify.github.io/liquid/), and [Jekyll](https://jekyllrb.com/). And I used the Jekyll theme ["Forty by HTML5 UP"](http://jekyllthemes.org/themes/Forty/).

Data-sets were generated using SQL but exported to CSV.

## About Sakila

The [Sakila](https://dev.mysql.com/doc/sakila/en/) MySQL sample database is available from [http://dev.mysql.com/doc/index-other.html](http://dev.mysql.com/doc/index-other.html). You can follow these simple [intructions](https://dev.mysql.com/doc/sakila/en/sakila-installation.html) to install it.

The database presents a nicely normalised schema modelling a DVD rental store, featuring information such as films, actors, film-actor relationships, and a central inventory table that connects film, stores, and rentals.

The following diagram provides an overview of the database structure. The diagram source file `sakila.mwb` (for use with MySQL Workbench) is included in the Sakila distribution.

![Sakila database structure]({{ site.url }}/assets/images/sakila-structure.png)
_You can get the PDF version of the image through this [link]({{ site.baseurl }}/assets/images/sakila-structure.pdf)._

&nbsp;

<div class="end-page">
<a href="/2017/08/24/tables-and-view.html" class="button fit small">Continue to section: Tables and Views</a>
</div>
