# Démystification de rulings

# Invocations

Cet article revient à un élément plus simple mais tout aussi fondamental du jeu : les Invocations.

N'oubliez pas de jeter un oeil à l'article précédent sur les [conjonctions](5_Conjonctions.md) !

## Procédure complète d'Invocation Normale
Afin d'effectuer une Invocation Normale ou une Invocation Sacrifice, il faut sélectionner un monstre à Invoquer, Sacrifier des monstre si nécessaire, sélectionner une Zone Monstre, et déclarer l'intention d'Invoquer ce monstre. 

Ce point précis est connu (non-officiellement) comme la Fenêtre d'Annulation d'Invocation (Summon Negation Window en anglais). Il s'agir du moment pendant lequel activer des effets qui peuvent annuler l'Invocation, comme *Corne du Paradis* :
- *Lorsqu'un ou plusieurs monstres vont être Invoqués : Sacrifiez 1 monstre ; annulez l'Invocation, et si vous le faites, détruisez les monstres.*

Si un effet est activé pour annuler l'Invocation, alors une chaîne peut être formée (par exemple, l'adversaire pourrait chaîner *Mouchard Électronique*, qui annulerait l'activation de *Corne du Paradis*). Cependant, seule la première carte dans la Chaîne peut annuler l'Invocation, puisqu'il s'agit de la seule activée directement en réponse à la tentative d'Invocation. De plus, il ne peut y avoir qu'une seule Chaîne dans la Fenêtre d'Annulation d'Invocation.

Un autre point important à préciser est que le monstre n'est pas encore sur le terrain à ce moment. Le monstre n'est pas encore un monstre que le joueur contrôle, bien qu'il soit en sa possession. Si l'Invocation de *Soldat de Carte* est annulée et qu'il est détruit, son effet ne s'activera pas :
- *Si cette carte que vous contrôlez est détruite et envoyée à votre Cimetière : piochez 1 carte.*

L'effet de *Ouhouteau Magidolce*, lui, s'activera tout de même :
- *Si cette carte en votre possession est détruite par une carte de votre adversaire et envoyée à votre Cimetière : mélangez cette carte dans le Deck.*

Cette distinction est très importante pour les Monstres Pendule. La règle pour que les Monstres Pendules reviennent à l'Extra Deck est la suivante :

**Un Monstre Pendule est envoyé à l'Extra Deck à la place du Cimetière si, et seulement si, il est envoyé de n'importe où sur le terrain au Cimetière.**

Donc si l'Invocation d'un Monstre Pendule est annulée, alors il ne sera pas envoyé à l'Extra Deck.

Une fois la Fenêtre d'Annulation d'Invocation passée, l'Invocation est réussie, et les joueurs peuvent répondre à l'Invocation avec des cartes comme *Hommage Torrentiel* :
- *Lorsqu'un ou plusieurs monstres sont Invoqués : détruisez tous les monstres sur le Terrain.*

Contrairement à ce qui a été vu plus tôt, cette Chaîne entière est en réponse à l'Invocation, et non pas seulement la première carte, donc plusieurs effets peuvent être activés en réponse à l'invocation. Cependant, il s'agit de la seule Chaîne en réponse à cette Invocation.

Voilà pourquoi cet exemple est correct :

<ins>Chain Link 1</ins> : *Hommage Torrentiel*

<ins>Chain Link 2</ins> : *Trappe Sans Fond*

Mais celui-ci ne l'est pas :

<ins>Chain Link 1</ins> : *Hommage Torrentiel*

<ins>Chain Link 2</ins> : *Mouchard Électronique*

Puis dans une nouvelle Chaîne :

<ins>Chain Link 1</ins> : *Trappe Sans Fond*

## Résumé 
1. Le joueur sélectionne un monstre, effectue les Sacrifices nécessaires, et déclare son intention d'invoquer le monstre. Celui-ci n'est pas sur le terrain tant que la Fenêtre d'Annulation d'Invocation n'est pas passée.
2. Si la Fenêtre est passée, et que l'Invocation a lieu avec succès, le monstre touche le terrain et les joueurs peuvent répondre à l'Invocation 

## Invocation et Timing
Comme vous pouvez le voir, invoquer est un processus assez long. Une fois de plus, rappelez vous de la règle des effets optionnels "lorsque" : *Un effet optionnel "lorsque" ne peut être activé que quand sa condition d'activation est "l'une des dernières actions à avoir lieu"*.

C'est pourquoi quand certains monstres comme *Dragon Pulsar de Lumière* sont Sacrifiés pour une Invocation Sacrifice, le fait qu'ils soient envoyés du terrain au Cimetière n'est pas l'une des dernières actions à avoir lieu, donc leur effet ne peuvent pas être activés :
- *Lorsque cette carte est envoyée depuis le Terrain au Cimetière : vous pouvez cibler 1 monstre TÉNÈBRES Dragon de min. Niveau 5 dans votre Cimetière ; Invoquez Spécialement la cible.*

La même chose a lieu en cas de Pose par Sacrifice : le joueur Sacrifie les monstres, et pose la carte, donc il ne pourra pas les activer de cette manière non plus.

## Invocations Spéciales
Il existe différentes manières d'Invoquer Spécialement des monstre, et beaucoup d'entre eux ont des effets spécifiques qui le permettent. Nous somme déjà capables de différencier des effets de monstre invoquant Spécialement qui démarrent une Chaîne de ceux qui n'en démarrent pas (les effets démarrent une Chaîne si, et seulement si, ils ont un deux-points ou un point-virgule dans l'effet). Les Invocations Spéciales fonctionnent de la même manière que présenté plus tôt, en remplaçant les Sacrifices par l'envoi au Cimetière ou la superposition des matériels pour les Invocations Synchros ou Xyz, ou en respectant le texte de la carte en général.

## Annulation d'Invocations
Observons de plus près les annulations d'Invocations. **Afin d'annuler une Invocation, la clef est de se demander : est-ce qu'une Chaîne est actuellement en train de se résoudre ?** Puisqu'il est impossible d'interrompre une Chaîne en cours de résolution, il est impossible d'activer un effet pendant la Fenêtre d'Annulation d'Invocation, donc l'Invocation est automatiquement considérée comme complétée avec succès, et les joueurs peuvent y répondre après que la Chaîne ait fini de résoudre (du moment qu'il n'y a pas de conflit de condition d'activation).

Par exemple, prenons *Soldat du Lustre Noir - Émissaire du Commencement* :
- *Doit d'abord être Invoquée Spécialement (depuis votre main) en bannissant 1 monstre LUMIÈRE et 1 monstre TÉNÈBRES depuis votre Cimetière.*

On peut lire de son texte que son effet d'Invocation ne démarre pas de Chaîne. Des cartes comme *Corne Céleste Ténébreuse* peuvent donc être activées dans sa Fenêtre d'Annulation d'Invocation normalement :
- *Lorsque votre adversaire va Invoquer Spécialement exactement 1 monstre : annulez l'Invocation Spéciale, et si vous le faites, détruisez-le.*

Supposons maintenant que j'active *Polymérisation*, et que j'Invoque Spécialement un monstre Fusion.

<ins>Chain Link 1</ins> : *Polymérisation*

<ins>Résolution de la Chaîne</ins> : *Polymérisation* Invoque Spécialement le monstre Fusion

La première partie de l'Invocation a lieu pendant la résolution de *Polymérisation*, donc rien ne peut être activé pendant la Fenêtre d'Annulation de l'Effet (bien qu'après que la Chaîne soit résolue, il reste possible de répondre à l'Invocation). *Corne Céleste Ténébreuse* n'est donc pas activable en réponse à *Polymérisation*, et elle ne peut pas non plus être activé après la résolution de *Polymérisation*.

Supposons maintenant que j'Invoque Spécialement *Grande Prêtresse de la Prophétie* :
- *Vous pouvez révéler 3 Magies "Livre de Magie" dans votre main ; Invoquez Spécialement cette carte depuis votre main.*

Le point-virgule dans l'effet précise que cet effet démarre une Chaîne :

<ins>Chain Link 1</ins> : *Grande Prêtresse de la Prophétie*

<ins>Résolution de la Chaîne</ins> : *Prêtresse* s'Invoque Spécialement

De nouveau, cette Invocation Spéciale a lieu pendant que la Chain Link 1 est entrain de se résoudre, donc rien ne peut être activé pendant la Fenêtre d'Annulation d'Invocation.

Il est toujours possible cependant d'annuler les activations de *Polymérisation* ou de *Prêtresse*. Les Invocations elles-mêmes ne peuvent simplement pas être annulées, du moment que l'effet résoud avec succès. Par exemple, il est toujours possible d'annuler l'effet de *Polymérisation* avec une carte comme *Annihilateur de Magie*, ou annuler l'Invocation Spéciale en chaînant une carte comme *Espace de Négation*.

Dans un article sur les mécaniques d'Invocation, il serait impensable de ne pas mentionner *Avertissement Divin* :
- *Lorsqu'un ou plusieurs monstres vont être Invoqués, OU lorsqu'une Carte Magie/Piège ou un effet de monstre qui inclut un effet qui Invoque Spécialement un ou plusieurs monstres est activé : payez 2000 LP ; annulez l'Invocation ou l'activation, et si vous le faites, détruisez-les.*

La première partie du texte annule les Invocations, tout comme *Corne Céleste Ténébreuse*. Cependant, la seconde partie du texte explique que la carte peut annuler l'activation de Cartes Magie, Piège, et des effets de Monstres. Ce point veut dire que la carte peut être chaînée à *Polymérisation* et à l'effet de *Prêtresse* plus haut, non pas pour annuler les invocations mais les cartes elles-mêmes, puisque leurs activations impliquent une Invocation Spéciale.

Le dernier exemple de cet article se basera sur *Bixi, Eau du Yang Zing* :
- *Une fois par tour, durant la Main Phase ou Battle Phase de votre adversaire, vous pouvez : <ins>immédiatement après la résolution de cet effet</ins>, Invoquez par Synchronisation 1 Monstre Synchro, en utilisant uniquement des monstres "Yang Zing" que vous contrôlez (ceci est un Effet Rapide).*

Le texte souligné est ici pour préciser que l'Invocation Synchro a lieu **après** que la Chaîne ait résolu.

<ins>Chain Link 1</ins> : *Bixi*

<ins>Résolution de la Chaîne</ins> : L'effet de *Bixi* résoud, bien qu'il ne fasse rien immédiatement

L'Invocation Synchro est effectuée à ce moment, après la résolution de la Chaîne.

Est-ce qu'une Chaîne est actuellement en cours de résolution ? Ici, ce n'est pas le cas, puisque l'Invocation Synchro a lieu après que la Chaîne ait fini de résoudre. Des effets peuvent donc être activés dans la Fenêtre d'Annulation d'Invocation normalement (et c'est là la raison du texte 'immédiatement après la résolution de cet effet').

## C'est l'heure du Quiz !
1. *Cafard Colonie de Chrome* peut-il annuler l'Invocation Spéciale de *Grande Prêtresse de la Prophétie* ?

   - *Grande Prêtresse de la Prophétie* :

        *Vous pouvez révéler 3 Magies "Livre de Magie" dans votre main ; Invoquez Spécialement cette carte depuis votre main.*

   - *Cafard Colonie de Chrome* :

        *Durant le tour de chaque joueur, lorsqu'un monstre de min. Niveau 5 va être Invoqué Spécialement : vous pouvez détacher 1 Matériel Xyz de cette carte ; annulez l'Invocation Spéciale, et si vous le faites, détruisez-le.*

2. Joueur A tente d'effectuer l'Invocation Synchro de *Virgile, Star du Rock des Abysses Ardents*, et Joueur B annule l'Invocation avec *Avertissement Divin*. L'effet de Virgil peut-il être activé ?

    - *Virgile, Star du Rock des Abysses Ardents* :

        *Si cette carte sur le Terrain est détruite au combat ou par un effet de carte, et envoyée au Cimetière : vous pouvez piocher 1 carte.*

    - *Avertissement Divin* :

        *Lorsqu'un ou plusieurs monstres vont être Invoqués, OU lorsqu'une Carte Magie/Piège ou un effet de monstre qui inclut un effet qui Invoque Spécialement un ou plusieurs monstres est activé : payez 2000 LP ; annulez l'Invocation ou l'activation, et si vous le faites, détruisez-les.*

3. Que se passerait-il si Joueur A tentait d'invoquer par Invocation Xyz *Dante, Voyageur des Abysses Ardents* à la place ?

   - *Dante, Voyageur des Abysses Ardents* : 

        *Si cette carte est envoyée au Cimetière : vous pouvez cibler 1 carte "Abysses Ardents" (cette carte exclue) dans votre Cimetière ; ajoutez-la à votre main.*

4. Joueur A active *Voleur d'Esprit* sur *Bixi, Eau du Yang Zing*, mais Joueur B chaîne en utilisant les effets de *Bixi*, l'utilisant avec d'autres monstres afin d'invoquer par Invocation Synchro *Dragon Rose Noire*. Joueur A peut-il annuler l'Invocation Synchro de *Dragon Rose Noire* ?

   - *Bixi, Eau du Yang Zing* :

        *Une fois par tour, durant la Main Phase ou Battle Phase de votre adversaire, vous pouvez : immédiatement après la résolution de cet effet, Invoquez par Synchronisation 1 Monstre Synchro, en utilisant uniquement des monstres "Yang Zing" que vous contrôlez (ceci est un Effet Rapide).*

   - *Dragon Rose Noire* :

        *Lorsque cette carte est Invoquée par Synchronisation : vous pouvez détruire toutes les cartes sur le Terrain.*

   - *Voleur d'Esprit* :

        *Ciblez 1 monstre face recto contrôlé par votre adversaire ; détruisez la cible, puis votre adversaire gagne 1000 LP.*

5. Dans l'exemple ci-dessus, l'effet de *Dragon Rose Noire* peut-il être activé ?

<details>
<summary>Réponses</summary>
    
 1. **Non.** 
   
      *L'effet de Prêtresse démarre une Chaîne, donc son Invocation Spéciale a lieu pendant la résolution d'une Chaîne. L'effet de Cafard ne pourra donc pas être utilisé à ce moment.*
      
 2. **Non.** 
   
      *Virgil a besoin d'être détruit sur le terrain. Si son Invocation est annulée, il n'aura jamais touché le terrain.*
 
 3. **L'effet de Dante pourra s'activer** 
      
      *Dante n'a pas besoin d'être envoyé spécifiquement depuis le terrain au Cimetière, donc son effet pourra s'activer.*

 4. **Non.**
 
      *La Chain Link 1 est Voleur d'Esprit, et la Chain Link 2 est Bixi. Rose Noire est Invoqué juste après la résolution de la Chain Link 2, mais avant la résolution de la Chain Link 1. Puisqu'une Chaîne est en cours de résolution, cette Invocation Synchro ne pourra pas être annulée.*

 5. **Non.**
 
      *Puisque l'Invocation Synchro de Rose Noire n'est pas l'une des dernières actions à avoir lieu (Voleur d'Esprit essaie toujours de résoudre après l'invocation de Rose Noire), son effet ne peut pas être activé.*
</details>

Le prochain article portera sur le [Timing d'effet rapide](7_Timing_Effet_Rapide.md).
