ISISS Matese — WebXR realtà mista (v2)
======================================

File: index.html + logo.png (stessa cartella, sito HTTPS)

Cosa fa adesso
- Dopo "Entra nella realtà mista" il logo compare DA SOLO davanti a te (nessun controller).
- Vola in autonomia: sceglie una meta, si ferma, riparte, sempre rivolto verso di te.
- Interagisce con la stanza:
  * pareti, tavoli e pavimento rilevati (plane-detection) = ostacoli che evita;
  * resta dentro i confini della stanza (guardian / spazio configurato);
  * ombra sul pavimento che cambia con l'altezza.
- Interagisce con le persone:
  * se ti avvicini (testa) o avvicini una mano/controller, si scansa;
  * premi il trigger (o pizzica con le mani) = salta e fa un giro;
  * se ti allontani troppo, ti raggiunge.

Per farlo "vedere" la stanza sul Meta Quest
- Meta Quest > Impostazioni > Fisico > Configurazione spazio: fai la scansione della stanza
  (su Quest 2 serve per avere pareti/mobili; senza, funziona comunque con i confini guardian).
- Nel Browser: abilita i permessi dello spazio quando richiesto.

Parametri
- Nel blocco CFG in index.html: dimensione, velocità, altezza, distanze di scansamento.
