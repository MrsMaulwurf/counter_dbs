# counter_dbs
Automatisierte Auswertung von COUNTER-Nutzungsstatistiken für die Deutsche Bibliotheksstatistik (DBS)

Ausgangsproblem

Etwa 250 wissenschaftliche Bibliotheken nehmen an der Deutschen Bibliotheksstatistik teil und werten dafür u. a. Nutzungsstatistiken ihrer E-Medien aus. Die DBS gibt sehr genau vor, welche Metriken für die Zugriffszahlen auf E-Books, E-Journals und Datenbanken verwendet werden. Die Statistiken werden von den jeweiligen Anbietern bereits größtenteils im standardisierten COUNTER-Format geliefert. Die Auswertung läuft in vielen Bibliotheken dennoch händisch, d. h. die Statistiken werden (i. d. R. als Excel-Datei) einzeln heruntergeladen und anschließend ebenfalls einzeln bearbeitet. Dafür werden die jeweils benötigten Metriken nach Vorgabe der DBS aus der Excel extrahiert und summiert. Eine Statistik der E-Book-Zugriffe z. B. des Portales Springer Link umfasst dabei an der TH-Bibliothek Aschaffenburg allein 30.000 Einträge. Anschließend wird die Summe der einzelnen Statistik mit den Summen der anderen Einzelstatistiken des gleichen Typs (E-Book-, E-Journal- oder Datenbankzugriff) zusammengeführt, um die in der DBS geforderten Gesamtzahl an E-Book- und E-Journal-Downloads sowie Suchen in Datenbanken zu erfassen. Dieses Vorgehen benötigt in einer kleinen Hochschulbibliothek wie der TH Aschaffenburg allein für die Erfassung der E-Medien-Nutzungsstatistik bereits 2-3 Arbeitstage.

Projektidee

Ein Script, das die oben beschriebene Auswertung automatisiert. 

