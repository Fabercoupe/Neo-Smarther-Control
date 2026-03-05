# ITALIANO

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


---

## 💖 Sostieni lo sviluppo

Se trovi utili le mie repository e vuoi sostenere il mio lavoro, puoi offrirmi un caffè tramite PayPal! Ogni contributo è molto apprezzato.

[![Donate with PayPal](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.me/Fabercoupe)

---

# INGLESE

# Neo-Smarther-Control
Advanced and minimalist card for BTicino Smarther thermostats on Home Assistant, featuring integrated graphs and CSS animations.

A custom Home Assistant (Lovelace) card with a modern, asymmetrical design, specifically crafted for thermostats (tested on BTicino Smarther).

## Features
- **Dynamic Temperature Display:** Large current temperature view with precise decimal detail.
- **Integrated Graph:** Background mini-graph showing temperature history for the last 12 hours.
- **Animated Status Bar:** A vertical bar that animates (v-scroll) when heating is active.
- **Side Control Panel:** Quick buttons to increase/decrease setpoint and toggle system power.

## Screenshot
![Card Preview](Card%20Termostato%20Bticino1.jpg)

## Requirements
To use this card, you must have the following plugins installed via HACS:
1. [button-card](https://github.com/custom-cards/button-card)
2. [mini-graph-card](https://github.com/kalkih/mini-graph-card)
3. [card-mod](https://github.com/thomasloven/lovelace-card-mod)

## Installation
1. Ensure you have the requirements listed above.
2. Copy the code from the `card.yaml` file in this repository.
3. Create a new "Manual" card in your Home Assistant dashboard.
4. Paste the code and replace `climate.smarther_thermostat_heater_cooler` with your thermostat entity ID.

---

## 💖 Support the Development

If you find my repositories useful and would like to support my work, feel free to buy me a coffee via PayPal! Every contribution is greatly appreciated and helps me keep the projects alive.

[![Donate with PayPal](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.me/Fabercoupe)

---
