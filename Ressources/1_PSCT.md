# Démystification de rulings

# 1. PSCT
Vos cartes vous en expliquent plus sur leur fonctionnement que ce que l'on pourrait croire. Les cartes sorties, ou réimprimées, après 2011, soit une grande majorité des cartes utilisées aujourd'hui, ont été écrites en *Problem Solving Card Text* (PSCT, ou Texte de Carte pour de la Résolution de Problèmes). Cela veut dire qu'avec un peu de connaissances, il est possible de connaître beaucoup d'informations supplémentaires sur le fonctionnement d'un effet de carte, et ce uniquement depuis son texte. 

## PSCT et Chaînes
A travers le PSCT, il est possible de dire si un effet démarre une Chaîne ou non. En plus de l'importance évidente des Chaînes dans Yu-Gi-Oh!, certaines cartes mentionnent des effets activés, comme *Démon de la Majesté* et *Miroir Absorbant des Ténèbres*, donc il est important de savoir quels effets s'activent et lesquels ne s'activent pas.

**Un effet démarre une Chaîne si, et seulement si, il a un deux-points *( : )* ou un point-virgule *( ; ).***

Par exemple, prenez *Graff, Malebranche des Abysses Ardents* : 


- *Si vous contrôlez un monstre (monstres "Abysses Ardents" exclus), détruisez cette carte. Vous ne pouvez utiliser qu'1 de ces effets de "Graff, Malebranche des Abysses Ardents" par tour, et uniquement une fois le tour.*
  - *Si vous ne contrôlez aucune Carte Magie/Piège : vous pouvez Invoquer Spécialement cette carte depuis votre main.*
  - *Si cette carte est envoyée au Cimetière : vous pouvez Invoquer Spécialement 1 monstre "Abysses Ardents" ("Graff, Malebranche des Abysses Ardents" exclu) depuis votre Deck.*

Quel effet de *Graff* démarre une Chaîne ? On peut voir que son effet d'Invoquer Spécialement depuis le deck démarre une Chaîne, puisqu'il a un deux-points dedans. On peut également voir que l'effet de s'Invoquer Spécialement depuis la main démarre une Chaîne. Cependant, son effet de se détruire si le joueur ne contrôle pas de monstre "Abysses Ardents" ne démarre PAS de Chaîne, puisqu'il n'a ni deux-points ni point-virgule. 

Un autre exemple est *Perdez 1 Tour* :

- *Activez uniquement si vous ne contrôlez actuellement aucun monstre Invoqué Spécialement. Tant qu'un monstre est face recto sur le Terrain, annulez ses effets durant le tour où ce monstre a été Invoqué Spécialement. Si un ou plusieurs Monstres à Effet sont Invoqués Spécialement en Position d'Attaque : changez-les en Position de Défense.*

L'effet de changer un monstre en Position de Défense démarre une Chaîne, parce qu'il a un deux-points. Cependant, son effet d'annuler les effets de monstres n'en démarre pas, parce qu'il n'a ni deux-points ni point-virgule. 

Une Invocation Normale, attaque, pose d'un Monstre / Magie / Piège etc... ne démarrent PAS de Chaîne : ces points sont mentionnés dans le livret de règles page **47**. Seules des activations de cartes et effets démarrent des Chaînes. Activer des Cartes Magies et Pièges démarrent toujours une Chaîne, peu importe la présence ou non de deux-points et point-virgule, et ceux apparaissant dans le texte sont présent simplement pour structurer l'effet. 

Toutes les phrases dans le texte d'une carte sans deux-points ou point-virgule ne correspondent pas des effets continus : certaines sont des conditions. Le PSCT n'est pas encore capable de les différentier pour nous, donc elles sont à interpréter au cas-par-cas. Par exemple, la première phrase de l'effet de *Denko Sekka* est une condition, tandis que la seconde est clairement un effet continu :

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

La partie "si votre adversaire a plus de cartes" est avant la virgule, donc il s'agit d'une condition d'activation. Elle explicite que l'adversaire doit avoir plus de cartes afin que l'effet soit activable. Donc même si l'adversaire Chaîne des cartes pour en avoir moins sur son terrain à la résolution, l'effet d'*Exciton* se résoudra quand même.

Si une carte a une condition à l'activation ET la résolution, elle spécifiera quelque chose comme la dernière phrase de *Grenouille d'Arbre* (anciennement *Rainette*) :
- *Une fois par tour, durant votre Standby Phase, si cette carte est dans votre Cimetière et que vous ne contrôlez pas "Grenouille d'Arbre" : vous pouvez Invoquer Spécialement cette carte. <ins>Vous ne devez contrôler aucune Carte Magie/Piège pour activer et résoudre cet effet.</ins>*

## Assemblage des règles
Certains effets n'auront pas de conditions spécifiques pour activer leurs effets, ou même d'actions à effectuer à leur activation, donc ils n'auront pas besoin de deux-points ou point-virgules. Mais dans l'ensemble, un effet typique qui démarre une Chaîne aura la structure suivante :

<ins>Condition d'activation de l'effet</ins> : <ins>action à effectuer à son activation</ins> ; <ins>actions à effectuer lors de la résolution de l'effet</ins>

## C'est l'heure du Quiz !
Utilisez ce que l'ont vient d'apprendre pour répondre aux questions suivantes.

1. Quel(s) effet(s) démarre une chaîne ?
   - L'effet de *Grapha, Seigneur Dragon du Monde Ténébreux* de s'Invoquer Spécialement du Cimetière :
       
       *Vous pouvez Invoquer Spécialement cette carte (depuis votre Cimetière) en renvoyant 1 monstre "Monde Ténébreux" que vous contrôlez ("Grapha, Seigneur Dragon du Monde Ténébreux" exclu) à la main.*

   - L'effet de *Simorgh des Ténèbres* de s'Invoquer Spécialement depuis la main : 
     
      *Si cette carte est dans votre main : vous pouvez bannir 1 monstre TÉNÈBRES et 1 monstre VENT depuis votre Cimetière ; Invoquez Spécialement cette carte.*

   - Cet effet de *Cogneur Puissant U.A.* :

      *Si cette carte attaque, jusqu'à la fin de la Damage Step, votre adversaire ne peut ni activer de cartes ni d'effets.*

2. Quelle(s) action(s) sont des coûts ?
   - Défausser pour cet effet de *Uni-Zombie* : 

      *Vous pouvez cibler 1 monstre face recto sur le Terrain ; défaussez 1 carte, et si vous le faites, augmentez le Niveau de la cible de 1.*

   - Envoyer un monstre au Cimetière pour *Changement de Masque* :

      *Ciblez 1 monstre "HÉROS" que vous contrôlez ; envoyez-le au Cimetière, et aussi, après ça, s'il a quitté le Terrain par cet effet, Invoquez Spécialement 1 monstre "HÉROS Masqué" du même Attribut que le monstre envoyé avait lorsqu'il était sur le Terrain (son Attribut d'origine, si face verso) depuis votre Extra Deck.*

   - Renvoyer un monstre à la main pour *Mouton Peluchimal* :

      *Vous pouvez renvoyer 1 autre monstre "Peluchimal" que vous contrôlez à la main ; Invoquez Spécialement 1 monstre "Lutin Tranchant" depuis votre main ou Cimetière.*

3. Vrai ou Faux : Si j'active *Dai Imprévu* et que je chaîne *Appel de l'Être Hanté*, *Dai Imprévu* invoque Spécialement quand même.
      - *Dai Imprévu* : 
        
        *Si vous ne contrôlez aucun monstre : Invoquez Spécialement 1 Monstre Normal de max. Niveau 4 depuis le Deck.*

      - *Appel de l'Être Hanté* :
       
        *Activez cette carte en ciblant 1 monstre dans votre Cimetière ; Invoquez Spécialement la cible en Position d'Attaque. Lorsque cette carte quitte le Terrain, détruisez le monstre. Lorsque le monstre est détruit, détruisez cette carte.*

4. Vrai ou Faux : Si j'invoque Spécialement *Archdémon Enfernité* tant que je n'ai aucune carte en main, et que je chaîne *Jarre de Cupidité* à l'activation de son effet, l'effet de *Archdémon Enfernité* me laisse quand même ajouter une carte.
      - *Archdémon Enfernité* :
      
        *Lorsque cette carte est Invoquée Spécialement : vous pouvez ajouter 1 carte "Enfernité" depuis votre Deck à votre main. Vous ne devez avoir aucune carte dans votre main pour activer et résoudre cet effet.*
      - *Jarre de Cupidité* :
        
        *Piochez 1 carte.*

<details>
<summary>Réponses</summary>
    
 1. **Uniquement l'effet de *Simorgh des Ténèbres*.** 
   
      *Les effets ne démarrent une chaîne que lorsqu'ils ont un point-virgule ou un deux-points.*
 2. **Seulement renvoyer un monstre à la main pour *Mouton Peluchimal*.** 
   
      *Une action est un coût uniquement lorsqu'elle est écrite avant un deux-points.*
 
 3. **Vrai.** 
      
      *Ne contrôler aucun monstre est uniquement une condition d'activation, parce que cette portion est rédigée avant le deux-points, et la carte ne précise pas qu'il faut n'avoir aucun monstre en résolution.*
 4. **Faux.** 
 
      *N'avoir aucune carte en main n'est pas uniquement une condition d'activation, comme l'effet de Archdémon Enfernité le précise explicitement*
</details>

Ce n'est pas la dernière fois que nous parlerons de PSCT ! D'autres éléments viendront tout au long de cette série. Si vous souhaitez en lire plus sur le PSCT en général, vous pouvez consulter les [articles officiels Konami sur le sujet](https://yugiohblog.konami.com/articles/?tag=problem-solving-card-text) (rédigés en Anglais).

Enfin, avant d'appliquer les règles énoncées plus haut, veillez à vous assurer que la carte est bien écrite en PSCT ! Comme décrit au début, la grande majorité des cartes que vous rencontrerez sont écrites en PSCT, mais si une carte est ancienne et n'a pas été réimprimée depuis longtemps, alors les règles énoncées ne s'appliqueront pas.

Le prochain article concernera le [Ciblage](2_Ciblage.md).