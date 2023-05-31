# Démistification de rulings

# 0. Introduction
Yu-Gi-Oh! est un jeu de carte assez complexe et demande beaucoup de lecture, et beaucoup de rulings et de mécaniques qui semblent très complexes. Vous vous dites peut être que d'apprendre les rulings complexes n'en vaut pas l'effort. Cependant, ce n'est pas le cas : un grand nombre de mécaniques du jeu est en réalité assez simple, et c'est mon but d'apporter les rulings et mécaniques de jeu les plus courantes à vous, les joueurs, de manière accessible. 

Ce post est le premier dans une série d'articles, qui va passer à travers les mécaniques clefs du jeu.

## Pourquoi s'embêter avec l'apprentissage de rulings ?
Je peux penser à au moins cinq raisons pour justifier apprendre les rulings :
1. Connaître les rulings peut vous aider à jouer mieux. Pour donner quelques exemples :
   - Si vous savez comment marche *Skill Drain*, vous saurez que vous pouvez jouer autour en activant un effet de monstre et en chaînant *Book of Moon* pour mettre le monstre face verso, et que *Skill Drain* n'annule pas les effets de monstres comme *Cardcar D.*.
   - Si vous ne lisez pas en détail *Dante, Traveler of the Burning Abyss* attentivement, vous pourriez avoir une mauvaise surprise en apprenant que son effet s'active même quand vous activez *Solemn Strike* sur son invocation.
   - *Fire Hand* et *Ice Hand* ont des effet optionnels "when", donc il est parfois possible de jouer autour de leurs effets et les empêcher de s'activer.
   - Il n'est pas possible d'utiliser *Effect Veiler* tant que l'effet du monstre adverse est déjà annulé. Si vous invoquez *Evilswarm Exciton Knight* et activez son effet, et que votre adversaire chaîne *Fiendish Chain*, gardez votre *MST* ! Vous pourrez ensuite activer l'effet de *Exciton Knight* dans une nouvelle chaîne, puis chaîner *MST* pour que votre adversaire ne puisse pas activer *Effect Veiler* durant cette chaîne !

2. Connaître des rulings peut vous permettre d'éviter d'atterrir dans des game states illégaux. Par exemple, si vous activez *Card Destruction* et défaussez *Shaddoll Hedgehog* et *Broww, Huntsman of Dark World* au Cimetière, *Broww* doit être Chain Link 1 et *Hedgehog* Chain Link 2 dans la chaîne d'après, donc vous devrez d'abord tuto puis piocher. Si vous piochez puis tuto, votre adversaire ne pourra pas dire quelle carte vous aurez pioché, donc le game state ne pourra pas être réparé. Cette erreur pourrait vous coûter une game loss dans le pire des cas, et vous devriez remettre la tuto de *Hedgehog* dans le meilleur des cas.

3. La connaissance de rulings aide pour la construction de decks. En connaissant bien vos rulings, lire une nouvelle carte et comprendre comment elle s'intègre dans un deck uniquement en lisant son texte devient beaucoup plus facile, surtout pour déterminer si la carte sera intéressante ou non.

4. Être à l'aise avec les rulings peut vous faire gagner à vous, votre adversaire, et votre Judge, du temps dans un duel, ce qui peut être crucial, surtout dans des tournois ayant une limite de temps.

5. Être à l'aise avec les rulings libère de la charge mentale pour vous aider à vous concentrer sur un jeu optimal.


## Pour commencer
Nous commencerons à apprendre différents rulings dans le post prochain. Pour le moment, il serait une bonne idée de jeter un oeil au dernier livret de règles officiel. Même si vous jouez depuis des années, il y a quelques points intéressants ici et là, et le lire vous mettra à jour pour le reste de cette série d'articles. 

Les pages suivantes sont particulièrement importantes :
- page **12-13** : Information sur les monstres Pendules et les invocations Pendule
- page **15** : Comment effectuer une invocation Xyz correcte
- page **21** : Invocation Spéciale via un effet de carte
- page **27** : Différence entre Carte Magie et Carte Piège posées
- page **41** : Spell Speeds
- page **45-51** : Rulings divers

D'autres sections du livret de règles, comme la **Damage Step**, seront étudiées et expliquées en détail au fur et à mesure de la progression de cette série. 

Lecture finie ? Dans ce cas...

## C'est l'heure du Quiz !
Voici quelques questions rapides pour tester des points importants. Les réponses peuvent toutes être trouvées dans les pages listées plus haut dans le livret de règles. Vous devriez pouvoir toutes les trouver.

1. Quelles cartes correspondent à un Spell Speed d'exactement 2 ?
   - Cartes Piège Contre
   - Cartes Magie Continue
   - Cartes Magie Rapide
   - Un effet déclencheur de Monstre


2. Quelles cartes peuvent être activées le tour où elles sont posées ?
   - Cartes Magie Terrain
   - Cartes Magie Continue
   - Cartes Magie Rapide
   - Cartes Piège Contre


3. Quelles actions démarrent une Chaîne ?
   - Invocation Normale d'un Monstre
   - Invocation Pendule de 2 Monstres de la main
   - Activataion d'une Magie Continue
   - Déclaration d'attaque


4. Vrai ou Faux : les Matériels Xyz sont des cartes sur le terrain.

5. Vrai ou Faux : Si vous envoyez un Monstre Synchro de votre Extra Deck au Cimetière, vous pouvez ensuite l'invoquer par Invocation Spéciale depuis le Cimetière avec des effets de cartes.

<details>
<summary>Réponses</summary>
    
 1. **Les Magies Rapides et les Pièges Continus.** *Comme expliqué page 41, seuls ces deux types de cartes ont un Spell Speed 2.*
 2. **Les Magies Terrain et les Magies Continues.** *Comme expliqué page 27, seules les Cartes Magies peuvent être activées le tour où elles ont été posées, sauf les Cartes Magies Rapides.*
 3. **Activer une Carte Magie Continue.** *Les autres actions ne démarrent pas une chaîne, comme mentionné explicitement page 47.*
 4. **Faux.** *Les Matériels Xyz sont également expliqués page 47.*
 5. **Faux.** *Ce point est expliqué page 21.*
</details>



# 1. PSCT
Vos cartes vous expliquent plus leur fonctionnement qu'observable de premier abord. Les cartes sorties, ou réimprimées, après 2011, soit presque toutes les cartes utilisées aujourd'hui, ont été écrites en *Problem Solving Card Text* (PSCT, Texte de Carte pour de la Résolution de Problèmes). Cela veut dire qu'avec un peu de connaissances, il est possible de connaître beaucoup d'informations supplémentaires sur le fonctionnement d'un effet de carte, et ce uniquement depuis leur texte. 

## PSCT et Chaînes
A travers le PSCT, il est possible de dire si un effet démarre une Chaîne ou non. En plus de l'importance évidente des Chaînes dans Yu-Gi-Oh!, certaines cartes mentionnent des effets activés, comme *Majesty's Fiend* et *Shadow-Imprisoning Mirror*, donc il est important de savoir quels effets s'activent et lesquels ne s'activent pas.

**Un effet démarre une Chaîne si, et seulement si, il a un deux-points *( : )* ou un point-virgule *( ; ).***

Par exemple, prenez *Graff, Malebranche des Abysses Ardents* : 


- *Si vous contrôlez un monstre (monstres "Abysses Ardents" exclus), détruisez cette carte. Vous ne pouvez utiliser qu'1 de ces effets de "Graff, Malebranche des Abysses Ardents" par tour, et uniquement une fois le tour.*
  - *Si vous ne contrôlez aucune Carte Magie/Piège : vous pouvez Invoquer Spécialement cette carte depuis votre main.*
  - *Si cette carte est envoyée au Cimetière : vous pouvez Invoquer Spécialement 1 monstre "Abysses Ardents" ("Graff, Malebranche des Abysses Ardents" exclu) depuis votre Deck.*

Quel effet de *Graff* démarre une Chaîne ? On peut voir que son effet d'Invoquer Spécialement depuis le deck démarre une Chaîne, puisqu'il a un deux-points dedans. On peut également voir que l'effet de s'Invoquer Spécialement depuis la main démarre ue Chaîne. Cependant, son effet de se détruire si le joueur ne contrôle pas de monstre "Abysses Ardents" ne démarre PAS de Chaîne, puisqu'il n'a ni deux-points ni point-virgule. 

Un autre exemple est *Perdez 1 Tour* :

- *Activez uniquement si vous ne contrôlez actuellement aucun monstre Invoqué Spécialement. Tant qu'un monstre est face recto sur le Terrain, annulez ses effets durant le tour où ce monstre a été Invoqué Spécialement. Si un ou plusieurs Monstres à Effet sont Invoqués Spécialement en Position d'Attaque : changez-les en Position de Défense.*

L'effet de changer un monstre en Position de Défense démarre une Chaîne, parce qu'il a un deux-points. Cependant, son effet d'annuler les effets de monstres n'en démarre pas, parce qu'il n'a ni deux-points ni point-virgule. 

Une Invocation Normale, attaque, pose d'un Monstre / Magie / Piège etc... ne démarrent PAS de Chaîne : ces points sont mentionnés dans le livret de règles page 47. Seules des activations de cartes et effets démarrent des Chaînes. Activer des Cartes Magies et Pièges démarrent toujours une Chaîne, peu importe la présence ou non de deux-points et point-virgule, et ceux apparaissant dans le texte sont présent simplement pour structurer l'effet. 

Toutes les phrases dans le texte d'une carte sans deux-points ou point-virgule ne sont pas des effets continus : certaines sont des conditions. Le PSCT n'est pas encore capable de les différentier pour nous, donc elles sont à interpréter au cas-par-cas. Par exemple, la première phrase de l'effet de *Denko Sekka* est une condition, tandis que la seconde est clairement un effet continu :

- *Non Invocable Spécialement. Tant que vous ne contrôlez aucune Magie/Piège Posé, aucun joueur ne peut ni Poser de Magies/Pièges ni activer de Cartes Magie/Piège qui sont Posées sur le Terrain.*

## PSCT et Coûts
Il est également possible de dire quand une action est à réaliser à l'activation de l'effet ou à sa résolution, afin de déterminer s'il s'agit d'un coût ou non.

**Une action est à effectuer à l'activation si, et seulement si, elle est écrite avant un point-virgule *( ; )*. Dans tous les autres cas, l'action est à réaliser en résolution.**

Par exemple, *Interruption de Raigeki* :
- *Défaussez 1 carte, puis ciblez 1 carte sur le Terrain ; détruisez-la.*

Vous pouvez défausser une carte et cibler à l'activation de *Interruption de Raigeki*, car ces actions sont écrites avant le point-virgule. 

Comparons cet effet à *Destriers Bête Spirituelle* :
- *Si vous contrôlez un monstre "Bête Spirituelle" : détruisez un nombre de monstres sur le Terrain, inférieur ou égal au nombre de monstres "Bête Spirituelle" que vous contrôlez actuellement.*

Il n'y a pas de point-virgule dans l'effet, donc le choix de destruction de monstres s'effectue à la résolution de l'effet. 

## PSCT et Conditions d'Activation
A quoi sert la virgule ? Ce point est un petit peu plus technique.

**Les Conditions d'Activation sont écrites avant une virgule *( , )*. Elles ont simplement besoin d'être vraies au moment de l'activation de l'effet.**

L'effet de *Chevalier Exciton Colonie du Mal* illustre bien ce point : 
- *Une fois par Chaîne, durant votre Main Phase ou la Battle Phase de votre adversaire, si votre adversaire a plus de cartes en tout dans sa main et sur son Terrain que vous (Effet Rapide) : vous pouvez détacher 1 Matériel de cette carte ; détruisez toutes les autres cartes sur le Terrain, et aussi, votre adversaire ne reçoit pas de dommages complémentaires ce tour.*

La partie "si votre adversaire a plus de cartes" est avant la virgule, donc il s'agit d'une condition d'activation. Elle explicite que l'adversaire doit avoir plus de cartes afin que l'effet soit activable. Donc même si l'adversaire Chaîne des cartes pour en avoir moins sur leur terrain à la résolution, l'effet d'*Exciton* aura quand même lieu.

Si une carte a une condition à l'activation ET la résolution, elle spécifiera quelque chose comme la dernière phrase de Grenouille d'Arbre (anciennement Rainette) :
- *Une fois par tour, durant votre Standby Phase, si cette carte est dans votre Cimetière et que vous ne contrôlez pas "Grenouille d'Arbre" : vous pouvez Invoquer Spécialement cette carte. <u>Vous ne devez contrôler aucune Carte Magie/Piège pour activer et résoudre cet effet.</u>*

## Assemblage des règles
Certains effets n'auront pas de conditions spécifiques pour activer leurs effets, ou même d'actions à effectuer à leur activation, donc ils n'auront pas besoin de deux-points ou point-virgules. Mais dans l'ensemble, un effet typique qui démarre une Chaîne aura la structure suivante :

