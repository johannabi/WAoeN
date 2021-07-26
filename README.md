# WAoeN
Wortliste der Assoziationen zur ökologischen Nachhaltigkeit

WAoeN ist eine Wortliste bestehend aus 1800 Wörtern, die mit ökologischer Nachhaltigkeit assoziiert werden können. Die Wortliste basiert auf einer Wortliste des Umweltbundesamtes (UBA/BMU 2021) und wurde mithilfe eines [Word2Vec-Modells](https://devmount.github.io/GermanWordEmbeddings/) und [GermaNet](https://uni-tuebingen.de/fakultaeten/philosophische-fakultaet/fachbereiche/neuphilologie/seminar-fuer-sprachwissenschaft/arbeitsbereiche/allg-sprachwissenschaft-computerlinguistik/ressourcen/lexica/germanet-1/) angereichert. Jedem Wort wurde zusätzlich ein Assoziations-Score zugewiesen, der angeben soll, wie stark (=5) bzw. schwach (=1) die Assoziation zu ökologischer Nachhaltigkeit ist. 

Die .csv-Datei ist wie folgt aufgebaut:
|Begriff|Quelle|Assoziations-Score|
|:---:|:---:|:---:|
|Klimaschutz|UBA Wortliste|5.0|
|Naturschutzbund|GermaNet|4.666666666666667|
| ... | ... | ...|

Die WAoeN wurde entwickelt, um in Azubi-Stellenanzeigen Referenzen auf ökologische Nachhaltigkeit zu identifizieren. Nähere Informationen zu diesem Projekt finden sich in [dieser Präsentation](https://www.agbfn.de/dokumente/pdf/AGBFN_Nachhaltigkeit_Praes_3.a.2_Binnewitt_Schnepf_Attraktivitaet.pdf). 


## Literatur
Bauer, Stefanie; Thobe, Ines; Wolter, Marc Ingo; Helmrich, Robert; Schandock, Manuel; Janser, Markus; Röttger, Christof; Liesen, Andrea; Mohaupt, Franziska (2021): Qualifikationen und Berufe für den Übergang in eine Green Economy. In: UBA, BMU (Hrsg.): Reihe Umwelt, Innovation, Beschäftigung XX/2021, Dessau-Roßlau, Berlin (im Erscheinen)
