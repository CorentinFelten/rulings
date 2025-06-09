# Démystification de rulings

# Divers Rulings
Dans cet article, nous passerons en revue différentes zones de règles : le Game State, et enfin, le sujet mystère...

N'oubliez pas de jeter un œil au dernier article, sur les [légalités d'activation](11_Legalite_Activation.md) !

## Le Game State
Le Game State (traduisible en État de Jeu, en français) correspond à l'emplacement de chaque carte connue par chaque joueur. Naturellement, le Game State évolue au fur et à mesure que les joueurs piochent des cartes et effectuent des actions. 

À noter que l'ordre du Deck est aléatoire, donc son ordre ne fait pas partie du Game State (sauf si des effets comme *Zombie Épidémique* sont utilisés pour placer une carte au-dessus du Deck). Donc si je mélange le Deck, le Game State n'est pas changé. De plus, "connaître des cartes" ne fait pas non plus parti du Game State : si je révèle une carte de ma main ou une carte Posée sans raison particulière, alors le Game State n'est pas brisé. 

Si le Game State ne peut pas être réparé de sorte que les deux joueurs peuvent le vérifier, alors le Game State est dit irréparable. Voyons quelques exemples. 

*Joueur A a 5 cartes en main (et Joueur B ne les connait pas). Joueur A pioche une carte illégalement, puis mélange sa main et Joueur B ne sait pas identifier quelle carte Joueur A a pioché.*

Il est impossible pour Joueur B de s'assurer que Joueur A reposera la bonne carte dans son Deck pour réparer le Game State, il s'agit donc d'un Game State irréparable. 

*Joueur A envoie 3 cartes du dessus de son Deck au Cimetière durant la End Phase via l'effet d'un monstre Seigneur Lumière, avant que Joueur B ne remarque qu'Absorption de Compétences aurait dû l'annuler.*

Les 3 cartes envoyées au Cimetière ont été vues par les deux joueurs, donc le Game State est considéré comme réparable.

Les policies de Konami expliquent que des cartes accidentellement piochées / envoyées du Deck au Cimetière doivent être révélées aux deux joueurs et renvoyées au-dessus du Deck sans le mélanger. Ceci s'applique également au second cas, vu ci-dessus : Joueur A devra renvoyer les 3 cartes au-dessus de son Deck dans le bon ordre.

En général, si un seul joueur est responsable pour créer un Game State irréparable, il sera pénalisé d'un Game Loss (C'est-à-dire qu'il sera considéré comme ayant perdu le Duel en cours, mais pas le Match). 


## Modificateurs d'ATK
Les bases des modificateurs d'ATK ne sont pas si difficiles qu'elles paraissent. Cependant, elles restent complexes à comprendre. Nous allons donc les décomposer et les parcourir lentement, mais ces points demandent de la concentration.

À tout moment, les monstres ont une ATK originale et une ATK actuelle. L'ATK d'un monstre vaut son ATK originelle, sauf si une carte ou effet la modifie. 

Quels types de modificateurs d'ATK existent ? Les types principaux sont les suivants. 

- **Effets continus**

    Ces modificateurs s'appliquent, comme leur nom indique, de manière continue. Par exemple, l'effet d'augmentation d'ATK de (la Magie Continue) *Formation Feu - Tenki* est appliqué de manière continue :
    - *Tous les monstres Bête-Guerrier que vous contrôlez gagnent 100 ATK.*

    Le terme "effet continu" résume tout ce qu'il faut connaître sur le type d'effet. Si un monstre de type Bête-Guerrier devient inaffecté par les effets de cartes Magie / Piège, ou s'il change de type et n'est plus Bête-Guerrier, alors l'augmentation d'ATK de *Tenki* arrêtera de s'appliquer.

- **Effets persistants**

    Ces modificateurs d'ATK continuent de s'appliquer pendant une durée précise après que l'effet ait été résolu. Par exemple, supposons que j'active *Boost d'Ego* sur un monstre :
    - *Lorsqu'un monstre déclare une attaque : ciblez 1 monstre face recto sur le Terrain ; jusqu'à la fin de la Battle Phase, il gagne 1000 ATK.*

    <ins>Chain Link 1</ins> : *Boost d'Ego*

    Résolution de la Chaîne : *Boost d'Ego* se résout, augmentant l'ATK de la cible.

    L'effet de *Boost d'Ego* persiste après que la Chaîne ait résolue. Même si le monstre devient inaffecté par les effets de cartes Magie / Piège après que *Boost d'Ego* ait résolu, **il ne perdra pas** ses 1000 ATK, parce que *Boost d'Ego* a déjà été appliqué sur le monstre.

Les effets persistants et continus appliquent des modificateurs de manière opposée, donc il est important de déterminer à quel type d'effet chaque carte correspond. 

Pour les cartes Magie / Piège Continues avec des effets qui s'activent et modifient l'ATK, il est souvent possible de déterminer si une modification d'ATK persiste ou s'applique continuellement après que l'effet ait résolu. Par exemple, regardons *Formation Feu - Tensen* :
- *Lorsque cette carte est activée : ciblez 1 monstre de Type Bête-Guerrier que vous contrôlez ; jusqu'à la fin de ce tour, il gagne 700 ATK. (Ce gain d'ATK reste même si cette carte quitte le Terrain.)*

La clause entre parenthèses nous explique que cet effet persiste après s'être appliqué. 

Pour les effets de monstres qui démarrent une Chaîne et modifient l'ATK, si l'effet de monstre ne peux que se modifier lui-même, alors il s'applique de manière continue. Prenons par exemple *Numéro 17 : Dragon Léviathan* :
- *Une fois par tour : vous pouvez détacher 1 Matériel de cette carte ; elle gagne 500 ATK.*

Les effets fixant l'ATK d'origine de monstres à l'Invocation rentre également dans cette catégorie. Un exemple classique est *Barbaros, le Roi des Bêtes* :
- *Vous pouvez Invoquer/Poser Normalement cette carte sans Sacrifices, mais son ATK d'origine devient 1900.*

Donc si *Illusionniste d'Effet* ou *Absorption de Compétence* est utilisé pour annuler les effets de *Dragon Léviathan* après que son effet ait résolu, ou s'il est utilisé sur *Barbaros* n'importe quand après son Invocation Normale, alors leurs effets arrêteraient de s'appliquer et leur ATK reviendrait à leur ATK d'origine.

À l'inverse, si l'effet peut s'appliquer à d'autres monstres, les modifications sont persistantes. Prenons par exemple *Numéro 20 : Giga-Brillant* :
- *Une fois par tour : vous pouvez détacher 1 Matériel Xyz de cette carte ; tous les monstres face recto que vous contrôlez actuellement gagnent 300 ATK.*

L'effet de *Giga-Brillant* peut affecter d'autres monstres. Si *Absorption de Compétences* ou *Compétence de Percée* est utilisée après la résolution de l'effet de *Giga-Brillant*, alors le boost d'ATK persistera, tant sur lui-même que sur tous les autres monstres affectés par cet effet.

Maintenant, la dernière catégorie de modificateurs d'ATK :

- **Effets de "gel"**

Ces modificateurs forcent l'ATK d'un monstre à "devenir" une certaine valeur. 

Les effets qui (démarrent une Chaîne et) divisent par deux, doublent, ou "changent" l'ATK rentrent aussi dans cette catégorie. Cependant, les effets s'appliquant de manière continue, qui changent l'ATK d'origine et ceux qui échangent l'ATK et la DEF ont des interactions plus compliquées, et ne seront pas considérés comme dans cette catégorie dans cet article. 

Un très bon exemple est celui de *Champion Héroïque - Excalibur* :
- *Une fois par tour : vous pouvez détacher 2 Matériels de cette carte ; jusqu'à la fin du tour de votre adversaire, l'ATK de cette carte devient le double de son ATK d'origine.*

    ATK: 2000 | DEF: 2000

Les effets gelant sont nommés de cette manière pour une raison : ils "gèlent" l'ATK à une valeur spécifiée. La connexion que tout autre modificateur avait précédemment à ce monstre est rompue.

Voyons ce point en action. Supposons que j'Invoque par Xyz *Excalibur* alors que mon adversaire contrôle *Tours Apoqliphort* :
- *Tous les monstres Invoqués Spécialement perdent 500 ATK/DEF.*

(Il s'agit clairement d'un effet continu.)

*Excalibur* aura donc 1500 ATK après son Invocation Xyz. Mais si son effet s'active, son ATK deviendra 4000. Elle ne sera pas réduite à 3500. L'effet de gel brise la connexion de l'effet de *Tours* sur *Excalibur*, bien que l'effet de *Tours* continue à s'appliquer.

Une fois que l'effet d'*Excalibur* arrête de s'appliquer (mais que *Tours* est toujours sur le Terrain), son ATK se dégèle : il retombe à son ATK d'origine de 2000, puis l'effet continu de *Tours* recommence à s'appliquer, puisqu'il est continu. Les effets persistants ne se réappliqueraient pas : si *Boost d'Ego* avait été utilisé sur *Excalibur* pour lui donner 1000 ATK avant qu'*Excalibur* n'utilise son effet, *Excalibur* reviendrait à 2000 et non pas 3000.

Étrange, n'est-ce-pas ? C'est le fonctionnement général des effets de gel. 

Vous devriez maintenant pouvoir comprendre cette interaction très intéressante :

*Je contrôle Aile Noire - Mistral le Tourbillon et mon adversaire contrôle Tragoedia.*

- *Aile Noire - Mistral le Tourbillon* :

    *Une fois par tour : vous pouvez cibler 1 monstre face recto contrôlé par votre adversaire ; l'ATK/DEF de la cible deviennent la moitié de son ATK/DEF actuelles.*

    (L'effet de *Mistral* gèle l'ATK du monstre à la moitié de son ATK actuelle.)

- *Tragoedia* :

    *Gagne 600 ATK/DEF pour chaque carte dans votre main.*

    (Il s'agit d'un autre effet continu.)

*Mon adversaire a 6 cartes en main. J'active l'effet de Mistral en ciblant Tragoedia, puis je finis mon tour et mon adversaire pioche pour sa Draw Phase. Quelle est l'ATK de Tragoedia maintenant ?*

Prenons ceci étape par étape. 6 cartes en main nous dit que *Tragoedia* aurait initialement 3600 ATK. L'effet de *Mistral* gèle ensuite l'ATK de *Tragoedia* à 1800. Souvenez-vous que le gel brise la connexion à tout modificateur d'ATK s'appliquant précédemment... incluant l'effet continu de *Tragoedia*. Donc même après que mon adversaire pioche une carte, et peu importe combien de cartes mon adversaire a en main et défausse, l'ATK de *Tragoedia* restera bloquée à 1800 !

Il existe bien plus de modificateurs compliqués et d'interactions, et très peu de personnes capables d'expliquer en détail les profondeurs des règles autour de *Rétrécissement*. Cependant, nous ne nous pencherons pas plus en détail sur ces points. Si besoin, n'hésitez pas à consulter des articles plus avancés et demander sur des forums réputés. 

## C'est l'heure du Quiz !

1. J'active *Pot de Dualité* et révèle 3 cartes, en ajoute une à ma main et mélange les autres dans le Deck. Je réalise alors que j'ai *Erreur* face recto sur mon Terrain :
   - *Aucun joueur ne peut ajouter de cartes depuis son Deck à sa main, sauf en les piochant.*

    L'activation de *Pot de Dualité* était-elle légale ? Si non, comment réparer le Game State ?

    <details>
    <summary>Réponse</summary>
    <p>
    <strong>L'activation était illégale et les cartes révélées devront être placée dans le bon ordre au-dessus du Deck.</strong><br>
    <i>Les policies Konami expliquent que les cartes révélées accidentellement doivent être montrées aux deux joueurs et remises dans le Deck dans le bon ordre, sans le mélanger. Le joueur ayant activé illégalement Pot de Dualité doit donc récupérer les deux cartes mélangées dans son Deck ainsi que la carte ajoutée, les remettre dans l'ordre précédent, mélanger son Deck et replacer les trois cartes au-dessus du Deck.</i>
    </p>
    </details>

2. *Pierre Blanche Légendaire* est envoyée à mon Cimetière, et j'active son effet :

    - *Si cette carte est envoyée au Cimetière : ajoutez 1 "Dragon Blanc aux Yeux Bleus" depuis votre Deck à votre main.*

    Cependant, je m'aperçois que je n'ai plus de *Dragon Blanc aux Yeux Bleus* dans mon Deck : les trois exemplaires sont dans mon Cimetière. Mon activation était-elle correcte ?

    <details>
    <summary>Réponse</summary>
    <p>
    <strong>L'activation était légale.</strong><br>
    <i>L'effet de Pierre Blanche est obligatoire, donc tant que son activation n'est pas explicitement empêchée, alors il doit être activé, même s'il ne peut pas résoudre (voir [l'article précédent](11_Legalite_Activation.md)).</i>
    </p>
    </details>

3. Supposons que je contrôle la carte Magie Continue *Formation Feu - Tenki*, et que j'Invoque *Bujin Yamato* (avec 1800 d'ATK d'origine). Supposons maintenant que je veuille utiliser l'effet de *Bujingi Grue* en attaquant avec :

    - *Formation Feu - Tenki* :

        *Tous les monstres Bête-Guerrier que vous contrôlez gagnent 100 ATK.*

    - *Bujingi Grue* : 

        *Durant le calcul des dommages (du tour de chaque joueur), si un monstre "Bujin" de Type Bête-Guerrier que vous contrôlez combat un monstre de votre adversaire : vous pouvez envoyer cette carte depuis votre main au Cimetière ; durant ce calcul des dommages uniquement, l'ATK de votre monstre devient le double de son ATK d'origine.*

    Quelle est l'ATK de *Yamato* après que l'effet de *Grue* ait résolu ? Quelle est l'ATK de *Yamato* après que l'effet de *Grue* arrête de s'appliquer ?

    <details>
    <summary>Réponse</summary>
    <p>
    <strong>3600, puis 1900.</strong><br>
    <i>L'effet de Grue gèle l'ATK de Yamato à 3600. L'effet de Tenki ne s'applique plus par-dessus, puisque sa connexion à Yamato a été coupée. Ensuite, puisque le boost de Tenki s'applique de manière continue, il recommencera à augmenter l'ATK de Yamato une fois que l'effet de Grue arrête de s'appliquer et que l'ATK de Yamato est dégelée.</i>
    </p>
    </details>

Lors du dernier article, nous observerons quelques [mécaniques avancées](13_Mecaniques_Avancees.md) avant de conclure cette série.

