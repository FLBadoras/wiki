<table>
 <tr>
  {% for header in page.table.headers %}
  <th>
   {{ header }}
  </th>
  {% endfor %}
 </tr>
 {% for object in page.table.objects %}
 <tr>
  {% for attr in object.attributes %}
  <td>
   <center>{{ attr | markdownify }}</center>
  </td>
  {% endfor %}
 </tr>
 {% endfor %}
</table>
