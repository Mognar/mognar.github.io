---
layout: page
title:  "division data"
date:   2019-01-21 12:18:21 -0400
categories: data
---
<table>
{% for x in site.data.Alldvisiondata %}
  <tr>
   <td>{{ x.Votenumber}}</td>	
    <td>{{ x.Votetitle}}</td>
  <tr>
{% endfor %}
</table>
