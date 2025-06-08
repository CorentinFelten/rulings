# Démystification de rulings

# Damage Step
La Damage Step est une zone de règles mystérieuse et complexe. Dans cet article, nous tenterons de développer votre intuition pour en comprendre sa structure. 

Cet article est en lien avec le dernier sur la [Battle Phase](08_Battle_Phase.md).

## Point initial
Tout d'abord, je tiens à dire que la Damage Step est complexe à comprendre. Nous la décortiquerons et l'étudierons lentement, mais cet article vous demandera plus de concentration que les autres. 

Avant de commencer, souvenons-nous que seuls certains effets rapides peuvent être utilisés lors de la Damage Step, comme résumé dans l'article précédent. Les effets utilisables sont les modificateurs directs d'ATK / DEF, les Pièges Contre, les effets de Monstres qui annulent les activations, et les effets qui mentionnent explicitement, ou qui nécessitent, d'être activés durant la Damage Step. 

Nous allons parcourir les sous-parties de la Damage Step en détail. Nous aurons besoin d'exemples, donc supposons qu'un monstre de mon adversaire attaque mon *Soldat Pingouin* Posé :
- *FLIP : Vous pouvez cibler max. 2 monstres sur le Terrain ; renvoyez les cibles à la main.*

## Début de la Damage Step
Il s'agit du début du combat. Beaucoup d'effets s'activent ici, comme l'effet de *Construction Marionnette de l'Ombre El* :
- *Au début de la Damage Step, si cette carte combat un monstre Invoqué Spécialement : détruisez le monstre.*

À noter que cette étape a lieu avant que le monstre ne soit retourné face recto. 

## Avant le calcul des dommages
Si le monstre attaqué est face verso, il est retourné face recto (dans notre exemple, il s'agit de *Soldat Pingouin*).

Cependant, l'effet Flip de *Soldat Pingouin* ne s'active pas de suite ! Il s'agit d'un des points particuliers de la Damage Step. 

Différentes cartes mentionnent qu'elles peuvent s'activer ici. Il s'agit également du moment lors duquel activer des modificateurs d'ATK / DEF. Par exemple, c'est un bon moment pour activer *Graal Interdit*, en ciblant *Soldat Pingouin* :
- *Ciblez 1 monstre face recto sur le Terrain ; jusqu'à la fin de ce tour, la cible gagne 400 ATK, mais ses effets sont annulés.*

Plusieurs Chaînes peuvent être créées ici en succession, jusqu'à ce que les deux joueurs aient fini d'activer des cartes et effets.

## Calcul des dommages
Lors de cette étape, les ATK et DEF des deux monstres sont enfin comparées. 

Les modificateurs généraux d'ATK / DEF ne peuvent plus être activés à partir d'ici. À noter donc que les effets d'*Ange de Loyauté* ne peuvent PLUS être activés ici :
- *Durant la Damage Step, lorsqu'un monstre LUMIÈRE que vous contrôlez combat (Effet Rapide) : vous pouvez envoyer cette carte depuis votre main au Cimetière ; jusqu'à la fin de ce tour, le monstre gagne une ATK égale à l'ATK du monstre de l'adversaire qu'il combat.*

À noter qu'avant la sortie de l'article officiel Konami sur la Damage Step, *Ange de Loyauté* pouvait être utilisé lors du calcul des dommages. Ce n'est plus le cas aujourd'hui.

Les effets qui précisent qu'ils s'activent ou s'appliquent lors du calcul des dommages s'activent ici. 

Une fois que les deux joueurs ont fini d'activer et appliquer leurs effets, le calcul effectif des dommages est effectué : les ATK / DEF des monstres combattants sont comparés, puis les monstres censés être détruits par le combat sont identifiés et les dommages appropriés sont calculés pour les joueurs. 

Si l'un des monstres combattants a été détruit, ou du moins retiré du Terrain, à un stade de la Damage Step avant ce point (par exemple à cause de *Construction Marionnette de l'Ombre El*), alors la Damage Step se terminerait avant d'atteindre ce stade. Un Replay d'attaque n'aura pas lieu cependant, puisque les Replays ne peuvent avoir lieu que lors de la Battle Step.

## Après le calcul des dommages
C'est à ce stade que l'on résout les conséquences du combat.

Si un monstre a été détruit par le combat, il est dit comme étant "marqué pour destruction" (plus d'informations sur ce point plus tard). 

Le dommage de combat est infligé ici. Puis, les effets suivants s'activent, en Chaîne :

- Les effets déclenchés par du dégât de combat étant infligé, comme *Tragoedia* :
  - *Lorsque vous recevez des dommages de combat : vous pouvez Invoquer Spécialement cette carte depuis votre main.*
- Les effets qui s'activent après le calcul des dommages, comme *Dame Guerrière D.D.* :
  - *Après le calcul des dommages, lorsque cette carte combat un monstre de l'adversaire : vous pouvez bannir le monstre, et aussi, bannissez cette carte.*
- Les effets déclenchés par un monstre étant retourné face recto, comme celui de *Soldat Pingouin*.

À préciser que certaines cartes comme *Trappe Sans Fond* ne pourront pas être activées lors de la Damage Step, donc ne pourront pas être utilisées en réponse à l'Invocation de *Tragoedia*.

Revenons sur *Dame Guerrière D.D.* attaquant mon *Soldat Pingouin* : leurs effets, si activés, formeraient une Chaîne, répondant aux [règles du SEGOC](03_Effets_Declencheurs.md) :

- <ins>Chain Link 1</ins> : *Dame Guerrière D.D.*

- <ins>Chain Link 2</ins> : *Soldat Pingouin*

Le terme "marqué pour destruction" a été mentionné plus tôt. Ce point est probablement le plus étrange jusque-là. Un monstre "marqué pour destruction" est toujours sur le Terrain, mais le jeu reconnaît qu'il partira bientôt au Cimetière en conséquence du combat.

Que veut dire "marqué pour destruction" ? Une conséquence de ce marquage est que mon *Soldat Pingouin* est toujours sur le Terrain jusqu'à ce point, et jusqu'à la prochaine partie de la Damage Step. 

Une autre conséquence du marquage implique que *Soldat Pingouin* ne pourra ni s'affecter ni se cibler avec son propre effet (il ne pourra donc pas se retourner lui-même à la main). Aucune autre carte ne peut le retourner à la main ou au Deck, mais la carte peut toujours être détruite, bannie ou avoir ses effets annulés.

Dans l'exemple donné plus tôt, supposons que *Dame Guerrière D.D.* a détruit *Soldat Pingouin* au combat. *Soldat Pingouin* est maintenant marqué pour destruction, donc il ne peut pas se cibler avec son propre effet. De plus, si *Dame Guerrière D.D.* active son effet, elle pourra bannir *Soldat Pingouin* malgré tout (ce qui est attendu de l'effet de *Dame Guerrière D.D.*, finalement).

## Fin de la Damage Step
A ce stade, les monstres effectivement détruits par le combat (donc marqué pour destruction) sont envoyés au Cimetière (s'ils sont encore sur le Terrain). Les effets déclenchés par cette action s'activeraient maintenant, comme celui de *Sirènemure Abysslinde* :
- *Si cette carte sur le Terrain est détruite et envoyée au Cimetière : vous pouvez Invoquer Spécialement 1 monstre "Sirènemure" ("Sirènemure Abysslinde" exclu) depuis votre Deck.*

Ou encore l'effet de *Confrérie du Poing de Feu - Gorille* :
- *Une fois par tour, lorsque cette carte détruit un monstre de l'adversaire au combat et l'envoie au Cimetière : vous pouvez Poser 1 Magie "Formation Feu" directement depuis votre Deck.*

Comme d'habitude, les effets qui mentionnent une activation à ce stade, soit "à la fin de la Damage Step", s'activent également ici.

Souvenez-vous de l'article sur les timings d'effets rapides que le jeu n'avancera pas jusqu'à ce que tous les effets ont fini de s'activer. Donc si *Abysslinde* Invoque Spécialement un monstre comme *Sirènemure Abysspike*, son effet déclencheur s'activera toujours dans cette partie de la Damage Step (et *Trappe Sans Fond* ne pourra pas s'activer) :
- *Lorsque cette carte est Invoquée Normalement ou Spécialement : vous pouvez défausser 1 monstre EAU au Cimetière ; ajoutez 1 monstre EAU de Niveau 3 depuis votre Deck à votre main.*

Il s'agit de la dernière portion de la Damage Step, et après ce stade le combat est fini. Après la résolution de la Damage Step, le joueur du tour retourne en Battle Step et peut déclarer une nouvelle attaque. S'il en déclare une nouvelle, il devra repasser par toutes ces étapes de nouveau.

## Points divers
Certaines cartes empêchent des cartes et effets de s'activer durant la Damage Step. Un bon exemple est *Armades, Gardien des Frontières* :
- *Si cette carte attaque ou est attaquée, jusqu'à la fin de la Damage Step, votre adversaire ne peut ni activer de cartes ni d'effets.*

Paradoxalement, la "fin de la Damage Step" mentionnée ici n'est pas la sous-étape mentionnée plus haut. Cette mention indique que son effet s'applique pour l'entièreté de la Damage Step. Donc, par exemple, si *Armades* détruit *Abysslinde*, alors l'effet de *Abysslinde* ne pourra pas s'activer.

Nous n'avons vu que quelques points complexes durant la Damage Step, mais il ne s'agit que de la partie émergée de l'iceberg. Si vous souhaitez en apprendre plus sur le sujet, le mieux est de consulter des juges plus expérimentés ou demander sur des forums avec une section ruling réputée.

Comme dit plus tôt, la Damage Step est complexe. Si vous avez trouvé cet article difficile à comprendre, c'est normal ! N'hésitez pas à revenir sur cet article plus tard et relire ces informations avant de tenter le quiz. 

## C'est l'heure du Quiz !
Le quiz de cet article s'appuiera sur différents rulings et mécaniques étudiés lors des derniers articles, ainsi que ce que nous avons vu dans celui-ci. Ce quiz est plus compliqué que les précédents. Souvenez-vous que le nombre de réponses erronées n'a pas d'importance ! Ce qui compte, c'est d'apprendre quelque chose de chaque question.

1. Quels effets peuvent être utilisés lorsque *Gorz, l'Émissaire des Ténèbres* active son effet pour s'Invoquer Spécialement lors de la Damage Step ?
   - *Trappe sans Fond* :

        *Lorsque votre adversaire Invoque un ou plusieurs monstres avec min. 1500 ATK : détruisez ces monstres avec min. 1500 ATK, et si vous le faites, bannissez-les.*

   - *Chaîne Démoniaque* :

        *Activez cette carte en ciblant 1 Monstre à Effet sur le Terrain ; annulez les effets du monstre face recto tant qu'il est sur le Terrain, et aussi, le monstre face recto ne peut pas attaquer. Lorsqu'il est détruit, détruisez cette carte.*

   - *Corne Céleste Ténébreuse* :

        *Lorsque votre adversaire va Invoquer Spécialement exactement 1 monstre : annulez l'Invocation Spéciale, et si vous le faites, détruisez-le.*

   - *Avertissement Divin* :

        *Lorsqu'un ou plusieurs monstres vont être Invoqués, OU lorsqu'une Carte Magie/Piège ou un effet de monstre qui inclut un effet qui Invoque Spécialement un ou plusieurs monstres est activé : payez 2000 LP ; annulez l'Invocation ou l'activation, et si vous le faites, détruisez-les.*

   <details>
   <summary>Réponse</summary>
   <p>
   <strong>Seul <i>Avertissement Divin</i> pourra s'activer.</strong><br>
   <i>Trappe Sans Fond et Chaîne Démoniaque ne peuvent pas être activées durant la Damage Step. Corne Céleste Ténébreuse et Avertissement Divin peuvent toutes deux être activées à ce stade, étant toutes deux des cartes Piège Contre, cependant Corne Céleste Ténébreuse ne peut pas annuler l'Invocation Spéciale de Gorz car l'effet de Gorz [démarre une Chaîne](06_Invocations.md).</i>
   </p>
   </details>

2. Mon *Sirènemure Abysslinde* attaque le *Abysslinde* de mon adversaire. Les deux sont en position d'attaque et sont tous deux détruits au combat. Nous souhaitons tous les deux activer nos effets. Quelle est la Chaîne formée ?
    - *Si cette carte sur le Terrain est détruite et envoyée au Cimetière : vous pouvez Invoquer Spécialement 1 monstre "Sirènemure" ("Sirènemure Abysslinde" exclu) depuis votre Deck.*

     <details>
     <summary>Réponse</summary>
     <p>
          <strong>Chain Link 1 : mon <i>Abysslinde</i> | Chain Link 2 : le <i>Abysslinde</i> de mon adversaire</strong><br>
          <i>Les deux sont détruits par le combat et veulent s'activer en même temps : le SEGOC prend donc le dessus. Mon Abysslinde sera donc Chain Link 1, car je suis le joueur du tour.</i>
     </p>
     </details>

3. Si les deux *Sirènemure Abysslinde* invoquent *Sirènemure Abysspike*, quelle est la Chaîne formée ?
   - *Lorsque cette carte est Invoquée Normalement ou Spécialement : vous pouvez défausser 1 monstre EAU au Cimetière ; ajoutez 1 monstre EAU de Niveau 3 depuis votre Deck à votre main.*

   <details>
   <summary>Réponse</summary>
   <p>
   <strong>Seul mon <i>Abysspike</i> s'activera, dans une nouvelle Chaîne.</strong><br>
   <i>Résolvons la Chaîne de la question (2) : l'Invocation Spéciale du Abysspike de mon adversaire n'est pas l'une des dernières actions à avoir lieu, alors que l'Invocation Spéciale du mien l'est, donc seul le mien peut s'activer (puisque Abysspike est un [effet optionnel "lorsque"](04_When_Optionnels.md)).</i>
   </p>
   </details>

4. Si je contrôle *Taupe Géante Néo-Spacien* et que j'attaque le *Kalidor, Allié de la Justice* de mon adversaire, que se passe-t-il ?
   - *Kalidor, Allié de la Justice* :

        *Au début de la Damage Step, si cette carte combat un monstre non-TÉNÈBRES face recto : détruisez le monstre.*

   - *Taupe Géante Néo-Spacien* :

        *Au début de la Damage Step, si cette carte combat un monstre de l'adversaire : vous pouvez renvoyer le monstre de l'adversaire ainsi que cette carte à la main.*

   <details>
   <summary>Réponse</summary>
   <p>
   <strong>Chain Link 1 : <i>Kalidor</i> | Chain Link 2 : <i>Taupe Géante Néo-Spacien</i></strong><br>
   <i>Il s'agit d'un autre exemple de SEGOC, puisque les deux effets veulent s'activer au même moment au début de la Damage Step. L'effet de Kalidor est obligatoire, il devient donc Chain Link 1.</i>
   </p>
   </details>

5. Supposons maintenant que je contrôle *Ehren le Moine, Seigneur Lumière* à la place, et que j'attaque le *Kalidor* de mon adversaire qui est en position de Défense face recto? Que se passe-t-il ? 
   - *Si cette carte attaque un monstre en Position de Défense, avant le calcul des dommages : mélangez le monstre dans le Deck.*

   <details>
   <summary>Réponse</summary>
   <p>
   <strong><i>Kalidor</i> détruit <i>Ehren</i>.</strong><br>
   <i>L'effet d'Ehren s'active avant le calcul des dommages, une sous-étape venant après celle durant laquelle s'active Kalidor. Les effets ne forment donc pas de Chaîne. Puisque Ehren est détruit avant d'atteindre 'avant le calcul des dommages', son effet ne s'activera pas.</i>
   </p>
   </details>

6. La réponse change-t-elle si le *Kalidor* était face verso ?

     <details>
     <summary>Réponse</summary>
     <p>
          <strong><i>Ehren</i> renvoie <i>Kalidor</i> à l'Extra Deck</strong><br>
          <i>Kalidor est face verso au début de la Damage Step, et ne peut donc pas s'activer (et lorsqu'il est retourné face recto, ce n'est plus le début de la Damage Step). Ensuite, Ehren s'active après que Kalidor soit retourné face recto.</i>
     </p>
     </details>

7. Si j'attaque le *Rat Géant* face verso de mon adversaire avec *Dragon Rouge Archdémon*, est-ce que l'effet de *Rat Géant* peut être activé ?
   - *Rat Géant* :

        *Lorsque cette carte est détruite au combat et envoyée au Cimetière : vous pouvez Invoquer Spécialement 1 monstre TERRE avec max. 1500 ATK depuis votre Deck en Position d'Attaque.*

   - *Dragon Rouge Archdémon* :

        *Après le calcul des dommages, si cette carte a attaqué un monstre de l'adversaire en Position de Défense : détruisez tous les monstres en Position de Défense contrôlés par votre adversaire.*

   <details>
   <summary>Réponse</summary>
   <p>
   <strong>Non.</strong><br>
   <i>Rat Géant perd le combat et est marqué pour destruction. Cependant, Dragon Rouge Archdémon le détruit par effet après le calcul des dommages, avant qu'il ne soit envoyé au Cimetière à cause du combat. Le Rat Géant n'est donc pas détruit par combat, mais par effet, et ne peut pas s'activer.</i>
   </p>
   </details>


Si vous avez réussi à venir jusque-là, félicitations ! Le plus dur est fait. Vous avez assez de connaissances pour gérer une grande variété de situations complexes. 

Plus que quelques articles dans cette série ! Le prochain portera sur les [annulations](10_Annulations.md).

