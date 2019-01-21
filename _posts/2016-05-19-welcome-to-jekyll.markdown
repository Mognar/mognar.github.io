---
layout: page
title:  "Some data"
date:   2019-01-21 12:05:21 -0400
categories: data
---
<table>
{% for x in site.data.Alldvisiondata %}
  <tr>
   <td>{{ x.Vote number}}</td>	<td>{{ x.Vote title}}</td>	<td>{{ x.Ayes}}</td>	<td>{{ x.Noes}}</td>	<td>{{ x.Conservative}}</td>	<td>{{ x.Democratic Unionist Party}}</td>	<td>{{ x.Green Party}}</td>	<td>{{ x.Independent}}</td><td>{{ x.Labour}}</td>	<td>{{ x.Labour (Co-op)}}</td>	<td>{{ x.Liberal Democrat}}</td>	<td>{{ x.Plaid Cymru}}</td>	<td>{{ x.Scottish National Party}}</td>	<td>{{ x.Grand Total}}</td>

  <tr>
{% endfor %}
</table>
