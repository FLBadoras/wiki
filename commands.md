---
title: Commands
layout: default
permalink: /commands
nav_order: 2
---

# Commands

Im Folgenden findet ihr eine Auflistung aller Commands auf Farmlife: Badoras
(ohne Garantie auf Vollständigkeit). Wir verwenden dabei folgende Konvention:

- Notwendige Argumente werden mit geschweiften Klammern dargestellt.
  Bsp.: `{Argument}`
- Optionale Argumente werden mit eckigen Klammern dargestellt.
  Bsp.: `[Argument]`

{: .contributing }
Weitere Commands können unter
[`_commands`](https://github.com/FLBadoras/wiki/tree/main/_commands) ergänzt
werden!

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
 {% for command in site.commands %}
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
