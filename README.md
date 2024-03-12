Email dei componenti:

- michele.olivieri3@studio.unibo.it
- keegancarlo.falcao@studio.unibo.it
- junkai.ji@studio.unibo.it
- pierdavide.elia@studio.unibo.it

il gruppo si pone come obiettivo quello di realizzare un'applicazione orientata agli appassionati di coltivazione di peperoncino, che permetta di gestirne i principali aspetti, come ricerca informazioni, calcoli temperatura, stime necessità irrigazione, graficazione risultati.

Funzionalità minimali ritenute obbligatorie:

- Creazione di un livello per classe di ostacoli
- implementazinoe di ostacoli statici e dinamici: pits, spikes, walls, saws (coins)
- gestione di fine livello
- personaggio giocabile in gradi di muoversi in due direzioni e salto
- gestione eventi di collisioni
- grafica minimale

Funzionalità opzionali:

- interfaccia di selezioni dei livelli (menu)
- salvataggio dello stato gioco
- multiplayer
- gestione di ostacoli dinamici (springs)
- creazione livello tutorial
- score (death counter), coins

"Challenge" principali:

- gestione accurata della dinamica tra il personaggio e gli ostacoli
- assicurarsi che gli elementi di gioco siano facilmente estendibili per consentire aggiunte future
- sviluppare un'interfaccia utente (GUI) appropriata
- dinamicità degli ostacoli
- triggers: (button, warping, controls)

Suddivisione del lavoro:

- Olivieri: player , gravità,
- Falcao: gestione IO,
- Elia:
- Ji:

menu, ambiente e mappa, personaggio, gravità, movimento e controlli, javaFx, gameEngine, salvataggio, score, multyplayer e livelli cooperativi, tutorial

oggetto: pits, spikes, walls, saws (coins), button, warping, controls, springs

entità
posizione
velocità

player
...

obstacle

Falcao => Obstacle (No Die) : walls, platforms, (2/3)coins, springs -> 7/10

Michele => Obstacle (Die) : spikes, saws, (1/3)coins -> 7/10

Ji => Trigger : button, controls, warps -> 7/10

Falcao => I/0 -> 4/10

Elia => Game Engine -> 5/10

Michele => Player -> 4/10

Michele => Gravità -> 4/10

Elia => Game World -> 6/10

Falcao => Trasformation -> 7/10

Ji => Collisione -> 6/10

Elia => Salvataggio e Score -> 2/10

Ji => Menu -> 3/10
