---
title: Commands
layout: default
permalink: /commands
---

# Commands

Im Folgenden findet ihr eine Auflistung aller Commands auf Farmlife: Badoras
(ohne Garantie auf Vollständigkeit). Wir verwenden dabei folgende Konvention:
- Notwendige Argumente werden mit geschweiften Klammern dargestellt. Bsp.: `{Argument}`
- Optionale Argumente werden mit eckigen Klammern dargestellt. Bsp.: `[Argument]`

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
			<center><pre>{{ command.aliases }}</pre></center>
		</td>
	</tr>
	{% endfor %}
</table>
