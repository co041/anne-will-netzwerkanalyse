Codebuch – Netzwerkanalyse der Anne-Will-Sendungen 500–503

1. Edgelist

| Variable | Definition und Codierung |
|---|---|
| from | Definiert den Ausgangsknoten einer gerichteten Beziehung. |
| to | Definiert den Zielknoten einer gerichteten Beziehung. |
| relationship | 1 = Gastteilnahme, 2 = Parteizugehörigkeit. |

2. Nodelist

| Variable | Definition und Codierung |
|---|---|
| `id` | Eindeutige Identifikationsnummer eines Knotens. Die IDs werden sowohl in der Nodelist als auch in der Edgelist verwendet. |
| `name` | Name oder Bezeichnung des jeweiligen Knotens. Bei Personen wird der vollständige Name, bei Sendungen die Folgenummer und bei Parteien die vollständige Parteibezeichnung angegeben. |
| `type` | Definiert die Art des Knotens: 1 = Person, 2 = Sendung, 3 = Partei. |
| `party` | Erfasst die Parteizugehörigkeit einer Person. Mögliche Ausprägungen: SPD, CDU, LINKE, FDP und GRUENE. |
| `sector` | Erfasst das berufliche beziehungsweise gesellschaftliche Tätigkeitsfeld einer Person. Mögliche Ausprägungen: Politik, Wissenschaft, Journalismus, Diplomatie, Militär und Literatur. |
| `country` | Erfasst das Land, dem die berufliche oder politische Funktion einer Person zum Untersuchungszeitpunkt zugeordnet wird. |

3. Allgemeine Codierregeln

Jede Person, Sendung und Partei wird nur einmal in der Nodelist aufgeführt.

Wiederholte Auftritte einer Person in mehreren Sendungen werden in der Edgelist durch jeweils eigene Beziehungen erfasst.

Die IDs müssen eindeutig sein und in beiden Datensätzen identisch verwendet werden.

Nicht zutreffende beziehungsweise nicht vorhandene Angaben werden als leere Felder eingetragen.

Die Zuordnung zu Tätigkeitsfeldern und Ländern erfolgt anhand der beruflichen beziehungsweise politischen Funktion zum Untersuchungszeitpunkt.
