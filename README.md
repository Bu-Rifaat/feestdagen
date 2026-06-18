# Feestdagen Dashboard

Widget voor het Dashboard van het urenregistratiesysteem die de eerstvolgende
feestdag(en) in Nederland toont.

## API

[Nager.Date](https://date.nager.at/Api) — `GET /api/v3/NextPublicHolidays/NL`

Geeft de resterende feestdagen van het lopende jaar terug, gesorteerd op
datum. De eerste datum in de lijst is de eerstvolgende feestdag; als er
meerdere feestdagen op diezelfde datum vallen worden die ook getoond.

## Gebruik

Open `index.html` in de browser, of plak de `<div id="feestdagenWidget">`
samen met het bijbehorende `<script>` rechtstreeks in de bestaande
Dashboard-pagina van het urenregistratiesysteem.

## Git geschiedenis

1. Dashboard kaart skeleton
2. API integratie + styling
