# Démystification de rulings

# Effets Optionnels "Lorsque"

Cet article concerne le point de règle souvent confus et mal interprété des effets optionnels "Lorsque". 

Avant de commencer, n'oubliez pas de lire le dernier article sur le [SEGOC](3_Effets_Declencheurs.md) !

## Règle fondamentale des effets optionnels "Lorsque"
**Un effet optionnel "Lorsque" ne peut être activé que lorsque sa condition d'activation correspond à "l'une des dernières actions à se dérouler".**

Cette règle explique qu'il est nécessaire d'activer un effet optionnel "lorsque" **exactement** "Lorsque" ce dernier rencontre sa condition d'activation. La difficulté réside dans savoir quand une action est "une des dernières actions à avoir lieu" du point de vue des mécaniques de jeu.

À noter que cette mécanique ne s'applique pas aux effets obligatoires, ni aux effets employant un "Si" plutôt qu'un "Lorsque".

Voyons un premier exemple :

Joueur A contrôle *Main de Feu*. Joueur B active *Typhon d'Espace Mystique* pour détruire une carte Posée, puis chaîne *Interruption de Raigeki*, ciblant *Main de Feu* pour la détruire.
- *Interruption de Raigeki* :

    *Défaussez 1 carte, puis ciblez 1 carte sur le Terrain ; détruisez-la.*
    
- *Main de Feu* :

    *<ins>Lorsque</ins> cette carte en votre possession est détruite par une carte de votre adversaire et envoyée à votre Cimetière : <ins>vous pouvez</ins> cibler 1 monstre qu'il contrôle ; détruisez la cible, puis vous pouvez Invoquer Spécialement 1 "Main de Glace" depuis votre Deck.*

Construction de la Chaîne :

- <ins>Chain Link 1</ins> : *Typhon d'Espace Mystique*

- <ins>Chain Link 2</ins> : *Interruption de Raigeki*

Résolution de la Chaîne :

- <ins>Chain Link 2</ins> résout : *Interruption de Raigeki* détruit *Main de Feu*

- <ins>Chain Link 1</ins> résout : *Typhon d'Espace Mystique* détruit sa cible

L'effet de *Main de Feu* est un "Lorsque" optionnel et sa destruction n'est pas l'une des dernières actions à avoir lieu. Son effet ne peut donc pas être activé dans ce cas de figure.

Cette règle s'applique également pour les cartes Magies et Pièges.

Joueur A active *Gobelin Parvenu* et Joueur B décide de chaîner *Appel de l'Être Hanté*, afin d'Invoquer Spécialement *Dragon Blanc aux Yeux Bleus*. Joueur A a une *Trappe Sans Fond* de Posée sur le Terrain.
- *Lorsque votre adversaire Invoque un ou plusieurs monstres avec min. 1500 ATK : détruisez ces monstres avec min. 1500 ATK, et si vous le faites, bannissez-les.*

Construction de la Chaîne :

- <ins>Chain Link 1</ins> : *Gobelin Parvenu*

- <ins>Chain Link 2</ins> : *Appel de l'Être Hanté*

Résolution de la Chaîne :

- <ins>Chain Link 2</ins> résout : *Appel de l'Être Hanté* invoque *Dragon Blanc aux Yeux Bleus*

- <ins>Chain Link 1</ins> résout : Joueur A pioche sa carte

*Trappe sans fond* emploie un "Lorsque", activer une carte Magie / Piège est optionnel et l'Invocation du monstre n'était pas "l'une des dernières actions à avoir lieu", donc elle ne peut pas être activée, tout comme l'exemple avec *Main de Feu*.

## Plus d'exemples
Jusque-là, il était assez évident de déterminer si la condition d'activation était "l'une des dernières choses à avoir lieu" ou non. Nous allons maintenant nous pencher sur des cas légèrement plus complexes. 

Joueur A active la Magie de Terrain *Ville des Engrenages* :
- *<ins>Lorsque</ins> cette carte est détruite et envoyée au Cimetière : <ins>vous pouvez</ins> Invoquer Spécialement 1 monstre "Rouages Ancients" depuis votre main, Deck ou Cimetière.*

À noter que cet effet déclencheur est un effet optionnel "Lorsque", et donc est capable de manquer de s'activer si sa destruction n'est pas "l'une des dernières actions à avoir lieu".

Supposons que Joueur B chaîne *Typhon d'Espace Mystique* à l'activation de *Ville des Engrenages* du Joueur A sur le Terrain.

- <ins>Chain Link 1</ins> : Activation de *Ville des Engrenages* sur le Terrain

- <ins>Chain Link 2</ins> : *Typhon d'Espace Mystique* ciblant *Ville des Engrenages*

Résolution de la Chaîne :

- <ins>Chain Link 2</ins> résout : *Typhon d'Espace Mystique* détruit *Ville des Engrenages*

- <ins>Chain Link 1</ins> résout : *Ville des Engrenages* résout sur le Terrain (mais elle résout sans effet puisqu'elle vient d'être détruite)

Notons que *Ville des Engrenages* a été détruite, mais son effet sur le Terrain tente tout de même de se résoudre en tant que Chain Link 1. Dans cette situation, le fait que *Ville des Engrenages* "tente de se résoudre" est la dernière chose qui a lieu, tandis que sa destruction ne l'est pas. C'est pourquoi l'effet déclencheur de *Ville des Engrenages* manque de s'activer.

Supposons que Joueur B chaîne *Brouilleur Magique*, pour annuler l'activation de *Ville des Engrenages*.
- *Lorsqu'une Carte Magie est activée : défaussez 1 carte ; annulez l'activation, et si vous le faites, détruisez-la.*

Construction de la Chaîne :

- <ins>Chain Link 1</ins> : Activation de *Ville des Engrenages* sur le Terrain

- <ins>Chain Link 2</ins> : *Brouilleur Magique*

Résolution de la Chaîne :

- <ins>Chain Link 2</ins> résout : *Brouilleur Magique* annule l'activation de *Ville des Engrenages* et la détruit

- <ins>Chain Link 1</ins> résout : (rien)

Comme *Brouilleur Magique* annule l'activation, les effets de *Ville des Engrenages* sur le Terrain n'essaient pas de résoudre du tout. C'est pourquoi il est possible de dire que la destruction de *Ville des Engrenages* était effectivement l'une des dernières choses à avoir lieu, donc son effet déclencheur peut s'activer normalement. 

## Effet optionnel "Lorsque" et SEGOC

Cet article ainsi que l'article précédent se penchent sur les effets déclencheurs. Voyons comment cette mécanique interagit avec le SEGOC.

Joueur A active *Trou Noir*, détruisant son *Bixi, Eau du Yang Zing*, ainsi que le *Soldat de Carte* du Joueur B. 
- *Bixi, Eau du Yang Zing* :
    
    *<ins>Lorsque</ins> cette carte que vous contrôlez est détruite au combat ou par un effet de carte, et envoyée à votre Cimetière : <ins>vous pouvez</ins> Invoquer Spécialement 1 monstre "Yang Zing" ("Bixi, Eau du Yang Zing" exclu) depuis votre Deck en Position d'Attaque.*

- *Soldat de Carte* :
  
    *Si cette carte que vous contrôlez est détruite et envoyée à votre Cimetière : piochez 1 carte.*

<ins>Chain Link 1</ins> : *Trou Noir*

Résolution de la Chaîne : *Trou Noir* détruit *Bixi* et *Soldat de Carte* en même temps.

Regardons d'abord quels effets veulent s'activer. Les effets de *Bixi* et *Soldat de Carte* sont tous les deux déclenchés, donc ils sont tous deux candidats.

Regardons si l'un des effets peut manquer son créneau d'activation. La destruction de *Bixi* et de *Soldat de Carte* est simultanée et la dernière action à avoir lieu (et l'activation de *Soldat de Carte* est obligatoire), donc les deux effets peuvent s'activer. 

Maintenant que les effets à activer ont été décidés, la prochaine étape concerne l'ordre d'activation de ces effets. *Soldat de Carte* est un effet obligatoire du **NJT**, et *Bixi* est un effet facultatif du **JT**, donc d'après les règles du SEGOC, les effets s'activeront dans la Chaîne suivante dans cet ordre :

- <ins>Chain Link 1</ins> : *Soldat de Carte*

- <ins>Chain Link 2</ins> : *Bixi*

(Si les règles du SEGOC mentionnées ici ne vous sont pas familières, n'hésitez pas à lire ou relire l'article précédent)

Le point important dans cet exemple concerne l'activation de *Soldat de Carte*, qui n'empêche pas *Bixi* de s'activer. Il faut vérifier si les conditions d'activations de son effet sont bien remplies dans la dernière action que le jeu a enregistré après la résolution de la Chaîne, puis les nouveaux effets sont mis en accord avec le SEGOC sur une nouvelle Chaîne. 


## C'est l'heure du Quiz !
Vous pouvez partir du principe que tous les effets dans les questions ci-dessous ont des activations légales : il n'y a pas de question piège.

1. Joueur A contrôle *Dragon Pulsar de Lumière* et *Soldat Canon*. Joueur A sacrifie *Dragon Pulsar de Lumière* pour l'effet de *Soldat Canon*.

   - *Dragon Pulsar de Lumière* :

        *Lorsque cette carte est envoyée depuis le Terrain au Cimetière : vous pouvez cibler 1 monstre TÉNÈBRES Dragon de min. Niveau 5 dans votre Cimetière ; Invoquez Spécialement la cible.*

   - *Soldat Canon* :

        *Vous pouvez Sacrifier 1 monstre pour infliger 500 points de dommages à votre adversaire.*

    L'effet de *Dragon Pulsar de Lumière* peut-il être activé ?

    <details>
    <summary>Réponse</summary>
    <p>

    <strong>Non.</strong><br>

    <i>Soldat Canon sacrifie en coût (puisque le sacrifice est marqué avant le point-virgule) donc le sacrifice de Dragon Pulsar de Lumière n'est pas la dernière action à avoir lieu. Si vous vous demandez si l'effet de Dragon Pulsar se chaîne à l'effet de Soldat Canon ou non, retenez que les effets déclencheurs s'activent toujours après que la chaîne actuelle (si elle existe) ait résolu.</i>
    </p>
    </details>

2. Joueur A contrôle *Transe Archdémon* et Joueur B contrôle *Main de Glace*. Joueur A active *Trou Noir*.
   
    - *Transe Archdémon* :

        *Lorsque cette carte que vous contrôlez est détruite et envoyée à votre Cimetière : vous pouvez cibler 1 de vos monstres TÉNÈBRES bannis ; ajoutez la cible à votre main.*
    
    - *Main de Glace* :

        *Lorsque cette carte en votre possession est détruite par une carte de votre adversaire et envoyée à votre Cimetière : vous pouvez cibler 1 Magie/Piège qu'il contrôle ; détruisez la cible, puis vous pouvez Invoquer Spécialement 1 "Main de Feu" depuis votre Deck.*

    Après la résolution de *Trou Noir*, quelle Chaîne est formée ?

    <details>
    <summary>Réponse</summary>
    <p>

    <strong>Chain Link 1 : effet de <i>Transe Archdémon</i> | Chain Link 2 : effet de <i>Main de Glace</i></strong><br>

    <i>Transe Archdémon et Main de Glace sont tous deux détruits dans l'une des dernières actions à avoir lieu, donc ils peuvent tous deux s'activer. D'après les règles du SEGOC, les effets optionnels du Joueur A rentrent en premier sur la chaîne, puis les effets optionnels du Joueur B. Aucun de ces effets ne manque son créneau d'activation.</i>
    </p>
    </details>

3. Joueur A active le second effet de *Bixi, Eau du Yang Zing*, et Joueur B l'annule avec *Colère Divine*. 
    - *Bixi, Eau du Yang Zing* :

        *Lorsque cette carte que vous contrôlez est détruite au combat ou par un effet de carte, et envoyée à votre Cimetière : vous pouvez Invoquer Spécialement 1 monstre "Yang Zing" ("Bixi, Eau du Yang Zing" exclu) depuis votre Deck en Position d'Attaque. Vous ne pouvez utiliser cet effet de "Bixi, Eau du Yang Zing" qu'une fois par tour. Une fois par tour, durant la Main Phase ou Battle Phase de votre adversaire, vous pouvez : immédiatement après la résolution de cet effet, Invoquez par Synchronisation 1 Monstre Synchro, en utilisant uniquement des monstres "Yang Zing" que vous contrôlez (ceci est un Effet Rapide).*

    - *Colère Divine* :

        *Lorsqu'un effet de monstre est activé : défaussez 1 carte ; annulez l'activation, et si vous le faites, détruisez le monstre.*

    Le premier effet de *Bixi* peut-il être activé ?

    <details>
    <summary>Réponse</summary>
    <p>

    <strong>Oui.</strong><br>

    <i>L'effet en Chain Link 1 est celui de Bixi, et l'effet en Chain Link 2 est Colère Divine. Puisque Colère Divine annule l'activation de l'effet de Bixi, la Chain Link 1 disparaît et la dernière action à avoir lieu est la destruction de Bixi.</i>
    </p>
    </details>

4. Supposons que le Joueur B chaîne l'effet de *Ogre Fantôme et Lapin des Neiges* au second effet de *Bixi* dans la question précédente.
    - *Ogre Fantôme et Lapin des Neiges* :

        *Lorsqu'un monstre sur le Terrain active son effet, ou lorsqu'une Magie/Piège qui est déjà face recto sur le Terrain active son effet (Effet Rapide) : vous pouvez envoyer cette carte depuis votre main ou Terrain au Cimetière ; détruisez la carte sur le Terrain.*
    
    Le premier effet de *Bixi* peut-il être activé ?

    <details>
    <summary>Réponse</summary>
    <p>

    <strong>Non.</strong><br>

    <i>Ogre Fantôme et Lapin des Neiges n'annule pas l'activation, donc en résolvant la chaîne, la destruction de Bixi ne sera pas "l'une des dernières actions à avoir lieu".</i>
    </p>
    </details>

Nous verrons plus en détail cette mécanique, et la verrons en action, dans des articles à venir. 

Le prochain article porte sur les [Conjonctions](5_Conjonctions.md).
