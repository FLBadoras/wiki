---
short_name: sealife
title: Meereswesen
layout: default
creatures:
  - name: Eisenaxt
    found_by: motrellin
    location: Hauptinsel (Hafen)
  - name: Feuerfisch
    found_by: motrellin
    location: Hauptinsel (Hafen)
  - name: Garnele
    found_by: motrellin
    location: Hauptinsel (Hafen)
  - name: Holzhacke
    found_by: motrellin
    location: Hauptinsel (Hafen)
  - name: Kugelfisch
    found_by: motrellin
    location: Hauptinsel (Hafen)
  - name: Lederjacke
    found_by: motrellin
    location: Hauptinsel (Hafen)
  - name: Muschel
    found_by: motrellin
    location: Hauptinsel (Hafen)
  - name: Roher Kabeljau
    found_by: motrellin
    location: Hauptinsel (Hafen)
  - name: Roher Lachs
    found_by: motrellin
    location: Hauptinsel (Hafen)
  - name: Sardelle
    found_by: motrellin
    location: Hauptinsel (Hafen)
  - name: Seetang
    found_by: motrellin
    location: Hauptinsel (Hafen)
    found_by: motrellin
    location: Hauptinsel (Hafen)
  - name: Tintenfisch
    found_by: motrellin
    location: Hauptinsel (Hafen)
  - name: Tilapia
    found_by: motrellin
    location: Hauptinsel (Hafen)
---
# {{ page.title }}

Viele verschiedene Wesen können z.B. am Hafen geangelt werden. Im Folgenden
entsteht eine Liste an geangelten Wesen, die gerne erweitert werden darf.

{: .contributing }
Die Meereswesen werden alphabetisch sortiert, bitte beim Ergänzen beachten!

<table>
	<tr>
		<th>
			Meereswesen
		</th>
		<th>
			Gefunden von
		</th>
		<th>
			Fundort
		</th>
	</tr>
	{% for creature in page.creatures %}
	<tr>
		<td>
			<center>{{ creature.name }}</center>
		</td>
		<td>
			<center>{{ creature.found_by }}</center>
		</td>
		<td>
			<center>{{ creature.location }}</center>
		</td>
	</tr>
	{% endfor %}
</table>
