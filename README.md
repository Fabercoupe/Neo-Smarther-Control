# Neo-Smarther-Control
Card avanzata e minimalista per termostati BTicino Smarther su Home Assistant, con grafico integrato e animazioni CSS
Una card personalizzata per Home Assistant (Lovelace) dal design moderno e asimmetrico, progettata specificamente per termostati (testata su BTicino Smarther).

## Caratteristiche
- **Display Temperatura Dinamico:** Visualizzazione grande della temperatura attuale con dettaglio dei decimali.
- **Grafico Integrato:** Sfondo con mini-grafico della temperatura delle ultime 12 ore.
- **Barra di Stato Animata:** Una barra verticale che si anima (v-scroll) quando il riscaldamento è attivo.
- **Pannello di Controllo Laterale:** Pulsanti rapidi per alzare/abbassare il setpoint e accendere/spegnere il sistema.

## Screenshot
![Anteprima Card](Card%20Termostato%20Bticino1.jpg)

## Requisiti
Per far funzionare questa card, devi aver installato i seguenti plugin tramite HACS:
1. [button-card](https://github.com/custom-cards/button-card)
2. [mini-graph-card](https://github.com/kalkih/mini-graph-card)
3. [card-mod](https://github.com/thomasloven/lovelace-card-mod)

## Installazione
1. Assicurati di avere i requisiti sopra elencati.
2. Copia il codice contenuto nel file `card.yaml` di questa repository.
3. Crea una nuova card "Manuale" nella tua dashboard di Home Assistant.
4. Incolla il codice e sostituisci `climate.smarther_thermostat_heater_cooler` con l'entità del tuo termostato.
