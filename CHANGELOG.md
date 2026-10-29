# Novità

Tutte le modifiche di rilievo, versione per versione. Gli eseguibili si scaricano dalla
pagina [Releases](https://github.com/rastlien78/SC-Radar-Signal/releases).

## [1.1.0] — 2026-10-29

### Nuovo
- **Luogo di estrazione** (facoltativo): scegli dove stai minando (`Tools → Luogo di estrazione`,
  anche in Impostazioni) e l'app mostra solo le rocce che si trovano lì. Se nel luogo scelto la
  firma non corrisponde a niente, ti dice dove altro corrisponde.
- **Calibrazione della zona di lettura con un solo schermo** (`Tools → Calibra ROI dal gioco`):
  l'app si riduce a icona, torni in gioco, inquadri una roccia e premi il tasto di scansione;
  il calibratore si apre sopra il gioco con la firma già visibile. Prima l'app fotografava se
  stessa e chi non ha un secondo schermo non poteva calibrare.
  - **Linux**: provato con il gioco.
  - **Windows**: soluzione *probabile*, non ancora provata con il gioco. Se il calibratore non
    compare sopra Star Citizen, segnalalo con il modulo dei bug.

### Corretto
- **Joystick**: assegnando il pulsante, l'app poteva prenderne subito uno a caso senza che
  fosse premuto niente. Succedeva con levette o pulsanti che restano "accesi" (interruttori,
  fermi della manetta). Ora vengono ignorati finché non li rilasci.
- Dopo aver cambiato il pulsante del joystick ogni pressione faceva **due** scansioni.

## [1.0.0] — 2026-10-28

Prima versione pubblica.

### Nuovo
- **Identificazione dalla firma radar**: con un tasto o un pulsante del joystick l'app legge la
  firma sullo schermo e mostra roccia, numero di rocce e tutti i minerali con percentuale,
  qualità e fascia di valore.
- **Riquadro sopra il gioco** con firma letta, rocce possibili e minerali; si sposta dove vuoi
  (`Tools → Sposta riquadro sopra il gioco…`) e si può spegnere.
- **Modalità di estrazione** Automatico / Nave / ROC / A mano: in Automatico, quando una firma
  vale per più tipi di estrazione, le mostra tutte (Nave → ROC → A mano).
- **Dove trovare**: località, rocce, percentuali e qualità di ogni minerale e gemma in
  Stanton, Pyro e Nyx.
- **Calibrazione con un click** della zona di lettura (`Tools → Quick Adjust ROI`).
- Comando da **tastiera** o da **qualsiasi joystick** (anche VIRPIL, WINWING, VKB); il joystick
  viene ritrovato da solo se si scollega e ricollega.
- **Dati di gioco aggiornati automaticamente** a ogni avvio da scunpacked-data.
- **Avviso di nuova versione** all'avvio, con le novità e il link per scaricarla.
- Windows 10/11 e Linux (X11, KDE Plasma su Wayland, wlroots).
