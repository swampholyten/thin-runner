Email dei componenti:

- michele.olivieri3@studio.unibo.it
- keegancarlo.falcao@studio.unibo.it
- junkai.ji@studio.unibo.it
- pierdavide.elia@studio.unibo.it

il gruppo si pone come obiettivo quello di realizzare un'applicazione orientata agli appassionati di coltivazione di peperoncino, che permetta di gestirne i principali aspetti, come ricerca informazioni, calcoli temperatura, stime necessità irrigazione, graficazione risultati.

Funzionalità minimali ritenute obbligatorie:

- Creazione dei livelli per classe di ostacoli
- implementazinoe di ostacoli statici e dinamici: pits, spikes, walls, saws (coins)
- gestione di fine livello
- personaggio giocabile in grado di muoversi in due direzioni e salto
- gestione eventi di collisioni
- interfaccia di selezioni dei livelli (menu)
- salvataggio dello stato gioco
- grafica minimale

Funzionalità opzionali:

- creazione livello tutorial
- multiplayer
- gestione di ostacoli dinamici (springs)
- score (death counter)

"Challenge" principali:

- gestione accurata della dinamica tra il personaggio e gli ostacoli
- assicurarsi che gli elementi di gioco siano facilmente estendibili per consentire aggiunte future
- sviluppare un'interfaccia utente (GUI) appropriata
- dinamicità degli ostacoli

Suddivisione del lavoro:

- Olivieri: lethal obstacles, player and gravity
- Falcao: harmless obstacles, trasformation and I/0
- Elia: game loop, game world, save and score
- Ji: triggers, collision and menu

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
