{: .contributing }
Die folgende Liste darf gerne erweitert werden! Wichtig: Die Einträge sollen
alphabetisch sortiert werden, bitte beim Einfügen beachten.

<table>
 <tr>
  {% for header in page.table_headers %}
  <th>
   {{ header }}
  </th>
  {% endfor %}
 </tr>
 {% for object in page.table_objects %}
 <tr>
  {% for attr in object.attributes %}
  <td>
   <center>{{ attr }}</center>
  </td>
  {% endfor %}
 </tr>
 {% endfor %}
</table>
