---
short_name: sealife
title: Meereswesen
layout: default

table_headers:
  - Meereswesen
  - Gefunden von
  - Fundort
table_objects:
  - attributes:
      - Feuerfisch
      - motrellin
      - Hauptinsel (Hafen)
  - attributes:
      - Garnele
      - motrellin
      - Hauptinsel (Hafen)
  - attributes:
      - Seetang
      - motrellin
      - Hauptinsel (Hafen)
  - attributes:
      - Tintenfisch
      - motrellin
      - Hauptinsel (Hafen)
  - attributes:
      - Tilapia
      - motrellin
      - Hauptinsel (Hafen)
---
# {{ page.title }}

Viele verschiedene Wesen können z.B. am Hafen geangelt werden. Im Folgenden
entsteht eine Liste an geangelten Wesen, die gerne erweitert werden darf.

{: .contributing }
Die Meereswesen werden alphabetisch sortiert, bitte beim Ergänzen beachten!

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
