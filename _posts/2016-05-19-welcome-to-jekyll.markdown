---
layout: page
title:  "Some data"
date:   2019-01-21 12:05:21 -0400
categories: data
---
<table>
{% for x in site.data.Alldvisiondata %}
  <tr>
    <td>{{ x.Ayes}}
    </td>
  <tr>
{% endfor %}
</table>
