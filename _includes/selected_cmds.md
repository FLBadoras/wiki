<table>
 <tr>
  <th>
   Command
  </th>
  <th>
   Beschreibung
  </th>
  <th>
   Aliases
  </th>
 </tr>
 {% assign selected_commands = site.commands | where: 'system', page.short_name
 %}
 {% for command in selected_commands %}
 <tr>
  <td>
   <center><pre>{{ command.command }}</pre></center>
  </td>
  <td>
   <center>{{ command.description }}</center>
  </td>
  <td>
   {% for alias in command.aliases %}
   <pre>{{ alias }}</pre>
   {% endfor %}
  </td>
 </tr>
 {% endfor %}
</table>
