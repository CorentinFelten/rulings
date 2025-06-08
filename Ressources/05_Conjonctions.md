# Démystification de rulings

# Conjonctions
Pour le PSCT, une conjonction est un mot ou un groupe de mots qui lie deux parties d'un effet. Elle contient beaucoup d'informations sur la manière dont un effet marche en un seul groupe de mots, ce qui en fait un élément crucial du PSCT. 

Avant de commencer, n'oubliez pas de lire le dernier article sur les [effets déclencheurs "Lorsque" optionnels](04_When_Optionnels.md).

## Introduction
Les 4 conjonctions principales sont <ins>*puis*</ins>, <ins>*et si vous le faites*</ins>, <ins>*et aussi*</ins> et <ins>*aussi, après cela*</ins>. Voici quelques exemples :
- *Le Livre de la Vie* :

    *Ciblez 1 monstre Zombie dans votre Cimetière et 1 monstre dans le Cimetière de votre adversaire ; Invoquez Spécialement la première cible, <ins>et aussi</ins>, bannissez la seconde cible.*

Ici, l'effet est de la forme 'faire A, *et aussi* faire B', où A est l'Invocation Spéciale de la première cible et B le bannissement de la seconde cible. La structure est similaire pour les autres conjonctions :
- *Nékroz de Valkyrus* :
    
    *Lorsqu'un monstre de l'adversaire déclare une attaque : vous pouvez bannir 1 carte "Nékroz" depuis votre Cimetière et défausser cette carte ; annulez l'attaque, <ins>puis</ins> terminez la Battle Phase.*

Ici, l'effet est de la forme 'faire A, *puis* faire B', où A est l'annulation d'attaque et B est la fin de la Battle Phase.

## Conjonctions et Créneaux
Le premier point que les conjonctions nous permettent d'identifier est de savoir si A et B sont simultanées ou non pour les effets optionnels "lorsque".

<ins>A et B sont simultanées</ins> :
- *et si vous le faites* (*and if you do*)
- *et aussi* (*also*)

<ins>A et B ne sont pas simultanées</ins> :
- *puis* (*then*)
- *aussi, après cela* (*also, after that*)

Pourquoi s'attarder sur ce point ? Souvenez-vous de la règle sur les effets optionnels "Lorsque" de l'article précédent : *Un effet optionnel "Lorsque" ne peut être activé uniquement quand sa condition d'activation est "l'une des dernières actions à avoir lieu".* Si A et B ne sont pas des actions simultanées, alors A **ne peut pas** être l'une des dernières actions à avoir lieu.

Voyons un exemple. Supposons que j'utilise *Voleur d'Esprit* sur *Dragon Pulsar de Lumière* :
- *Voleur d'Esprit* :

    *Ciblez 1 monstre face recto contrôlé par votre adversaire ; détruisez la cible, <ins>puis</ins> (<ins>then</ins>) votre adversaire gagne 1000 LP.*

- *Dragon Pulsar de Lumière* :

    *<ins>Lorsque</ins> cette carte est envoyée depuis le Terrain au Cimetière : <ins>vous pouvez</ins> cibler 1 monstre TÉNÈBRES Dragon de min. Niveau 5 dans votre Cimetière ; Invoquez Spécialement la cible.*

(À noter que l'effet de *Dragon Pulsar de Lumière* est effectivement un effet optionnel "Lorsque")

<ins>Chain Link 1</ins> : *Voleur d'Esprit*

L'emploi du *puis* (*then*) dans l'effet de *Voleur d'Esprit* explique que la destruction et le gain de LP ne sont pas simultanés. Le gain de LP a lieu <ins>après</ins> la destruction en termes de timing. 

<ins>Résolution de la Chaîne</ins> : *Voleur d'Esprit* détruit *Dragon Pulsar*. Une fois le monstre détruit, mon adversaire gagne 1000 LP.

La destruction de *Dragon Pulsar* n'est donc pas l'une des dernières actions à avoir lieu, il manque donc son créneau d'activation.

Supposons maintenant que j'active l'effet de *Numéro 50 : Bateau Noir de Maïs* sur *Dragon Pulsar de Lumière* (on suppose également que j'ai réduit l'ATK de *Dragon Pulsar* pour qu'elle soit plus basse que celle du *Bateau*) :
- *Numéro 50 : Bateau Noir de Maïs* :

    *Une fois par tour : vous pouvez détacher 1 Matériel Xyz de cette carte, puis ciblez 1 monstre face recto contrôlé par votre adversaire avec une ATK inférieure ou égale à l'ATK de cette carte ; envoyez-le au Cimetière, <ins>et si vous le faites</ins> (<ins>and if you do</ins>), infligez 1000 points de dommages à votre adversaire.*

<ins>Chain Link 1</ins> : effet de *Numéro 50 : Bateau Noir de Maïs*

Cette fois-ci, la conjonction est *et si vous le faites*, ce qui veut dire que l'envoi au Cimetière et le fait d'infliger des dommages sont simultanés à la résolution.

<ins>Résolution de la Chaîne</ins> : *Dragon Pulsar de Lumière* est envoyé au Cimetière, et au même moment mon adversaire prend 1000 points de dommages.

La condition d'activation de l'effet de *Dragon Pulsar* est l'une des dernières actions à avoir lieu, donc son effet peut être activé. 

À noter que les effets ici étaient en Chain Link 1, et la résolution serait différente s'ils étaient Chain Link 2 ou plus. Surveillez toujours les dernières actions à avoir lieu.

## Conjonctions et Résolutions

Les conjonctions nous expliquent également la quantité à résoudre d'un effet si un autre effet perturbateur est chaîné. Ce type d'effet devrait vous rappeler la discussion sur le mot "cible" étant utilisé après le point-virgule, dans le [deuxième article](02_Ciblage.md) de cette série.

<ins>A doit se résoudre pour faire B</ins> :
- *et si vous le faites* (*and if you do*)
- *puis* (*then*)

<ins>Si A ne résout pas, B résout quand même</ins> :
- *et aussi* (*also*)
- *aussi, après cela* (*also, after that*)

B n'est jamais requis pour A : si B n'est pas réalisable à la résolution de l'effet, A sera tout de même résolue (on dit qu'on résout l'effet autant que possible).

Supposons que je déclare une attaque. Mon adversaire active l'effet de *Nékroz de Valkyrus* pour annuler mon attaque, mais je chaîne *Le Livre de la Lune* pour passer mon monstre face verso.
- *Nékroz de Valkyrus* :
    
    *Lorsqu'un monstre de l'adversaire déclare une attaque : vous pouvez bannir 1 carte "Nékroz" depuis votre Cimetière et défausser cette carte ; annulez l'attaque, <ins>puis</ins> (<ins>then</ins>) terminez la Battle Phase.*

*Valkyrus* ne peut donc plus annuler l'attaque, puisque le monstre n'est plus en train d'attaquer. Comme *Valkyrus* utilise la conjonction *puis*, il ne pourra pas terminer la Battle Phase.

Supposons maintenant que j'active *Le Livre de la Vie*, et que mon adversaire utilise son *Corbeau D.D.* pour bannir ma cible de type Zombie dans mon Cimetière.
- *Le Livre de la Vie* :

    *Ciblez 1 monstre Zombie dans votre Cimetière et 1 monstre dans le Cimetière de votre adversaire ; Invoquez Spécialement la première cible, <ins>et aussi</ins> (<ins>also</ins>), bannissez la seconde cible.*

Comme *Le Livre de la Vie* utilise la conjonction *et aussi*, bien que je ne puisse pas Invoquer Spécialement ma première cible à la résolution, la seconde cible sera tout de même bannie.

Dernier exemple. J'ai invoqué plus de 5 fois pendant le tour, et mon adversaire déclare l'effet de *Nibiru, l'Être Primitif* à ma déclaration de sortie de Main Phase 1 (soit en CL1). Je chaîne l'effet d'*Appel de l'Être Hanté*, ciblant mon *Fossile Dyna Pachycéphalosaure* dans mon Cimetière.

- *Nibiru, l'Être Primitif* :

    *Durant la Main Phase, si votre adversaire a Invoqué Normalement ou Spécialement min. 5 monstres ce tour (Effet Rapide) : vous pouvez Sacrifier autant de monstres face recto sur le Terrain que possible, et si vous le faites, Invoquez Spécialement cette carte depuis votre main, puis Invoquez Spécialement 1 "Jeton Être Primitif" (Rocher/LUMIÈRE/Niveau 11/ATK ?/DEF ?) sur le Terrain de votre adversaire.*

- *Appel de l'Être Hanté* :

    *Activez cette carte en ciblant 1 monstre dans votre Cimetière ; Invoquez Spécialement la cible en Position d'Attaque.*

- *Fossile Dyna Pachycéphalosaure* :

    *Aucun joueur ne peut Invoquer Spécialement de monstres.*

Si *Fossile Dyna Pachycéphalosaure* était sur mon terrain avant mon changement de phase, l'effet de *Nibiru, l'Être Primitif* n'aurait pas pu être activé puisque sa résolution implique d'invoquer spécialement un jeton et *Nibiru*. Or comme l'invocation de *Fossile Dyna* s'effectue en cours de résolution de Chaîne, on tentera de résoudre l'effet de *Nibiru* au maximum. En résolution de Chaîne, *Fossile Dyna* sera invoqué sur le terrain, puis l'effet de *Nibiru* sera résolu, sacrifiant tous les monstres face recto, **y compris Fossile Dyna**, avant de tenter d'invoquer le jeton et lui-même (l'invocation n'ayant lieu qu'après avoir sacrifié sur le terrain, comme spécifié par le <ins>*et si vous le faites*</ins> (<ins>*and if you do*</ins>)).


## "Et"
Il existe une conjonction supplémentaire, en plus des 4 mentionnées plus haut : *et*. Lorsqu'un effet dit 'faire A *et* B', il explique que A et B sont simultanés en termes de timing. Cependant, contrairement à *et si vous le faites* et *et aussi*, la conjonction demande de pouvoir réaliser A et B à la résolution, et dans le cas où l'un des deux n'est pas réalisable, l'effet ne fera rien.

Par exemple, *Numéro 53 : Heart-eartH* utilise la conjonction *et* :
- *Lorsque cette carte sur le Terrain est détruite par un effet de carte tant qu'elle n'a pas de Matériel Xyz : vous pouvez Invoquer Spécialement 1 "Numéro 92 : Dragon Heart-eartH" depuis votre Extra Deck <ins>et</ins> lui attacher cette carte depuis le Cimetière comme Matériel Xyz. (Cette Invocation Spéciale est traitée comme une Invocation Xyz.)*

Dans cet effet, la partie A est l'Invocation Spéciale de *Numéro 92*, et la partie B est d'attacher *Numéro 53* en tant que Matériel Xyz. Si *Corbeau D.D.* bannit *Numéro 53* du Cimetière, l'effet n'Invoquera pas *Numéro 92*. Aussi, l'Invocation Spéciale et le fait d'attacher sont simultanés en termes de timing, donc si cette action a lieu en Chain Link 1, *Hommage Torrentiel* peut être activé en réponse à l'Invocation.

À noter également que la conjonction *et* a été utilisée par Konami brièvement pendant l'apparition du PSCT en tant que conjonction à part entière, avant d'être remplacée par des conjonctions plus précises comme *et aussi* ou *et si vous le faites* en raison de la confusion engendrée par le terme. N'oubliez donc pas de relire la dernière version du texte afin de vous assurer que la bonne conjonction est employée ! 

## Divers
Comment retenir toutes ces conjonctions ? La façon dont elles sont écrites est d'une aide précieuse : *et si vous le faites* et *puis* suggèrent que B est dépendant de la bonne résolution de A, *puis* et *après cela* suggèrent que les deux parties de l'effet ne sont pas simultanées, etc. Avec de l'entraînement, ces conjonctions ne sont pas compliquées à retenir, et vous pourrez toujours les revérifier en cas d'oubli.

Quelques points importants :

1. Les conjonctions sont une des dernières additions au PSCT. Il existe donc quelques cartes écrites en PSCT qui utilisent *et* alors qu'elles veulent dire *et si vous le faites*, parce que ces cartes ont été rédigées avant que les conjonctions soient introduites, et elles n'ont pas encore été réimprimées. La conjonction *et* est très rare, donc si vous la croisez, n'hésitez pas à vérifier si la carte veut bien dire *et* ou si elle veut en réalité dire *et si vous le faites*.
2. Les conjonctions n'ont aucun rapport avec la légalité d'activation ! Elles n'expliquent que comment résoudre l'effet. Par exemple, il n'est pas légal d'activer *Le Livre de la Vie* sous *Mur de Fer Impérial*, bien qu'il ne soit pas nécessaire de bannir un monstre pour pouvoir Invoquer de nouveau la première cible. 

Nous reviendrons sur la légalité d'activation dans un article futur.

## C'est l'heure du Quiz !
1. Joueur A active le premier effet de *Yazi, Mal du Yang Zing*, et Joueur B l'annule avec *Stellnova Alpha* :

    - *Yazi, Mal du Yang Zing* :

        - *Vous pouvez cibler 1 monstre "Yang Zing" que vous contrôlez et 1 carte contrôlée par votre adversaire ; détruisez-les.*
        - *Lorsque cette carte que vous contrôlez est détruite au combat ou par un effet de carte, et envoyée à votre Cimetière : vous pouvez Invoquer Spécialement 1 monstre Wyrm depuis votre Deck en Position de Défense.*

    - *Stellnova Alpha* :

        *Lorsqu'une Carte Magie/Piège ou un effet de monstre est activé : envoyez 1 monstre "tellchevalier" face recto que vous contrôlez au Cimetière ; annulez l'activation, et si vous le faites, détruisez la carte, puis piochez 1 carte.*

    Le second effet de *Yazi* peut-il être activé ?

    <details>
    <summary>Réponse</summary>
    <p>

    <strong>Non.</strong><br>

    <i>Stellnova Alpha utilise "puis", ce qui veut dire que la destruction et la pioche ne sont pas simultanées. La destruction de Yazi n'est donc pas l'une des dernières actions à avoir lieu.</i>
    </p>
    </details>

2. Supposons maintenant que Joueur A active le second effet de *Yazi* dans le Cimetière, et que Joueur B l'annule avec *Stellnova Alpha*. Joueur B peut-il piocher 1 carte ?

    <details>
    <summary>Réponse</summary>
    <p>

    <strong>Non.</strong><br>

    <i>Puisque Yazi est dans le Cimetière, il ne peut pas être détruit par Alpha, et comme Alpha utilise "puis", Joueur B ne peut pas piocher.</i>
    </p>
    </details>

3. Qu'arrive-t-il au monstre "tellchevalier" que j'ai ciblé quand mon adversaire chaîne *Espace de Négation* (qui empêche d'Invoquer Spécialement) à mon *Satellchevalier Pont Célèste* ?
    - *Satellchevalier Pont Célèste* :

        *Ciblez 1 monstre "tellchevalier" que vous contrôlez ; Invoquez Spécialement 1 monstre "tellchevalier" de nom différent depuis votre Deck, et si vous le faites, mélangez le monstre ciblé dans le Deck.*

    <details>
    <summary>Réponse</summary>
    <p>

    <strong>Le monstre ciblé reste sur le Terrain.</strong><br>

    <i>Pont Célèste emploie "et si vous le faites", ce qui veut dire que si le monstre tellchevalier ne peut pas être Invoqué Spécialement, la cible ne peut pas être mélangée sur le Terrain.</i>
    </p>
    </details>

4. Mon adversaire peut-il activer *Hommage Torrentiel* en réponse à l'effet de *Satellchevalier Pont Célèste* en Chain Link 1 ?

    <details>
    <summary>Réponse</summary>
    <p>

    <strong>Oui.</strong><br>

    <i>Puisque Pont Célèste emploie "et si vous le faites", l'Invocation Spéciale et le retour dans le Deck sont les dernières actions à avoir lieu, donc Hommage Torrentiel peut être activé.</i>
    </p>
    </details>

Pour conclure, voici le post officiel sur le blog de Konami concernant les [conjonctions](https://yugiohblog.konami.com/articles/?p=4514).

Le prochain article portera sur les [Invocations](06_Invocations.md).

