ISISS Matese — WebXR realtà mista (v3)
======================================

File: index.html + logo.png (stessa cartella, sito HTTPS)

Comportamenti
- Compare da solo davanti a te; vola in autonomia, sempre rivolto verso di te.
- TI VIENE INCONTRO: ogni 9-16 s, se sei lontano, si avvicina a circa 1 m e ti ruota attorno curioso.
- SI SCANSA: se ti avvicini (o avvicini la mano) velocemente fa uno scatto di sorpresa e si sposta di lato.
- ARRETRA CON GARBO: se ti avvicini piano resta fermo, ma sotto i 55 cm si sposta indietro.
- ANNUSA LA MANO: tieni il controller/mano quasi fermo vicino a lui e viene a 30 cm dalla mano.
- SI POSA: si appoggia su tavoli e mensole rilevati (altezza 30-140 cm) per qualche secondo, con l'ombra sul piano.
- TI SALUTA: se lo fissi per ~1,3 s fa un saltello.
- TOCCO: trigger o pizzico = salto e giro.
- Evita pareti e mobili (plane-detection) e resta dentro i confini della stanza.

Per pareti/tavoli sul Quest: fai la Configurazione spazio (Impostazioni > Fisico).
Parametri regolabili nel blocco CFG di index.html.

NOVITÀ v4 — Programmi di studio
- File nuovi: programma-3-4-anno.jpg e programma-5-anno.jpg (tienili accanto a index.html).
- La prima volta che il logo ti viene incontro, ti presenta da solo i due pannelli (3°-4° e 5° anno).
- In qualsiasi momento: punta il logo col controller (o pizzica con le mani) e premi il trigger = apre/chiude i pannelli.
- Punta un pannello e premi = lo ingrandisce; premi di nuovo = torna normale.
- I pannelli escono dal logo, restano nella stanza e si girano sempre verso di te; si chiudono da soli dopo 90 s o se ti allontani.

NOVITÀ v5 — Effetto wow
- Logo con spessore 3D e tre sfere luminose in orbita (arancio, azzurro, rosa).
- Scia di scintille colorate mentre si muove; esplosioni di coriandoli quando compare, quando lo tocchi, quando si spaventa e quando apre i pannelli.
- Pannelli olografici: riflesso luminoso che li attraversa, si inclinano verso dove punti.
- Suoni sintetizzati (nessun file audio): arpeggio all'apparizione, tintinnio all'apertura, click, "boop" quando si scansa. Servono volume attivo sul visore.

NOVITÀ v6 — Quiz, fumetti e voce
- QUIZ "Quale indirizzo fa per te?": quando i pannelli sono aperti compare sotto di loro il pulsante "Quiz".
  Punta una risposta col controller e premi il trigger (o pizzica con le mani). 4 domande, risultato ITI / ITA / IPSEOA
  con coriandoli; "Rifai il quiz" per il prossimo visitatore, "Chiudi" per tornare ai pannelli.
  Domande e descrizioni sono nel blocco TRACKS / QUIZ di index.html: modificale con i testi ufficiali della scuola.
- FUMETTI: il logo parla (saluto iniziale, quando lo fissi, quando si spaventa, quando annusa la mano, quando apre i programmi).
- VOCE (facoltativa): in CFG metti voice: true per fargli leggere i fumetti con la sintesi vocale italiana (se il browser la supporta).

NOVITÀ v7 — Gioco "Colpisci il logo"
- Apri i pannelli (tocca il logo) e premi "Gioco: colpisci il logo!" (sotto il pulsante Quiz).
- 30 secondi: ogni trigger lancia una pallina colorata nella direzione del controller (o pizzico con le mani).
  Ogni colpo = 1 punto; il logo fa un salto, si scansa e vola più veloce. Punteggio e tempo restano davanti a te.
- A fine partita il logo commenta il risultato e mostra il record della sessione.
- Durata e velocità si cambiano in index.html (GAME_SECS, e la velocità 9 m/s in shoot()).
