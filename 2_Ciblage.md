# Démistification de rulings

# 2. Ciblage
Dans cet article, nous verrons de nouveaux points sur le [PSCT](1_PSCT.md), et ce qu'il explique concernant le ciblage. 

## Bases du ciblage
En utilisant le PSCT, il est aisé d'identifier quand un effet cible ou non. 

**Un effet cible si, et seulement si, le texte de la carte emploie le mot 'cible'.**

Plutôt simple, mais il est important de rappeler que cela ne s'applique qu'aux cartes écrites avec du PSCT. Voici deux cartes d'exemples :
- *Un Souffle d'Aile de Phœnix* :

    *Défaussez 1 carte, puis <u>ciblez</u> 1 carte contrôlée par votre adversaire ; placez la cible au-dessus du Deck.*
    
    Cet effet cible explicitement.

- *Force de Miroir* :

    *Lorsqu'un monstre de l'adversaire déclare une attaque : détruisez tous les monstres en Position d'Attaque de votre adversaire.*

    Cet effet ne cible pas.

## Cibles et résolution
Les choses deviennent bien plus intéressante lorsqu'on s'attarde sur ce qui est rédigé après le point-virgule.

**Si un effet utilise également le mot 'cible' après le point-virgule, alors les conditions de ciblage doivent toutes être correctes à la résolution de l'effet, sinon la carte résoudra sans effet.**

Cette description peut sembler complexe, mais elle deviendra plus claire avec des exemples. Commençons avec l'effet de *Tireur de l'Atlantide* :
- *Lorsque cette carte est envoyée au Cimetière pour activer un effet de monstre EAU : <u>ciblez</u> 1 carte Posée contrôlée par votre adversaire ; détruisez la <u>cible</u>.*

L'effet utilise le mot 'cible' après le point-virgule. *Tireur de l'Atlantide* cible une carte Posée, donc cette règle de PSCT explique que *Tireur* vérifie si sa cible est toujours Posée à la résolution avant de la détruire. Donc si la cible de cette effet est Chaînée, alors *Tireur de l'Atlantide* ne la détruira pas. 

Comparons cette situation avec le premier effet de *Cyclone Galactique* :
- *<u>Ciblez</u> 1 Magie/Piège Posé sur le Terrain ; détruisez-<u>le</u>.*

Puisque cet effet n'emploie pas le terme 'cible' après le point-virgule, il ne vérifiera pas si la cible est toujours face cachée à la résolution. *Cyclone Galactique* détruira sa cible peu importe sa position.

Un autre exemple est *Trappe* :
- *Lorsque votre adversaire Invoque Normalement ou par Flip un monstre avec min. 1000 ATK : <u>ciblez</u> le monstre ; détruisez la <u>cible</u>.*

Puisque l'effet mentionne la 'cible' après le point-virgule, il ne détruira le monstre ciblé que s'il a toujours 1000 ou plus d'ATK en résolution. Si l'adversaire chaîne une carte comme 
*Rétrécissement* (ou *Livre de la Lune*), pour que le monstre ait moins de 1000 ATK (ou qu'il soit face verso, donc pour que son ATK ne puisse pas être déterminée), alors *Trappe* ne le détruira pas.

**Si un effet n'utilise pas le mot 'cible' après le point-virgule, lisez la carte attentivement pour déterminer quelles conditions doivent être correctes en résolution.**

Par exemple, penchons-nous sur *Trappe Sans Fond* :
- *Lorsque votre adversaire Invoque un ou plusieurs monstres avec min. 1500 ATK : détruisez <u>ces monstres avec min. 1500 ATK</u>, et si vous le faites, bannissez-les.*

Bien que la carte ne cible pas, le texte nous dit que les monstres ont besoin d'avoir 1500 d'ATK ou plus à la résolution. Si un effet est Chaîné, réduisant leur ATK en dessous de 1500, alors *Trappe Sans Fond* ne détruira ni bannira ces monstres.

Un [article dédié](www.ygorganization.com/chooseyourtarget/) à ce petit point de règle et à son application sur les cartes comme *Illusionniste d'Effet* est disponible.

Il est important de noter que les effets ne suivent pas les cartes lorsqu'elles changent de localisation (terrain, Cimetière, etc). Pour plus de simplicité, utilisons *Monster Reborn* pour illustrer ce point :
- *Ciblez 1 monstre dans l'un des Cimetières ; Invoquez-le Spécialement.*

Si *Corbeau D.D.* est Chaîné sur la carte ciblée par *Monster Reborn*, alors le monstre ne sera pas Invoqué Spécialement, puisqu'il n'est plus dans la même localisation, bien que *Monster Reborn* spécifie "Invoquez-le Spécialement".

## Plusieurs cibles
Lorsqu'un effet cible plusieurs cartes, il existe différents niveaux d'importance auxquels l'effet fait attention concernant la validité des conditions de ciblage en résolution.

**Si l'effet ne spécifie pas 'les cibles' après le point-virgule, il n'a pas besoin que les conditions de ciblages soient correctes en résolution.**

Ce point est le cas le plus libre. Par exemple, *Arsenal Zenmaioh Automate* :
- *Une fois par tour : vous pouvez détacher 1 Matériel de cette carte, puis ciblez 2 cartes Posées sur le Terrain ; détruisez-les.*

L'effet n'utilise pas le mot 'cibles' après son point-virgule, donc comme dans un cas de cible unique, il n'accorde pas d'importance au fait que la moindre cible ne soit plus Posée lorsque l'effet résoud. Il ne fait également pas attention à s'il est incapable de détruire une des cibles : il essaiera tout de même de détruire l'autre cible. C'est donc le cas le plus flexible.

**Si l'effet spécifie 'les cibles' après le point-virgule, il vérifie les conditions de ciblages pour chaque cible individuellement en résolution.**

Il s'agit du cas dans lequel l'effet vérifie chaque carte individuellement. Par exemple, *Dragon Tigre* :
- *Lorsque cette carte est Invoquée par Sacrifice en Sacrifiant un monstre Dragon : vous pouvez cibler max. 2 cartes Posées dans la Zone Magie & Piège de votre adversaire ; détruisez <u>les cibles</u>.*

Si une des cibles est retournée face recto, *Dragon Tigre* ne la détruira pas, mais il regardera tout de même l'autre cible et la détruira si elle est effectivement toujours face verso.

**Si l'effet spécifie 'les deux' ou 'toutes' (en fonction de l'effet), alors il vérifie les conditions collectivement, et si elles ne sont pas toutes correctes, l'effet ne fera rien.**

Prenons l'exemple de *Pot d'Avarice* :
- *Ciblez 5 monstres dans votre Cimetière ; mélangez-les <u>tous les 5</u> dans le Deck, puis piochez 2 cartes.*

Puisque l'effet précise 'tous les 5', si un *Corbeau D.D.* est chaîné pour bannir une des 5 cibles, alors *Pot d'Avarice* ne fera rien. 'Tous' (ou 'les deux') veut dans les faits dire 'tous ou aucun'.

## C'est l'heure du Quiz !
1. Quel(s) effet(s) ciblent ?
   - Cet effet de *Dragon Sombre Métallique aux Yeux Rouges* :
       
        *Durant votre Main Phase : vous pouvez Invoquer Spécialement 1 monstre Dragon ("Dragon Sombre Métallique aux Yeux Rouges" exclu) depuis votre main ou Cimetière.*

   - *Énorme Trappe Profonde des Ténèbres* : 
     
      *Lorsqu'un ou plusieurs Monstres à Effet de min. Niveau 5 sont Invoqués Spécialement : bannissez ces Monstres à Effet de min. Niveau 5.*

   - *Permutation de Créature* :

      *Chaque joueur choisit 1 monstre qu'il contrôle et échange son contrôle avec celui choisi par l'adversaire. Le reste de ce tour, ces monstres ne peuvent pas changer de position de combat.*

2. Vrai
