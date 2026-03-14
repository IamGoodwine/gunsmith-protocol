# Mark O'Connell — Gunsmith Protocol

> Minigame browser per mobile tratto dalla serie a fumetti **I Tre Fratelli**

---

## Il personaggio

**Mark O'Connell** è un pistolero cyberpunk con capelli bianchi e un occhio cibernetico destro che ospita un'AI integrata: **AIò**. Tinkerer sbruffone in estasi da combattimento, parla con AIò ad alta voce senza accorgersene. AIò risponde con fredda precisione analitica. Nessuno dei due si ascolta davvero.

---

## Il gioco

Arena laterale a ondate. Nemici avanzano da entrambi i lati, Mark è al centro. Tap a sinistra o destra per sparare in quella direzione.

### Meccaniche principali

- **5 livelli di arma** — potenziabili a ogni fine ondata tramite combinazione di materiali
- **Livello Leggendario (lv4)** — attiva l'OVERDRIVE: 12 secondi di raggio automatico e Mark in completa estasi da combattimento
- **Granata al Plasma** — con cooldown, arma tattica per situazioni critiche
- **Sistema Crafting** — combina due materiali negli slot A e B, rischia l'esplosione o sali di livello
- **Dialogo dinamico** — AIò commenta, Mark ignora. Durante l'overdrive Mark non si ferma più
- **Modale codec** — transizione con effetto glitch cyberpunk tra ogni ondata

### Progressione arma

| Livello | Tipo | Effetto |
|---------|------|---------|
| Lv 0 | Fucile Base | Proiettile singolo |
| Lv 1 | Fucile Potenziato | Proiettile + glow |
| Lv 2 | Upgrade | Doppio proiettile |
| Lv 3 | Raggio | Beam continuo (hold) |
| Lv 4 ⚡ | LEGGENDARIO | OVERDRIVE automatico 12s |

---

## Tecnologia

- Single HTML file — nessuna dipendenza esterna
- Canvas 2D per il rendering dell'arena
- Mobile-first, ottimizzato per Chrome Android
- Delta-time based movement (velocità costante a qualsiasi refresh rate)
- Sprite pixel art di Mark disegnati via Canvas API con variazioni per livello

---

## Come giocare

Scarica `index.html` e aprilo in Chrome su Android (o qualsiasi browser moderno). Nessuna installazione, nessun server necessario.

---

## Crediti

Concept, design e direzione creativa: **Marco Buonvino**
Sviluppo e implementazione: **Claude** (Anthropic)

Personaggi e universo narrativo di *I Tre Fratelli* © Marco Buonvino 

---

*"Il 67% delle statistiche è inventato. Anche questa." — Mark O'Connell*
