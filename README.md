Email dei componenti:

- michele.olivieri3@studio.unibo.it
- keegancarlo.falcao@studio.unibo.it
- junkai.ji@studio.unibo.it
- pierdavide.elia@studio.unibo.it

## DESCRIZIONE

Il gruppo si pone come obbiettivo quello di realizzare un platform game chiamato 'Paradox Platformer', un avventura in cui il giocatore esplora diverse mappe affrontando sfide e risolvendo enigmi per raggiungere la porta di endgame. Il cuore del gioco si basa sull'idea innovativa di oggetti, ostacoli e triggers controintuitivi, che mettono il giocatore di fronte a sfide in grado di sovvertire le dinamiche di gioco tradizionali.

Funzionalità minimali ritenute obbligatorie:

- Creazione di un livello per classe di ostacoli
- implementazione di ostacoli statici e dinamici
- gestione di fine livello
- personaggio giocabile in grado di muoversi in due direzioni e salto
- gestione eventi di collisioni tra il personaggio e vari oggetti
- interfaccia di selezioni dei livelli (menu)
- salvataggio dello stato gioco

Funzionalità opzionali:

- Creazione livello tutorial
- Multiplayer
- Aumentare il numero di ostacoli
- Score (death counter)

"Challenge" principali:

- Gestione accurata della dinamica tra il personaggio e gli ostacoli.
- Sviluppo del modifier in grado di regolare le dinamiche di comportamento dei componenti del gioco
- Sviluppare un'interfaccia utente (GUI) appropriata.
- Effetti prodotti dagli ostacoli.
- Creazione del game loop.
- Assicurarsi che gli elementi di gioco siano facilmente estendibili per consentire aggiunte future.

Suddivisione del lavoro:

- Olivieri: Implementazione degli ostacoli di tipo letale, del personaggio principale e della gravità.
- Falcao: Implementazione degli ostacoli di tipo non letale, dei modifier delle entità e della gestione dell'I/O.
- Elia: Implementazione del mondo di gioco, gestione del game loop e salvataggio del gioco.
- Ji: Implementazione degli eventi di collisione tra il personaggio e gli oggetti, dei trigger e del menu.

<!-- menu, ambiente e mappa, personaggio, gravità, movimento e controlli, javaFx, gameEngine, salvataggio, score, multyplayer e livelli cooperativi, tutorial

oggetto: pits, spikes, walls, saws (coins), button, warping, controls, springs

entità
posizione
velocità

player
...

obstacle

Falcao => Harmless Obstacles: walls, platforms, (2/3)coins, springs -> 7/10

Michele => Lethal Obstacles: spikes, saws, (1/3)coins -> 7/10

Ji => Triggers : button, controls, warps -> 7/10

Falcao => I/0 -> 4/10

Elia => Game Engine -> 5/10

Michele => Player -> 4/10

Michele => Gravity -> 4/10

Elia => Game World -> 6/10

Falcao => Trasformation -> 7/10

Ji => Collision -> 6/10

Elia => Save and Score -> 2/10

Ji => Menu -> 3/10 -->
