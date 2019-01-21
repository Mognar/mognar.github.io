---
layout: page
title:  "division data"
date:   2019-01-21 12:18:21 -0400
categories: data
---
<table class="divtable">
   <thead>
    {% for column in site.data.Alldvisiondata[0] %}
        <th class="rotate">{{ column[0] }}</th>
    {% endfor %}
    </thead>
{% for x in site.data.Alldvisiondata %}
  <tr>
   <td>{{ x.Votenumber}}</td>	
    <td>{{ x.Votetitle}}</td>
    <td>{{ x.Ayes}}</td>
    <td>{{ x.Noes}}</td>	
    <td>{{ x.Conservative}}</td>	
    <td>{{ x.DemocraticUnionistParty}}</td>	
    <td>{{ x.GreenParty}}</td>	
    <td>{{ x.Independent}}</td>	
    <td>{{ x.Labour}}</td>	
    <td>{{ x.LabourCoop}}</td>	
    <td>{{ x.LiberalDemocrat}}</td>	
    <td>{{ x.PlaidCymru}}</td>	
    <td>{{ x.ScottishNationalParty}}</td>	
    <td>{{ x.GrandTotal}}</td>
  <tr>
{% endfor %}
</table>
