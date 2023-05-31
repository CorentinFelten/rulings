# Démystification de rulings

# Effets Optionnels 'Lorsque'

Cet article concerne le point de règle souvent confus et mal interprété des effets optionnels 'lorsque'. 

Avant de commencer, n'oubliez pas de lire le dernier article sur le [SEGOC](3_Effets_Declencheurs.md) !

## Règle fondamentale des effets optionnels "lorsque"
**Un effet optionnel "lorsque" ne peut être activé que lorsque sa condition d'activation correspond à "l'une des dernières actions à se dérouler".**

Cette règle explique qu'il est nécessaire d'activer un effet optionnel "lorsque" **exactement** "lorsque" ce dernier rencontre sa condition d'activation. La difficulté réside dans savoir quand une action est "une des dernières actions à avoir lieu" du point de vue des mécaniques de jeu.

A noter que cette mécanique ne s'applique pas aux effets obligatoires, ni aux effets employant un "si" plutôt qu'un "lorsque".

Voyons un premier exemple :

Joueur A contrôle *Main de Feu*. Joueur B active *Typhon d'Espace Mystique* pour détruire une carte Posée, puis chaîne *Interruption de Raigeki*, ciblant *Main de Feu* pour la détruire.
- *Interruption de Raigeki* :

    *Défaussez 1 carte, puis ciblez 1 carte sur le Terrain ; détruisez-la.*
    
- *Main de Feu* :

    *<u>Lorsque</u> cette carte en votre possession est détruite par une carte de votre adversaire et envoyée à votre Cimetière : <u>vous pouvez</u> cibler 1 monstre qu'il contrôle ; détruisez la cible, puis vous pouvez Invoquer Spécialement 1 "Main de Glace" depuis votre Deck.*

<u>Chain Link 1</u> : *Typhon d'Espace Mystique*

<u>Chain Link 2</u> : *Interruption de Raigeki*

Résolution de la Chaîne :

<u>Chain Link 2</u> résoud : *Interruption de Raigeki* détruit *Main de Feu*

<u>Chain Link 1</u> résoud : *Typhon d'Espace Mystique* détruit sa cible

L'effet de *Main de Feu* est un "lorsque" optionnel, et sa destruction n'est pas l'une des dernières actions à avoir lieu. Son effet ne peut donc pas être activé dans ce cas de figure.

Cette règle s'applique également pour les cartes Magies et Pièges.

Joueur A active *Gobelin Parvenu*, et Joueur B décide de chaîner *Appel de l'Être Hanté*, afin d'Invoquer Spécialement *Dragon Blanc aux Yeux Bleus*. Joueur A a une *Trappe Sans Fond* de Posée sur le terrain.
- *Lorsque votre adversaire Invoque un ou plusieurs monstres avec min. 1500 ATK : détruisez ces monstres avec min. 1500 ATK, et si vous le faites, bannissez-les.*

<u>Chain Link 1</u> : *Gobelin Parvenu*

<u>Chain Link 2</u> : *Appel de l'Être Hanté*

Résolution de la Chaîne :

<u>Chain Link 2</u> résoud : *Appel de l'Être Hanté* invoque *Dragon Blanc aux Yeux Bleus*

<u>Chain Link 1</u> résoud : Joueur A pioche sa carte

*Trappe sans fond* utilise un "lorsque", activer une carte Magie / Piège est optionnel, et l'Invocation du monstre n'était pas "l'une des dernières actions à avoir lieu", donc elle ne peut pas être activée, tout comme l'exemple avec *Main de Feu*.

## Plus d'exemples
Jusque là, il était assez évident de déterminer si la condition d'activation était "l'une des dernières choses à avoir lieu" ou non. Nous allons maintenant nous pencher sur des cas légèrement plus complexes. 

Joueur A active la Magie de Terrain *Ville des Engrenages* :
- *Lorsque cette carte est détruite et envoyée au Cimetière : vous pouvez Invoquer Spécialement 1 monstre "Rouages Ancients" depuis votre main, Deck ou Cimetière.*

A noter que cet effet déclencheur est un effet optionnel "lorsque", et donc est capable de manquer de s'activer si sa destruction n'est pas "l'une des dernières actions à avoir lieu".

Supposons que Joueur B chaîne *Typhon d'Espace Mystique* à l'activation de *Ville des Engrenages* du Joueur A sur le terrain.

<u>Chain Link 1</u> : Activation de *Ville des Engrenages* sur le terrain

<u>Chain Link 2</u> : *Typhon d'Espace Mystique* ciblant *Ville des Engrenages*

Résolution de la Chaîne :

<u>Chain Link 2</u> résoud : *Typhon d'Espace Mystique* détruit *Ville des Engrenages*

<u>Chain Link 1</u> résoud : *Ville des Engrenages* résoud sur le terrain (mais elle résoud sans effet puisqu'elle vient d'être détruite)

Notons que *Ville des Engrenages* a été détruite, mais son effet sur le terrain tente tout de même de se résoudre en tant que Chain Link 1. Dans cette situation, le fait que *Ville des Engrenages* "tente de se résoudre" est la dernière chose qui a lieu, tandis que sa destruction ne l'est pas. C'est pourquoi l'effet déclencheur de *Ville des Engrenages* manque de s'activer.

Supposons que Joueur B chaîne *Brouilleur Magique*, pour annuler l'activation de *Ville des Engrenages*.
- *Lorsqu'une Carte Magie est activée : défaussez 1 carte ; annulez l'activation, et si vous le faites, détruisez-la.*

<u>Chain Link 1</u> : Activation de *Ville des Engrenages* sur le terrain

<u>Chain Link 2</u> : *Brouilleur Magique*

Résolution de la Chaîne :

<u>Chain Link 2</u> résoud : *Brouilleur Magique* annule l'activation de *Ville des Engrenages* et la détruit

<u>Chain Link 1</u> résoud : (rien)

Comme *Brouilleur Magique* annule l'activation, les effets de *Ville des Engrenages* sur le terrain n'essaient pas de résoudre du tout. C'est pourquoi il est possible de dire que la destruction de *Ville des Engrenages* était effectivement l'une des dernières choses à avoir lieu, donc son effet déclencheur peut s'activer normalement. 

## Effet optionnels "Lorsque" et SEGOC
Both this article and the previous one have involved Trigger effects. Let’s see how this mechanic interacts with SEGOC.

Player A activates Dark Hole, destroying his Bixi, Water of the Yang Zing and Player B’s Card Trooper.
When this card you control is destroyed by battle or card effect and sent to your Graveyard: You can Special Summon 1 “Yang Zing” monster from your Deck in Attack Position, except “Bixi, Water of the Yang Zing”.

If this card you control is destroyed and sent to your Graveyard: Draw 1 card.

Chain Link 1: Dark Hole

Resolve the Chain: Dark Hole destroys Bixi and Card Trooper at the same time.

First we look at what effects want to activate. Bixi and Trooper’s effects were triggered, so they’re both candidates.

Let’s check if either is going to miss its activation timing. The destruction of Bixi and the destruction of Card Trooper were both the last thing to happen (and Card Trooper’s effect is mandatory), so both effects can activate.

Now that we’ve decided what needs to activate, we look at the order they need to activate in. Card Trooper is the NTP’s mandatory effect, and Bixi is the TP’s optional effect, so according to the rules of SEGOC, they activate in the next Chain this order:

Chain Link 1: Card Trooper
Chain Link 2: Bixi

(If the rules of SEGOC quoted here are unfamiliar, double-check last week’s article).

The key thing to take away here is that the activation of Card Trooper does not throw off the activation of Bixi. We checked to see if its activation condition was the last thing to happen after the Chain resolved, and then put everything onto the Chain.

## C'est l'heure du Quiz !

You can assume any effects are legal to activate – there are no trick questions here.

(1) Player A controls Lightpulsar Dragon and Cannon Soldier. Player A tributes Lightpulsar Dragon for the effect of Cannon Soldier.
When this card is sent from the field to the Graveyard: You can target 1 Level 5 or higher DARK Dragon-Type monster in your Graveyard; Special Summon that target.

You can Tribute 1 monster; inflict 500 damage to your opponent.

Can the effect of Lightpulsar Dragon be activated?

(2) Player A controls Trance Archfiend and Player B controls Ice Hand. Player A activates Dark Hole.
When this card you control is destroyed and sent to the Graveyard: You can target 1 of your banished DARK monsters; add that target to your hand.

When this card in your possession is destroyed by your opponent’s card (either by battle, or by card effect) and sent to your Graveyard: You can target 1 Spell/Trap Card they control; destroy that target, then you can Special Summon 1 “Fire Hand” from your Deck.

After Dark Hole resolves, what Chain forms?

(3) Player A activates the (second) effect of Bixi, Water of the Yang Zing, and Player B negates it with Divine Wrath.
When this card you control is destroyed by battle or card effect and sent to your Graveyard: You can Special Summon 1 “Yang Zing” monster from your Deck in Attack Position, except “Bixi, Water of the Yang Zing”. You can only use this effect of “Bixi, Water of the Yang Zing” once per turn. Once per turn, during your opponent’s Main Phase or Battle Phase, you can: Immediately after this effect resolves, Synchro Summon 1 Synchro Monster, using only “Yang Zing” monsters you control (this is a Quick Effect).

When a monster effect is activated: Discard 1 card; negate the activation, and if you do, destroy that monster.

Can the (first) effect of Bixi be activated?

(4) Suppose instead Player B Chains the effect of Ghost Ogre & Snow Rabbit (‘Yuki Usagi’) to the (second) effect of Bixi, in the above question.
During either player’s turn, when a monster on the field activates its effect, or when a Spell/Trap Card that is already face-up on the field activates its effect: You can send this card from your hand or your side of the field to the Graveyard; destroy that card on the field.

Can the (first) effect of Bixi be activated?


Réponses :
(1) No
Cannon Soldier tributes as a cost (tributing is written before the semi-colon) so the tributing of Lightpulsar is nowhere near the last thing to happen.
(If you’re wondering whether Lightpulsar Chains to the effect of Cannon Soldier or not, remember that trigger effects always activate after the current chain (if any) resolves.)

(2) Chain Link 1: The effect of Trance Archfiend
Chain Link 2: The effect of Ice Hand
Trance Archfiend and Ice Hand being destroyed are both one of the last things to happen, so both can activate. According to the rules of SEGOC, Player A’s optional effect goes first on the Chain, and Player B’s optional effect is second. Neither misses its chance to activate.

(3) Yes
Chain Link 1 is the effect of Bixi, and Chain Link 2 is Divine Wrath. Since Divine Wrath negates the activation of Bixi’s effect, Chain Link 1 vanishes, and the last thing to happen is Bixi’s destruction.

(4) No
Ghost Ogre & Snow Rabbit does not negate activations, so, resolving the Chain, Bixi’s destruction would not be the last thing to happen.
