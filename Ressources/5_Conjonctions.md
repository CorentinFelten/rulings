# Démystification de rulings

# Conjonctions
Une conjonction, en PSCT, est un mot / ensemble de mots qui joint deux parties d'un effet. Elle contient beaucoup d'informations sur la manière dont un effet marche en un seul groupe de mots, ce qui en fait un élément crucial du PSCT. 

Avant de commencer, n'oubliez pas de lire le dernière article sur les [effets déclencheurs "lorsque" optionnels](4_When_Optionnels.md).

## Introduction
Les 4 conjonctions principales sont *puis*, *et si vous le faites*, *et aussi* et *aussi, après cela*. Voici quelques exemples :
- *Le Livre de la Vie* :

    *Ciblez 1 monstre Zombie dans votre Cimetière et 1 monstre dans le Cimetière de votre adversaire ; Invoquez Spécialement la première cible, <ins>et aussi</ins>, bannissez la seconde cible.*

Ici, l'effet est de la forme 'faire A, et aussi faire B', où A est l'Invocation Spéciale de la première cible, et B le bannissement de la seconde cible. La structure est similaire pour les autres conjonctions :
- *Nékroz de Valkyrus* :
    
    *Lorsqu'un monstre de l'adversaire déclare une attaque : vous pouvez bannir 1 carte "Nékroz" depuis votre Cimetière et défausser cette carte ; annulez l'attaque, <ins>puis</ins> terminez la Battle Phase.*

Ici, l'effet est de la forme 'faire A, puis faire B', où A est l'annulation d'attaque et B est la fin de la Battle Phase.

## Conjonctions et Créneaux
Le premier point que les conjonctions nous permettent d'identifier est de savoir si A et B sont simultanées ou non pour les effets optionnels "lorsque".

<ins>A et B sont simultanées</ins> :
- *et si vous le faites*
- *et aussi*

<ins>A et B ne sont pas simultanées</ins> :
- *puis*
- *aussi, après cela*

Pourquoi s'attarder sur ce point ? Souvenez-vous de la règle sur les effets optionnels "lorsque" de l'article précédent : *Un effet optionnel "lorsque" ne peut être activé uniquement quand sa condition d'activation est "l'une des dernières actions à avoir lieu".* Si A et B ne sont pas simultanées, alors A ne peut pas être l'une des dernières actions à avoir lieu.

Voyons un exemple : supposons que j'utilise *Voleur d'Esprit* sur *Dragon Pulsar de Lumière* :
- *Voleur d'Esprit* :

    *Ciblez 1 monstre face recto contrôlé par votre adversaire ; détruisez la cible, <ins>puis</ins> votre adversaire gagne 1000 LP.*

- *Dragon Pulsar de Lumière* :

    *<ins>Lorsque</ins> cette carte est envoyée depuis le Terrain au Cimetière : <ins>vous pouvez</ins> cibler 1 monstre TÉNÈBRES Dragon de min. Niveau 5 dans votre Cimetière ; Invoquez Spécialement la cible.*

(A noter que l'effet de *Dragon Pulsar de Lumière* est effectivement un effet optionnel "lorsque")

<ins>Chain Link 1</ins> : *Voleur d'Esprit*

L'emploi du *puis* dans l'effet de *Voleur d'Esprit* explique que la destruction et le gain de LP ne sont pas simultanés. Le gain de LP a lieu <ins>après</ins> la destruction en terme de timing. 

<ins>Résolution de la Chaîne</ins> : *Voleur d'Esprit* détruit *Dragon Pulsar*. Une fois le monstre détruit, mon adversaire gagne 1000 LP.

La destruction de *Dragon Pulsar* n'est donc pas l'une des dernières actions à avoir lieu, il manque donc son créneau d'activation.

Supposons maintenant que j'active l'effet de *Numéro 50 : Bateau Noir de Maïs* sur *Dragon Pulsar de Lumière* (on suppose également que j'ai réduit l'ATK de *Dragon Pulsar* pour qu'elle soit plus basse que celle du *Bateau*) :
- *Numéro 50 : Bateau Noir de Maïs* :

    *Une fois par tour : vous pouvez détacher 1 Matériel Xyz de cette carte, puis ciblez 1 monstre face recto contrôlé par votre adversaire avec une ATK inférieure ou égale à l'ATK de cette carte ; envoyez-le au Cimetière, <ins>et si vous le faites</ins>, infligez 1000 points de dommages à votre adversaire.*

<ins>Chain Link 1</ins> : effet de *Numéro 50 : Bateau Noir de Maïs*

Cette fois-ci, la conjonction est *et si vous le faites*, ce qui veut dire que l'envoi au Cimetière et le fait d'infliger des dommages sont simultanés à la résolution.

<ins>Résolution de la Chaîne</ins> : *Dragon Pulsar de Lumière* est envoyé au Cimetière, et au même moment mon adversaire prend 1000 points de dommages.

La condition d'activation de l'effet de *Dragon Pulsar* est l'une des dernières actions à avoir lieu, donc son effet peut être activé. 

A noter que les effets ici étaient en Chain Link 1, et la résolution serait différente s'ils étaient Chain Link 2 ou plus. Surveillez toujours les dernières actions à avoir lieu.

## Conjonctions et Résolutions

Les conjonctions nous expliquent également la quantité à résoudre d'un effet si un autre effet perturbateur est chaîné. Ce type d'effet devrait vous rappeler la discussion sur le mot 'cible' étant utilisé après le point-virgule, dans le [deuxième article](2_Ciblage.md) de cette série.

<ins>A est requis pour B</ins> :
- *et si vous le faites*
- *puis*

<ins>A n'est pas requis pour B</ins> :
- *et aussi*
- *aussi, après cela*

B n'est jamais requis pour A : si B n'est pas réalisable à la résolution de l'effet, A sera tout de même résolue (on dit qu'on résout l'effet autant que possible).

Supposons que je déclare une attaque. Mon adversaire active l'effet de *Nékroz de Valkyrus* pour annuler mon attaque, mais je chaîne *Le Livre de la Lune* pour passer mon monstre face verso.
- *Nékroz de Valkyrus* :
    
    *Lorsqu'un monstre de l'adversaire déclare une attaque : vous pouvez bannir 1 carte "Nékroz" depuis votre Cimetière et défausser cette carte ; annulez l'attaque, <ins>puis</ins> terminez la Battle Phase.*

*Valkyrus* ne peut donc plus annuler l'attaque, puisque le monstre n'est plus entrain d'attaquer. Comme *Valkyrus* utilise la conjonction *puis*, il ne pourra pas terminer la Battle Phase.

Supposons maintenant que j'active *Le Livre de la Vie*, et que mon adversaire utilise son *Corbeau D.D.* pour bannir ma cible de type Zombie dans mon Cimetière.
- *Le Livre de la Vie* :

    *Ciblez 1 monstre Zombie dans votre Cimetière et 1 monstre dans le Cimetière de votre adversaire ; Invoquez Spécialement la première cible, <ins>et aussi</ins>, bannissez la seconde cible.*

Comme *Le Livre de la Vie* utilise la conjonction *et aussi*, bien que je ne puisse pas Invoquer Spécialement ma première cible, la seconde cible sera tout de même bannie.

## 'Et'
Il existe une conjonction supplémentaire, en plus des 4 mentionnées plus haut : *et*. Lorsqu'un effet dit 'faire A et B', il explique que A et B sont simultanés en terme de timing. Cependant, contrairement à *et si vous le faites* et *et aussi*, la conjonction demande de pouvoir réaliser A et B à la résolution, et dans le cas où l'un des deux n'est pas réalisable, l'effet ne fera rien.

Par exemple, *Numéro 53 : Heart-eartH* utilise la conjonction *et* :
- *Lorsque cette carte sur le Terrain est détruite par un effet de carte tant qu'elle n'a pas de Matériel Xyz : vous pouvez Invoquer Spécialement 1 "Numéro 92 : Dragon Heart-eartH" depuis votre Extra Deck et lui attacher cette carte depuis le Cimetière comme Matériel Xyz. (Cette Invocation Spéciale est traitée comme une Invocation Xyz.)*

Dans cet effet, la partie A est l'Invocation Spéciale de *Numéro 92*, et la partie B est attacher *Numéro 53* en tant que Matériel Xyz. Si *Corbeau D.D.* bannit *Numéro 53* du Cimetière, l'effet n'Invoquera pas *Numéro 92*. Aussi, l'Invocation Spéciale et le fait d'attacher sont simultanés en terme de timing, donc si cette action a lieu en Chain Link 1, *Hommage Torrentiel* peut être activé en réponse à l'Invocation.

## Divers
Comment retenir toutes ces conjonctions ? La façon dont elles sont écrites est d'une aide précieuse : *et si vous le faites* et *puis* suggèrent que B est dépendant de la bonne résolution de A, *puis* et *après cela* suggèrent que les deux parties de l'effet ne sont pas simultanées, etc. Avec de l'entraînement, ces conjonctions ne sont pas compliquées à retenir, et vous pourrez toujours les revérifier en cas d'oubli.

Quelques points importants :

1. Les conjonctions sont une des dernières additions au PSCT. Il existe donc quelques cartes écrites en PSCT qui utilisent *et* alors qu'elle veulent dire *et si vous le faites*, parce que ces cartes ont été rédigées avant que les conjonctions soient introduites, et elles n'ont pas encore été réimprimées. La conjonction *et* est très rare, donc si vous la croisez, n'hésitez pas à vérifier si la carte veut bien dire *et* ou si elle veut en réalité dire *et si vous le faites*.
2. Les conjonctions ne mentionnent rien concernant la légalité d'activation ! Elles n'expliquent que comment résoudre l'effet. Par exemple, il n'est pas légal d'activer *Le Livre de la Vie* sous *Mur de Fer Impérial*, bien qu'il ne soit pas nécessaire de bannir un monstre pour pouvoir Invoquer de nouveau la première cible. 

Nous reviendrons sur la légalité d'activation dans un article futur.

## C'est l'heure du Quiz !
1. Joueur A active le premier effet de *Yazi, Mal du Yang Zing*, et Joueur B l'annule avec *Stellnova Alpha* :

    - *Yazi, Mal du Yang Zing* :

        - *Vous pouvez cibler 1 monstre "Yang Zing" que vous contrôlez et 1 carte contrôlée par votre adversaire ; détruisez-les.*
        - *Lorsque cette carte que vous contrôlez est détruite au combat ou par un effet de carte, et envoyée à votre Cimetière : vous pouvez Invoquer Spécialement 1 monstre Wyrm depuis votre Deck en Position de Défense.*

    - *Stellnova Alpha* :

        *Lorsqu'une Carte Magie/Piège ou un effet de monstre est activé : envoyez 1 monstre "tellchevalier" face recto que vous contrôlez au Cimetière ; annulez l'activation, et si vous le faites, détruisez la carte, puis piochez 1 carte.*

    Le second effet de *Yazi* peut-il être activé ?

2. Supposons maintenant que Joueur A active le second effet de *Yazi* dans le Cimetière, et que Joueur B l'annule avec *Stellnova Alpha*. Joueur B peut-il piocher 1 carte ?

3. Qu'arrive-t-il au monstre "tellchevalier" que j'ai ciblé quand mon adversaire chaîne *Espace de Négation* (qui empêche d'Invoquer Spécialement) à mon *Satellchevalier Pont Célèste* ?
    - *Satellchevalier Pont Célèste* :

        *Ciblez 1 monstre "tellchevalier" que vous contrôlez ; Invoquez Spécialement 1 monstre "tellchevalier" de nom différent depuis votre Deck, et si vous le faites, mélangez le monstre ciblé dans le Deck.*

4. Mon adversaire peut-il activer *Hommage Torrentiel* en réponse à l'effet de *Satellchevalier Pont Célèste* en Chain Link 1 ?

<details>
<summary>Réponses</summary>
    
 1. **Non.** 
   
      *Stellnova Alpha utilise "puis", ce qui veut dire que la destruction et la pioche ne sont pas simultanées. La destruction de Yazi n'est donc pas l'une des dernières actions à avoir lieu.*
      
 2. **Non.** 
   
      *Puisque Yazi est dans le Cimetière, il ne peut pas être détruit par Alpha, et comme Alpha utilise "puis", Joueur B ne peut pas piocher.*
 
 3. **Le monstre ciblé reste sur le terrain.** 
      
      *Pont Célèste emploie "et si vous le faites", ce qui veut dire que si le monstre tellchevalier ne peut pas être Invoqué Spécialement, la cible ne peut pas être mélangée sur le terrain.*

 4. **Oui.** 
 
      *Puisque Pont Célèste emploie "et si vous le faites", l'Invocation Spéciale et le retour dans le Deck sont les dernières actions à avoir lieu, donc Hommage Torrentiel peut être activé.*
</details>

Pour conclure, voici le post officiel sur le blog de Konami concernant les [conjonctions](https://yugiohblog.konami.com/articles/?p=4514).

Le prochain article portera sur les [Invocations](6_Invocations.md).

