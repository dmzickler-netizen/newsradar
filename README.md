# Newsradar

Datenquelle für die Seite **Newsradar** auf [danielzickler.com/newsradar](https://danielzickler.com/newsradar).

Die Datei `news.json` enthält ausschließlich Meldungen, die Dr. Daniel Zickler in seinem Newsradar ausdrücklich für den Blog freigegeben hat. Sie wird automatisch aktualisiert; bitte nicht von Hand bearbeiten.

## Aufbau von `news.json`

| Feld | Inhalt |
|---|---|
| `aktualisiert` | Zeitpunkt des letzten Abgleichs (ISO 8601) |
| `rubriken` | Liste der Rubriken mit `key` und Anzeigename `name` |
| `meldungen` | Freigegebene Meldungen, neueste zuerst |

Jede Meldung hat die Felder `id`, `rubrik` (ein `key` aus `rubriken`), `titel`, `kurz` (Zusammenfassung), `einordnung`, `datum` (Datum der Quelle, JJJJ-MM-TT), `quellen` (Liste aus `name`, `url`, `datum`) und `freigegeben_am`.

Die Zusammenfassungen sind KI-gestützt vorbereitet. Maßgeblich ist immer die verlinkte Originalquelle. Die Inhalte ersetzen keine ärztliche Beratung im Einzelfall.
