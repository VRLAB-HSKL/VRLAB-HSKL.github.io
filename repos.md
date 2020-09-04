# Standard-Struktur der Repositories
Wir verwenden Branches in git, um verteilt an unseren Projekte zu arbeiten. Dabei verwenden wir *mindestens* die beiden Branches
1. master
1. develop

Neue Entwicklungen finden prinzipiell *immer* im develop- oder einem weiteren von uns angelegten Branch statt. Wir arbeiten dabei lokal und machen in regelmässigen Abständen ein push
auf den von uns verwendeten branch. Sind die Änderungen in einem Branch, der nicht develop oder master ist stabil und getestet, dann wird dieser Branch mit Hilfe eines merge mit develop
synchronisiert.

Sobald wir ein neues Release definiert haben wird develop durch ein Merge mit master synchronisiert. Wir erzeugen ein Release (Tag, ...) in master.
