# Démystification de rulings

# La Battle Phase
Dans cet article, nous décortiquerons la structure de la Battle Phase, un élément fondamental de chaque duel.

Le [timing d'effet rapide](07_Timing_Effet_Rapide.md) est extrêmement important pour comprendre la Battle Phase. N'hésitez pas à le consulter pour vous rafraîchir la mémoire ! 

## Structure
La Battle Phase est comprise de 4 étapes, appelées Steps :
1. La Start Step
2. La Battle Step
3. La Damage Step
4. La End Step

Chaque Battle Phase commence par la **Start Step**. Après cette étape, la **Battle Step** est toujours entrée, et le joueur du tour déclare ses attaques, les unes après les autres, à ce moment. Une attaque se résolvant avec succès passe par la **Damage Step**, dans laquelle les ATK et DEF des monstres sont comparées. La **Battle Step** et la **Damage Step** sont ensuite répétées en séquence jusqu'à ce que le joueur du tour décide de terminer sa Battle Phase, nous amenant donc à la **End Step**.

À noter que chaque Step suit le graphe de timing d'Effets Rapides du dernier article (bien que, par exemple, les Effets Déclencheurs ne peuvent pas être activés en Game State ouverts). En particulier, retenez que les Phases et Steps ne peuvent en général pas changer tant que tous les effets n'ont pas fini de se résoudre, et que les deux joueurs n'ont pas fini d'activer des cartes.

Observons maintenant chaque Step en détail.
## Start Step
Il n'y a pas grand-chose de spécifique à dire dans cette Step, à part qu'il s'agit du meilleur moment pour activer *Rugissement Menaçant* :
- *Votre adversaire ne peut pas déclarer d'attaque ce tour.*


## Battle Step
Cette Step est atteinte même si aucune attaque ne sera déclarée. La Step est commencée dans un Game State ouvert, donc si le joueur du tour veut attaquer ou activer un effet, il peut (sinon, si son adversaire est d'accord, le jeu se déplace à la End Step). Donc, par exemple, *Juragedo* peut toujours être invoqué si le joueur du tour est entré en Battle Phase, même si le joueur ne contrôle pas de monstre : 
- *Durant la Battle Step (Effet Rapide) : vous pouvez Invoquer Spécialement cette carte depuis votre main, et si vous le faites, gagnez 1000 LP.*

Une attaque est déclarée lorsqu'un joueur choisit un monstre attaquant, ainsi qu'une cible pour son attaque. Les deux joueurs peuvent répondre à cette attaque, en accord avec les règles de timing d'effets rapides. De la même manière que la réponse à une Invocation, la Chaîne complète est construite en réponse à l'attaque.

Cette Chaîne est donc correcte :

- <ins>Chain Link 1</ins> : *Force de Miroir*

- <ins>Chain Link 2</ins> : *Prison Dimensionnelle*

Cependant, il ne peut y avoir qu'une Chaîne qui réponde à l'attaque. Vous ne pouvez pas construire deux Chaînes à la suite pour répondre à la déclaration de l'attaque.

Ces actions ne sont donc pas correctes :

- <ins>Chain Link 1</ins> : *Force de Miroir*

- <ins>Chain Link 2</ins> : *Mouchard Électronique*

  (puis dans une nouvelle Chaîne)

- <ins>Chain Link 1</ins> : *Force de Miroir*

Cependant, ces actions sont correctes :

- <ins>Chain Link 1</ins> : *Force de Miroir*

- <ins>Chain Link 2</ins> : *Mouchard Électronique*

  (puis dans une nouvelle Chaîne)

- <ins>Chain Link 1</ins> : *Chaîne Démoniaque*

*Chaîne Démoniaque* ne dépend pas d'une déclaration d'attaque, donc il est légal de l'activer suite à la résolution de la première chaîne.

La Battle Step est également l'étape lors de laquelle un Replay d'attaque peut arriver. Le livret de règles explique ce qu'est un Replay :

*Après avoir annoncé votre monstre attaquant et le monstre cible de l'attaque durant une Battle Step, la cible de l'attaque peut être retirée du Terrain, ou un nouveau monstre peut être joué sur le Terrain de votre adversaire avant la Damage Step, en raison de l'effet d'une carte. Ceci provoque un “Replay”. Dans ce cas, vous pouvez choisir d'attaquer avec le même monstre à nouveau, choisir d'attaquer avec un autre monstre ou de ne pas attaquer du tout. Notez que si vous choisissez d'attaquer avec un monstre différent, le premier monstre est toujours considéré comme ayant déclaré une attaque et ne pourra pas attaquer à nouveau durant ce tour.*

Par exemple, supposons que j'attaque le *Magicien Sombre* de mon adversaire avec mon *Dragon Blanc aux Yeux Bleus*. Mon adversaire répond à l'attaque avec *Appel de l'Être Hanté*, pour Invoquer de nouveau *Apprenti Sorcier* :
- *Tant que cette carte reste face recto sur le Terrain, augmentez l'ATK de tous les monstres TÉNÈBRES de 500 points et diminuez l'ATK des monstres LUMIÈRE de 400 points.*

Mes cibles d'attaques ont changé, donc je peux :
1. Sélectionner de nouveau ma cible d'attaque, en choisissant soit *Magicien sombre* soit *Apprenti Sorcier*
2. Annuler l'attaque

À noter qu'avec le choix (1), je ne redéclare pas l'attaque en elle-même. Mon adversaire ne pourra pas activer *Force de Miroir* à ce stade.

Dans les deux cas, l'attaque a maintenant été déclarée. Même si je choisis l'option (2), et attaque avec un monstre différent, je ne pourrai plus attaquer avec ce *Dragon Blanc aux Yeux Bleus* ce tour.

Les Replays n'ont lieu que quand le nombre de cibles potentielles change. Si mon adversaire active *Rétrécissement* (*Ciblez 1 monstre face recto sur le Terrain ; jusqu'à la fin de ce tour, son ATK d'origine sera divisée par deux.*) à la place d'*Appel de l'Être Hanté* en réponse à mon attaque, je ne pourrai pas annuler l'attaque de mon *Dragon Blanc*.

## Damage Step
Nous arrivons enfin au cœur du combat. Elle peut sembler simple, mais dans les faits, cette Step comporte quelques-unes des règles les plus bizarres et perturbantes du jeu. 

Cette Step est spécifiquement pour le combat en lui-même. Seuls certains effets peuvent être activés à cette étape. Le point important sur cette restriction, est que la carte a besoin d'avoir une raison spécifique de s'activer durant la Damage Step, autre qu'uniquement 'être un effet rapide'. Les types de cartes qui PEUVENT être activées sont les suivantes :
- Cartes Contre Piège
- Modificateurs directs d'ATK / DEF, comme *Rétrécissement* ou *Lance Interdite* :
  - *Rétrécissement* :

    *Ciblez 1 monstre face recto sur le Terrain ; jusqu'à la fin de ce tour, son ATK d'origine sera divisée par deux*

  - *Lance Interdite* :

    *Ciblez 1 monstre face recto sur le Terrain ; jusqu'à la fin de ce tour, la cible perd 800 ATK, mais elle n'est pas affectée par les effets d'autres Magies/Pièges.*
- Effets de monstre annulant l'**activation** d'effets, comme *Dragon Poussière d'Étoile* :
  - *Lorsqu'une carte ou un effet qui va détruire une ou plusieurs cartes sur le Terrain est activé (Effet Rapide) : vous pouvez Sacrifier cette carte ; annulez l'activation, et si vous le faites, détruisez-la.*
- Effets qui mentionnent explicitement ou implicitement qu'ils s'activent durant la Damage Step, comme *Rat Géant* (son effet s'active qui s'active durant la Damage Step, comme il s'active en étant détruit par combat) :
    - *Lorsque cette carte est détruite au combat et envoyée au Cimetière : vous pouvez Invoquer Spécialement 1 monstre TERRE avec max. 1500 ATK depuis votre Deck en Position d'Attaque.*

Cependant, il n'est **PAS** possible d'activer *Typhon d'Espace Mystique*, puisqu'il n'y a pas de raison particulière de l'autoriser dans la Damage Step. De la même manière, si un monstre est Invoqué Spécialement dans la Damage Step, il est impossible d'activer *Trappe Sans Fond*. Certaines cartes et effets expliciteront qu'ils ne peuvent pas être activés durant la Damage Step, donc il est toujours sage de revérifier l'effet de la carte.

Nous étudierons la structure exacte de la Damage Step dans le prochain article.

## End Step
Une fois que le joueur du tour ne souhaite plus déclarer d'attaque, le joueur arrive à cette étape. C'est l'étape dans laquelle s'activent les effets comme *Bestiari, Bête Gladiateur* :
- *À la fin de la Battle Phase, si cette carte a attaqué ou a été attaquée : vous pouvez la mélanger dans le Deck ; Invoquez Spécialement 1 monstre "Bête Gladiateur" ("Bestiari, Bête Gladiateur" exclus) depuis votre Deck.*

## C'est l'heure du Quiz !
1. Quels effets activés par mon adversaire causent un Replay d'attaque s'ils sont activés en réponse à mon attaque ?
     - *Trio Ojama* :
     
       *Invoquez Spécialement 3 "Jeton Ojama" (Type Bête/LUMIÈRE/Niveau 2/ATK 0/DEF 1000) sur le Terrain de votre adversaire en Position de Défense.*

     - *Cercle des Rois du Feu* :

       *Ciblez 1 monstre FEU que vous contrôlez et 1 monstre FEU dans votre Cimetière ; détruisez le monstre que vous contrôlez, et si vous le faites, Invoquez Spécialement l'autre monstre depuis votre Cimetière. Vous ne pouvez activer qu'1 "Cercle des Rois du Feu" par tour.*

     - *Boost d'Ego* :

       *Lorsqu'un monstre déclare une attaque : ciblez 1 monstre face recto sur le Terrain ; jusqu'à la fin de la Battle Phase, il gagne 1000 ATK.*

    <details>
    <summary>Réponse</summary>
    <p>
      <strong>Uniquement <i>Cercle des Rois du Feu</i>.</strong><br>
      <i>Les deux autres cartes ne changent pas les cibles d'attaque potentielles, contrairement à Cercle.</i>
    </p>
    </details>

2. Quels effets peuvent être activés durant la Damage Step ?

     - *Hommage Torrentiel* :

       Lorsqu'un ou plusieurs monstres sont Invoqués : détruisez tous les monstres sur le Terrain.*

     - Le second effet de *Loi des Ténèbres, HÉROS Masqué* :

       *Une fois par tour, si votre adversaire ajoute une ou plusieurs cartes depuis son Deck à sa main (sauf durant la Draw Phase ou la Damage Step) : vous pouvez bannir 1 carte au hasard depuis la main de votre adversaire.*

     - *Colère Divine* :

       *Lorsqu'un effet de monstre est activé : défaussez 1 carte ; annulez l'activation, et si vous le faites, détruisez le monstre.*

    <details>
    <summary>Réponse</summary>
    <p>
    <strong>Uniquement <i>Colère Divine</i>.</strong><br>
    <i>Hommage Torrentiel n'a pas de raison d'être autorisé durant la Damage Step et l'effet de Loi des Ténèbres exclue spécifiquement la Damage Step. Colère Divine annule l'activation des effets, donc elle peut être activée.</i>
    </p>
    </details>

3. J'entre en Battle Phase. Puis-je déclarer une attaque avec *Golem Rouages Ancients* avant que mon adversaire n'active *Rugissement Menaçant* ?
     - *Rugissement Menaçant* :

       *Votre adversaire ne peut pas déclarer d'attaque ce tour.*

     - *Golem Rouages Ancients* :

       *Si cette carte attaque, votre adversaire ne peut pas activer de Cartes Magie/Piège jusqu'à la fin de la Damage Step.*

    <details>
    <summary>Réponse</summary>
    <p>
    <strong>Non.</strong><br>
    <i>Rugissement Menaçant peut être activé durant la Start Step, avant que Golem Rouages Ancients ne puisse déclarer une attaque durant la Battle Step. N'oubliez pas du dernier article sur le timing d'effets rapides que les Phases ne changent pas sans que les deux joueurs ne soient d'accord.</i>
    </p>
    </details>

4. Puis-je activer *Flèches Anti-Magie* avant que mon adversaire n'active *Rugissement Menaçant* ? 
     - *Flèches Anti-Magie* :

       *Au début de la Battle Phase : le reste de ce tour après la résolution de cette carte, aucun joueur ne peut activer ni de Cartes Magie/Piège ni leurs effets. Aucun joueur ne peut activer ni de cartes ni d'effets en réponse à l'activation de cette carte.*

    <details>
    <summary>Réponse</summary>
    <p>
    <strong>Oui.</strong><br>
    <i>Le Joueur du Tour a le droit d'activer un effet rapide avant son adversaire lors de la Start Step, de nouveau d'après les timings d'effet rapide.</i>
    </p>
    </details>

Lors du prochain article, nous nous pencherons plus en détail sur la structure de la [Damage Step](09_Damage_Step.md).

