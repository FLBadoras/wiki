---
title: Support
layout: default
permalink: /support
nav_order: 4
---
# {{ page.title }}

Du kommst einmal nicht weiter, trotz aller Informationen im Wiki oder unter
`/hilfe`? Kein Problem, dafür steht dir unser kompetentes Support-Team gerne zur
Seite.

Nebenbei hat unser Support auch die Aufgabe, über die Einhaltung des
Regelwerks zu wachen. Hierbei kommt ein spezielles Punktesystem zur Geltung.

## Helfer

Die Hemmschwelle ist zu groß, den Support zu kontaktieren und du kommst
einmal nicht weiter und brauchst schnell greifbare und kompetente Hilfe?

Dann kannst du hierfür unsere Helfer\*innen aufsuchen.
Sie beantworten viele deiner Fragen und unterstützen dich gerne mit all ihrer
Erfahrung und ihrem Wissen.

Mit ein paar netten Worten verraten sie vielleicht
auch dir ihre Tipps und Tricks, um im Spiel gut voranzukommen.

**Wichtig**: Bei Regelverstößen und Fragen, die über das simple Spielerlebnis
hinausgehen, kann _nur_ der Support selbst helfen.

## Kontaktmöglichkeiten

Unser Support kann auf verschiedenen Wegen erreicht werden:

- Auf unserem Discord findest du den Channel "#fragen-und-hilfe" im Bereich
  Support.
- Auf unserem Discord findest du den Channel "#supportticket" im Bereich
  Support.
- Ingame kannst du den Befehl [`/h`](/commands/h) nutzen. Mehr Informationen
  hierzu findest du [hier](/systems/chat/#hilfe-chat).

{: .note }
Generell empfiehlt es sich, erst die Möglichkeiten des Communitysupports zu
nutzen. Bei vielen Fragen können vermutlich andere Spieler\*innen (schneller!)
helfen.

## Punktesystem

Regelverstöße können mit sogenannten Verwanungspunkten geahndet werden. Unser
spezielles Punktesystem hat eine variable Spanne, wobei wir uns hier aber
grundsätzlich nach einem vordefiniertem internen Richtwert orienterieren. Es
kommen folgende Limite für unsere Verwarnungspunkte zur Geltung:

- Bei einer aktiven Punktzahl von 50 Punkten gibt es eine mündliche Verwarnung
  in einem persönlichen Gespräch.
- Bei einer aktiven Punktzahl von 70 Punkten gibt es einen 24h Ban.
- Bei einer aktiven Punktzahl von 100 Punkten gibt es einen permanenten Ban.

Verwarnungen haben generell ein Ablaufdatum von 4 Monaten. **Achtung**: Ein
permanenter Ban wird natürlich _nicht_ entfernt, weil eine Verwarnung nach 4
Monaten abgelaufen ist. Schließlich ist der Ban permanent!

## Unser Support- und Helfenden-Team

{% for team_member in site.team_members %}
{% if team_member.section == "support" %}
{: .text-blue-000 }
{% elsif team_member.section == "help" %}
{: .text-grey-dk-000 }
{% else %}
{% continue %}
{% endif %}
<h3> {{ team_member.name }} - {{ team_member.position }} </h3>
{{ team_member.content | markdownify }}
{% endfor %}
{% for helper in page.helpers %}
{: .text-blue-000 }
<h3> {{ team_member.name }} - {{ team_member.position }} </h3>
{{ team_member.content | markdownify }}
{% endfor %}
