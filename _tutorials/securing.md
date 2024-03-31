---
short_name: lwc
title: Sicherungen (LWC)
layout: default
---
# Sicherungen

Für die Sicherung von privaten Kisten und anderen Dingen (Türen, etc.) nutzen
wir LWC. Das System ist vielen Spielern seit vielen Jahren wohlbekannt und
bietet alles, was man zum Schützen seiner Privatsachen benötigt. Wir haben die
wichtigsten Befehle auf dem Server mit deutschen Befehlen ersetzt, dennoch
funktionieren auch die Standard-LWC-Befehle noch.

## Befehle
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
	{% assign lwc_cmds = site.commands | where: 'system', page.short_name %}
	{% for command in lwc_cmds %}
	<tr>
		<td>
			<center><pre>{{ command.command }}</pre></center>
		</td>
		<td>
			<center>{{ command.content }}</center>
		</td>
		<td>
			<center><pre>{{ command.aliases }}</pre></center>
		</td>
	</tr>
	{% endfor %}
</table>

## Weiterführende Links

Hier geht es zu allen
[LWC-Standard-Befehlen](https://github.com/pop4959/LWCX/wiki/Commands).
