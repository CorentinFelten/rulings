# Démystification de rulings

# 3. SEGOC
Les effets déclencheurs sont très présents dans Yu-Gi-Oh!, et leur fonctionnement est gouverné par quelques mécaniques de jeu.

Cet article partira du principe que vous êtes familier avec le concept de Chaîne. Si ce n'est pas le cas, ou bien pour un petit rafraîchissement, n'hésitez pas à relire le livret de règles officiel. 

Et n'oubliez pas de lire le dernier article sur le [ciblage](2_Ciblage.md).

## Règle fondamentale d'effets déclencheurs
**Les effets déclencheurs s'activent toujours après que la chaîne actuelle (si elle existe) soit résolue.**

Voyons un exemple. Supposons que *Tireur de l'Atlantide* et *Sirènemure Abyssgunde* sont défaussés par l'effet de *Sirènemure Abyssmégalo* en tant que coût. 
- *Tireur de l'Atlantide* :
  
  *Lorsque cette carte est envoyée au Cimetière pour activer un effet de monstre EAU : ciblez 1 carte Posée contrôlée par votre adversaire ; détruisez la cible.*

- *Sirènemure Abyssgunde* :

    *Si cette carte est défaussée au Cimetière : vous pouvez cibler 1 monstre "Sirènemure" ("Sirènemure Abyssgunde" exclu) dans votre Cimetière ; Invoquez Spécialement la cible.*

- *Sirènemure Abyssmégalo* :

    *Vous pouvez défausser 2 autres monstres EAU au Cimetière ; Invoquez Spécialement cette carte depuis votre main. Lorsqu'elle est Invoquée de cette façon : vous pouvez ajouter 1 Magie/Piège "-Abysses" depuis votre Deck à votre main. Vous pouvez Sacrifier 1 autre monstre EAU en Position d'Attaque ; durant chaque Battle Phase ce tour, cette carte peut faire une seconde attaque.*

<ins>Chain Link 1</ins> : L'effet de *Megalo* pour s'invoquer, défaussant *Tireur de l'Atlantide* et *Gunde*. A noter que l'effet de *Megalo* démarre effectivement une chaîne, puisque son effet possède un point-virgule.

Les effets de *Tireur* et de *Gunde* ne s'activent pas encore, bien qu'ils aient techniquement rempli leurs conditions d'activation. Ils attendent que la Chaîne en cours soit résolue avant de s'activer.

<ins>Résolution de Chaîne</ins> : *Megalo* est Invoqué Spécialement.

A ce moment là, on regarde quels effets ont été déclenchés et veulent s'activer. *Tireur* et *Gunde* ont attendu, et à ce moment précis le second effet de *Megalo* a également été déclenché.

Cette situation, lorsque plusieurs effets déclencheurs veulent s'activer en même temps, est appelée SEGOC : Simultaneous Effects Go On Chain (ou Effets Simultanés Vont En Chaîne en français, mais nous resterons avec le terme de SEGOC lors de cette série).

(Note importante : la situation de 'Missing Timing' (ou les effets optionnels 'When' VS 'If') sera expliquée dans le prochain article, et ne sera pas abordée dans celui-ci.)

## SEGOC
**Lorsque plusieurs effets déclencheurs veulent s'activer en même temps, ils le font dans l'ordre suivant :**
1. JT - Obligatoire
2. NJT - Obligatoire
3. JT - Optionnel
4. NJT - Optionnel

(où **JT** = Joueur du Tour et **NJT** = Non-Joueur du Tour)

Comme d'habitude, voyons ce concept directement avec un exemple :

Joueur A contrôle *Dante, Voyageur des Abysses Ardents*, avec *Cir, Malebranche des Abysses Ardents* comme Matériel Xyz. Joueur B contrôle *Bête Marionnette de l'Ombre*. C'est le tour du Joueur A, et il active *Trou Noir*.
- *Dante, Voyageur des Abysses Ardents* :
    
    *Si cette carte est envoyée au Cimetière : vous pouvez cibler 1 carte "Abysses Ardents" (cette carte exclue) dans votre Cimetière ; ajoutez-la à votre main.*

- *Cir, Malebranche des Abysses Ardents* :
    
    *Si cette carte est envoyée au Cimetière : vous pouvez cibler 1 monstre "Abysses Ardents" ("Cir, Malebranche des Abysses Ardents" exclu) dans votre Cimetière ; Invoquez-le Spécialement.*

- *Bête Marionnette de l'Ombre* :
    
    *Si cette carte est envoyée au Cimetière par un effet de carte : vous pouvez piocher 1 carte.*

<ins>Chain Link 1</ins> : *Trou Noir*

<ins>Résolution</ins> : *Trou Noir* détruit *Dante* et *Beast*, et *Cir* est également envoyé au Cimetière, le tout simultanément.

*Dante* et *Cir* sont tous deux des effets optionnels du **JT**, et rencontrent tous deux leurs conditions d'activation au même moment. Ils iront donc sur la Chaîne en premier en tant que CL1 et CL2 dans l'ordre du choix du **JT**. *Bête* déclenche son effet optionnel pour le **NJT**, donc il viendra après les deux premiers en tant que CL3. 

<ins>Chain Link 1</ins> et <ins>Chain Link 2</ins> : *Dante* et *Cir* (peu importe l'ordre)

<ins>Chain Link 3</ins> : *Bête*

Revenons à l'exemple avec *Tireur*, *Gunde* et *Megalo* :
- *Tireur de l'Atlantide* :
  
  *Lorsque cette carte est envoyée au Cimetière pour activer un effet de monstre EAU : ciblez 1 carte Posée contrôlée par votre adversaire ; détruisez la cible.*

- *Sirènemure Abyssgunde* :

    *Si cette carte est défaussée au Cimetière : vous pouvez cibler 1 monstre "Sirènemure" ("Sirènemure Abyssgunde" exclu) dans votre Cimetière ; Invoquez Spécialement la cible.*

- *Sirènemure Abyssmégalo* :

    *Vous pouvez défausser 2 autres monstres EAU au Cimetière ; Invoquez Spécialement cette carte depuis votre main. Lorsqu'elle est Invoquée de cette façon : vous pouvez ajouter 1 Magie/Piège "-Abysses" depuis votre Deck à votre main. Vous pouvez Sacrifier 1 autre monstre EAU en Position d'Attaque ; durant chaque Battle Phase ce tour, cette carte peut faire une seconde attaque.*

<ins>Chain Link 1</ins> : Effet de *Megalo* pour s'Invoquer Spécialement, en défaussant *Tireur* et *Gunde*

<ins>Résolution</ins> : *Mégalo* s'Invoque Spécialement

*Tireur*, *Gunde* et *Megalo* on tous les trois validé la condition d'activation de leurs effets. *Tireur* est un effet obligatoire du **JT**, donc il s'active en premier. *Gunde* et *Megalo* sont tous deux des effets optionnels du **JT**, donc ils peuvent être activés dans l'ordre du choix du **JT**.

<ins>Chain Link 1</ins> : *Tireur*, ciblant une carte Posée
<ins>Chain Link 2</ins> : *Gunde*, ciblant un Sirènemure dans le Cimetière
<ins>Chain Link 3</ins> : second effet de *Megalo*

Les Chaînes ont été développées entièrement dans les exemples ci-dessus, car c'est une bonne pratique de les construire correctement et les résoudre attentivement. 

## Points divers
Il est important de s'assurer que tous les effets déclencheurs ont été utilisés pour la construction de la Chaîne avant qu'un des joueurs puisse Chaîner des effets rapides. Même les cartes Pièges Contre ne peuvent pas être utilisées pendant que des effets déclencheurs sont ajoutés à la Chaîne. Ce point est important, car pour pouvoir annuler l'activation d'un effet, il faut que l'effet soit Chaîné directement à cette activation.

Certaines cartes Magies et Piège ont des effets qui s'activent lorsqu'une condition est remplie, pendant que la carte Magie / Piège est face recto. Ces effets sont comparables à des effets déclencheurs, et fonctionnent de la même manière que les effets déclencheurs. Ils respecteront ainsi les règles de SEGOC. 

Un bon exemple de ce type d'effet est le second effet d'*Espace de Négation* :
- *Aucun joueur ne peut Invoquer Spécialement de monstres. Si une carte est envoyée depuis le Deck ou Terrain à votre Cimetière : détruisez cette carte.*

Quelques avertissements :
1. SEGOC ne s'applique pas sur les effets s'activant durant une Phase ou Step précise (par exemple lors de la Standby Phase, ou la End Step de la Battle Phase). Ces effets s'activent et se résolvent dans des Chaînes séparées.

Par exemple, supposons que vous avez deux *Lyla la Magicienne, Seigneur Lumière* sur le terrain :
- *Une fois par tour, durant votre End Phase : envoyez les 3 cartes du dessus de votre Deck au Cimetière.*

Les effets des deux Lyla ne forment pas une Chaîne durant la End Phase : ils s'active et se résolvent séparément.

2. Il existe une exception unique à la règle de SEGOC. Pour résumer, il n'est pas possible d'activer plusieurs effets déclencheurs qui implique une Invocation Spéciale de la main (ou des effets déclencheurs qui s'activent de la main et qui Invoquent Spécialement). Par exemple, il n'est pas possible d'activer 1 *Gorz, l'Émissaire des Ténèbres* et 1 *Tragoedia* en réponse à une attaque, malgré le fait qu'en appliquant strictement la règle de SEGOC, les deux cartes s'activeraient en Chaîne. 
- *Gorz, l'Émissaire des Ténèbres* :

    *Lorsque vous recevez des dommages d'une carte possédée par votre adversaire : vous pouvez Invoquer Spécialement cette carte depuis votre main.*

- *Tragoedia* :

    *Lorsque vous recevez des dommages de combat : vous pouvez Invoquer Spécialement cette carte depuis votre main.*

## C'est l'heure du Quiz !

1. Joueur A attaque le *Mathématicien* du Joueur B avec son propre *Mathématicien*. Les deux monstres sont détruits par le combat et leurs effets se déclenchent :
   
   *Lorsque cette carte est détruite au combat et envoyée au Cimetière : vous pouvez piocher 1 carte.*

    Quel joueur **pioche** en premier ?

2. Joueur A active *Changement de Masque* sur *Zéro Absolu, HÉROS Élémentaire*, afin d'invoquer spécialement *Acid, HÉROS Masqué*.
   - *Changement de Masque* :
       
       *Ciblez 1 monstre "HÉROS" que vous contrôlez ; envoyez-le au Cimetière, et aussi, après ça, s'il a quitté le Terrain par cet effet, Invoquez Spécialement 1 monstre "HÉROS Masqué" du même Attribut que le monstre envoyé avait lorsqu'il était sur le Terrain (son Attribut d'origine, si face verso) depuis votre Extra Deck.*

   - *Zéro Absolu, HÉROS Élémentaire* :
       
       *Si cette carte quitte le Terrain : détruisez tous les monstres contrôlés par votre adversaire.*

   - *Acid, HÉROS Masqué* :
       
       *Lorsque cette carte est Invoquée Spécialement : détruisez autant de Magies/Pièges contrôlés par votre adversaire que possible, et si vous le faites, tous les monstres qu'il contrôle perdent 300 ATK*

    Quelle Chaîne est formée après résolution du *Changement de Masque* ?

3. En continuant sur la situation précédente, Joueur B possède une *Colère Divine* de Posée. 
   - *Lorsqu'un effet de monstre est activé : défaussez 1 carte ; annulez l'activation, et si vous le faites, détruisez le monstre.*

    Joueur B peut-il annuler l'effet de *Zéro Absolu* avec *Colère Divine* ? Joueur B peut-il annuler l'effet de *Acid* ?

4. Joueur A contrôle *Espace de Négation* et *La Troupe Exilée*. Joueur B contrôle *Faucon Marionnette de l'Ombre*. Joueur A Sacrifie *La Troupe Exilée* pour détruire *Faucon Marionnette de l'Ombre*.
   - *Espace de Négation* :

       *Aucun joueur ne peut Invoquer Spécialement de monstres. Si une carte est envoyée depuis le Deck ou Terrain à votre Cimetière : détruisez cette carte.*

   - *La Troupe Exilée* :
     
       *Vous pouvez Sacrifier cette carte, puis ciblez 1 monstre sur le Terrain ; détruisez la cible.*

   - *Faucon Marionnette de l'Ombre* :
       
       *Si cette carte est envoyée au Cimetière par un effet de carte : vous pouvez l'Invoquer Spécialement en Position de Défense face verso.*

    A quel moment *Espace de Négation* active-t'il son second effet ? *Faucon Marionnette de l'Ombre* peut-il s'activer ?

5. Est-il possible d'activer l'effet de deux *Kagetokage* en réponse à la même Invocation Normale ?
   - *Lorsque vous Invoquez Normalement un monstre de Niveau 4 : vous pouvez Invoquer Spécialement cette carte depuis votre main.*

<details>
<summary>Réponses</summary>
    
 1. **Le NJT pioche en premier.** 
   
      *Les deux Mathématiciens veulent s'activer au même moment, ils construisent donc une Chaîne en accordance avec le SEGOC :*
      
      *CL1 : Mathématicien du **JT***
      
      *CL2 : Mathématicien du **NJT***

      *La Chaîne se résoud dans le sens inverse de sa construction.*

      
 2. **Peu importe l'ordre !** 
   
      *Acid et Zéro Absolu veulent tous les deux activer leur effet après la résolution de Mask Change, ils forment donc une Chaîne en respectant le SEGOC. Les deux effets sont des effets obligatoires du **JT**, donc ce dernier décide de leur ordre d'activation.*
 
 3. ***Colère Divine* ne pourra annuler que l'effet du second monstre dans la Chaîne.** 
      
      *Zéro Absolu et Acid entrent au même moment dans la Chaîne en tant qu'effets déclencheurs. Colère Divine ne pourra être ajoutée à la Chaîne qu'après les deux effets déclencheurs, et doit être chaîné directement à l'effet qu'elle tente d'annuler.*

 4. ***Espace de Négation* s'active après que l'effet de *Troupe Exilée* ait été résolu. L'effet de *Faucon* ne pourra pas être activé.** 
 
      *Bien que l'effet d'Espace de Négation soit déclenché immédiatement, il n'est pas chaîné à l'effet de Troupe Exilée : il attend de s'activer dans la Chaîne suivante. Après la résolution de Troupe Exilée, Espace de Négation et Faucon ont tous deux été déclenchés, mais comme Espace de Négation est encore sur le terrain à ce moment précis, son effet continu s'applique toujours, donc l'effet de Faucon ne peut pas être activé.*

 5. **Ce n'est pas possible.** 
 
      *L'effet déclencheur de Kagetokage implique une invocation spéciale de la main, donc il n'est possible d'en activer qu'un seul.*
</details>

Le prochain article portera sur les [effets optionnels 'Lorsque'](4_When_Optionnels.md).
