ISISS Matese — WebXR realtà mista (versione 3)
==============================================

File nella cartella: index.html, logo.png, programma-anni-3-4.jpg, programma-anno-5.jpg
Pubblica tutta la cartella su HTTPS e aprila dal browser del visore (WebXR immersive-ar).

Novità
- Le due tavole dei programmi sono ora INDIPENDENTI dal logo: compaiono ferme nella stanza,
  a circa 3 m davanti a te, affiancate e leggermente ruotate verso di te, con cornice al neon,
  alone luminoso, fascio di luce dal pavimento e lieve fluttuazione. Il logo non le attraversa.
- Interazioni solo per vicinanza (nessun pulsante, nessun grilletto):
  * Mano/controller a ~35 cm dal logo: il logo si ferma, l'alone si illumina e le materie si allargano.
  * Tocco del logo (~14 cm): giro su sé stesso, scintille colorate, onda luminosa, vibrazione
    del controller e cambio di anno (3°-4° <-> 5°).
  * Tocco di una materia in orbita (~10 cm): si apre la scheda con i contenuti, resta aperta
    finché la mano è vicina.
  * Mano vicina a una tavola: la tavola si ingrandisce e si illumina.
- Restano lo sguardo (materia fissata per 0,8 s), la comparsa automatica, il movimento lento,
  la distanza personale e il rilevamento delle superfici.
- Con le mani libere (hand tracking) vale la punta dell'indice; con i controller, il punto anteriore.

Parametri regolabili: oggetto CFG (logo) e funzioni buildStage/placeStage (tavole) in index.html.
