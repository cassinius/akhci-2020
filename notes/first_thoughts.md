Bernd Malle, [05.03.20 20:42]
manche Modelle liefern gar nicht so schlechte Ergebnisse (doc2vec), schau mir jetzt noch starspace an, das soll fuer alle moeglichen Entities gut sein (nicht nur Text)

Bernd Malle, [05.03.20 20:42]
das Dumme an den reinen Text-Embeddings ist, dass ich nicht weiss wie ich verschiedene Diskriminanten unterschiedlich gewichten kann

Bernd Malle, [05.03.20 20:43]
bspw. Mann/Frau ist bei Kleidung ein viel staerkeres Signal fuer eine Grenze als gruen/blau

Bernd Malle, [05.03.20 20:44]
aber das weiss das embedding scheinbar nicht, da es ja allgemein Sprache lernt

Nicola Giuliani, [05.03.20 20:44]
sollte das nicht impliziet gemodellt sein wenn du es auf einem entsprechendem datensatz trainierst?

Bernd Malle, [05.03.20 20:46]
sollte man meinen, liefert aber bei den 5.8 Mio flipkart produkten immer wieder Falsches

Bernd Malle, [05.03.20 20:49]
ist bei einem generellen e-commerce Datensatz auch schwer, weil Mann/Frau bei Elektronikprodukten keine Rolle spielt z.b.... die Frage ist wie man diese (starren) Regeln in das Modell einarbeitet... aber vermutlich gar nicht..

Bernd Malle, [05.03.20 20:49]
eher Transfer-learning von einem generischen Modell auf unterschiedliche Spezial-Corpora, was meinst?

Bernd Malle, [05.03.20 20:51]
oder - was ich sexier finde, weil zur Laufzeit ohne viel Processing power &| Speicher machbar - aus dem Modell einen lokalen Similaritaetsgraphen ziehen, der je nach Produkt-Domain noch spezielle Regeln eingebaut bekommt - der Recommender lauft dann relativ 'starr', aber dafuer kontrollierbar, ab

Bernd Malle, [05.03.20 20:51]
[In reply to Bernd Malle]
das ist halt sau-teuer....

Nicola Giuliani, [05.03.20 20:52]
aber wahrscheinlich einfacher

Bernd Malle, [05.03.20 20:53]
Du meinst code-maessig, weil du nur das Modell laden & den spezifischen Corpus hinzufuegen musst?

Nicola Giuliani, [05.03.20 20:56]
ja und einfacher ergebnisse zu bekommen. die andere sache ist glaub ich schwieriger zum laufen zu bringen. was ist ein passender lokaler grah? welche speziellen regeln baust du ein? usw..

Bernd Malle, [05.03.20 20:58]
wuerde sagen ein lokaler graph ist erstmal ein subgraph des store-similarity-graphen... was die Regeln betrifft, die muessen aus den Rueckmeldungen der User kommen - was akzeptiert wird und was nicht - fragt sich ob man hier ein gutes Startset bekommen kann

Bernd Malle, [05.03.20 20:59]
sobald genuegend feedback da ist, koennte man das ins zugrundeliegende Datenset rueck-einbauen (weiss aber noch nicht wie) und damit das NN fuettern... naja viel coole Arbeit

Bernd Malle, [05.03.20 20:59]
ich denke ich werde ein paar solche Experimente aufstellen - die sollen die Studis dann mit mir durchfuehren.. eh eine coole Sache

Bernd Malle, [05.03.20 21:02]
... da fallt sogar ein gutes praktisches "interactive ML" paper ... oder "graph enrichment via domain embeddings"... oder...
