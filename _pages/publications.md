---
layout: page
permalink: /publications/
title: publications
description: "* denotes equal contribution"
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<div class="publications">

<h2 class="bibliography">conference & journal papers</h2>

{% bibliography --group_by none --query @*[category=main] %}

<h2 class="bibliography">workshop papers</h2>

{% bibliography --group_by none --query @*[category=workshop] %}

</div>
