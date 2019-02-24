# Projet Conversion de chiralité

[latex], [kalkul], [plutar], [chéma], [...]

Le but de notre projet est d'étudier la conversion de chiralité, d'observer les mécanismes réactionnels qui permettent de passer d'une molécule chirale à centre stéréogène à une molécule à chiralité axiale. L'objet de notre étude est la transformation d'une molécule de dihydropyridine en une molécule de pyridine.

## Etude des molécules

[chéma des deux molécules]

Dans cette partie, nous avons choisis de séparer en deux chaque molécule, en considérant les groupes de part et d'autre de l'axe de chiralité (et donc de la liasion C-C qui deviendra l'axe de chiralité, pour la dihydropyridine). Alors que pour la dihydropyridine, ces deux groupes sont plus ou moins deplacables et tournables l'un part rapport à l'autre, on observe un bloquage après la réaction de conversion de chiralité, qui empèche la molécule de pyridine de passer d'un énantiomère à l'autre sans une energie suffisante. Due à cette propriété, cette molécule à chiralité axiale est donc appelée **atropoisomère**.

On observe également que les deux groupes de la molécule de pyridine sont semblables à deux plans, perpendiculaires l'un à l'autre, ce qui limite surement les intéractions entre les groupes de part et d'autre de l'axe de chiralité.

##### Géométrie de l'atome d'azote de la molécule de dihydropyridine

[chéma de l'atome d'azote du cycle principal]

L'atome d'azote représenté sur le schéma çi-dessus semble être de géométrie pyramidale, car est lié à trois autres atomes (deux atomes de carbone et un atome d'hydrogène), ce qui est bien le nombre de liaison qu'il doit créer pour pouvoir être stable et neutre. Cependant, nous savons que dans la réalité, la géométrie de cet atome est plus proche du plan. En effet, les doublets non liants de cet atome vont tenter de se conjuguer avec les deux doubles liaisons C=C, ce qui va "redresser" l'azote et lui faire adopter une géométrie plane, bien que pyramidalisée.

#### Pouvoir de rotation

##### Barrières de rotations

Notion d'enthalpie libre:

Pour étudier les différences energétiques entre les molécules, nous devons nous interesser aux notions d'entropie et d'enthalpie, propres aux molécules. Cependant, les molécules étudiées étants des isomères, nous avons estimé que la différences d'entropie entre les différentes coformations, configurations et isomères est négligeable. Ainsi, nous ne nous interesserons qu'à la différence d'enthalpie libre des molécules. [passur].

L'enthalpie libre est une fonction d'état propre au système, et donc ici propre à la molécule étudiée. Or, les barrières de rotations des molécules sont en fait reliées à cette enthalpie libre.

L'enthalpie libre d'une molécule est souvent determinée avec la méthode de HPLC (Dynamic High Performance Liquid Chromatography).

On peut également lier l'enthalpie libre d'activation et l'energie d'activation, qui sont deux concepts relativement semblables, qui quantifient l'energie nécessaire à un système afin de provoquer une certaine réaction.

Finalement, nous savons que ces barrières varient en fonction de critères de l'envrionnement comme la température, le solvant ou les réactifs. C'est donc en jouant sur ces critères que nous pourront préférer des réactions à d'autres.

##### Loi d'Arrhenius

La loi d'Arrhenius, qui relie la vitesse de vartiation d'une réaction en fonction de la température, nous interesse ici car elle permet également de relier $E^{\ddagger}$ (l'énergie d'activation de la réaction) avec le coefficient de vitesse k, qui nous sera important par la suite. La relation est la suivante:

$$\frac{\mathrm{d} ln(k)}{\mathrm{d}T}=\frac{E^{\ddagger}}{RT^2}$$

En jouant sur cette énergie d'activation, on a remarqué que cela nous permettrait de préférer certaines réactions à d'autres, voir même à en bloquer certaines, si leur énergie d'activation était trop grande.

#### Configuration absolue

Nous avons determiné la méthode nommant la configuration absolue des molécules de chiralité axiales, ce qui nous permettra de différencier les énantiomères et de représenter celui que l'on veut obtenir en majorité, à terme.

Afin de différencier les deux pseudo-énantomères de la pyridine, nous utiliserons à partir de maintenant son appelation en configuration absolue. Il se trouve que cette configuration absolue se determine à peu près de la même manière que pour celle d'une molécule à chiralité de centre stéréogène.

- Regarder la molécule dans l'axe, en mettant le groupe le moins important à l'arrière.
- On identifie ensuite le groupe principal, le second, et le troisème, et on étudie l'ordre de rotation pour aller de 1 -> 2 -> 3.

## Etude de la réaction

#### Partie théorique
Nous avons d'abord essayé d'analyser la nature de la réaction qui permet de passer de la première molécule à la deuxième: Il s'agit d'une réaction d'oxydation, qui élimine une molécule de dihydrogène. A travers cette réaction, une des doubles liasions du cyle principal est brisée et deux autres sont formées.

Nous avons observé que l'orientation des deux groupes de la molécules de dihypyridine autour de la liaison qui va devenir l'axe de chiralité est cruciale: C'est en effet cette orientation qui va définir si la molécule produit sera un énantiomère de la pyridine ou l'autre.
Il semble donc important de trouver un réactif qui fera en moyenne plus une réaction que l'autre, peut-être en intéragissant avec certains atomes d'oxygènes. Il semble également logique que retirer les deux hydrogènes necessaire pour former la pyridine est un opération qui demandra plus ou moins d'energie en fonction de l'orientation des groupes de la dihydropyridine.



#### Partie expérimentale

Pour faire la réaction de la molécule de dihydropyrédine vers la pyrédine, nous disposons comme réactif d'une solution racémique de dihydropyrédine, obtenue [plutar].
Nous avons également décidé de tester plusieurs réactifs, et d'étudier les résultats de chacuns d'entre eux:
- La DDQ, qui semble être souvent utilisée lors de ce type de réaction, impliquant une conversion de chiralité.
- [listdéréaktif, plutar]

## Etude de la méthode d'analyse de la solution finale

Pour analyser la solution finale, qui devra comporter plus d'un énantiomère que de l'autre, nous devons trouver une méthode qui conviendra à cette étude. Il est impossible de faire une RMN ou une spectroscopie infra-rouge car les deux énantiomères ont la même énergie interne et seront donc indifférenciables à travers ces deux méthodes. En revanche, il est possible de faire une chromatographie en milieu chiral qui permettra de mesurer le ratio de chaque énantiomère. En effet, si la phase stationaire est elle-même chirale, elle pourra réagir avec chacun des énantiomères pour former des diastéréoisomères, qui seront eux différenciables au cours de la chromatographie.

Le choix le plus logique est de faire cette chromatographie en phase liquide, étant donnée la masse molaire élevée de la molécule de pyridine
( []g.mol^{-1} [kalkul]) ce qui demanderait un grand apport de chaleur pour maintenir cette molécule en phase gazeuze.

L'analyse se fera en sortie du tube de chromatographie, [...].
- Truc de l'aire + pourcentage 
- Truc du pouvoir rotatoire, signes changent, valeur absolue identique

Une autre méthode d'analyse aurait été par diffraction de rayons X, [crytal de molécule toussa].

## Exploitation des résultats

Nous avons pu calculer plusieurs valeurs caractéristiques de chaque solution finale, dans le tableau suivant:

[plutar]

- EE signifie Excès énantiomérique, il représente le pourcentage de surplus d'un énantiomère par rapport à l'autre (par exemple, l'excès énantiomérique d'un mélange racémique est de 0%). Il est calculé par [latex].
- ER signifie ratio énantiomérique, il représente le rapport relatif entre les deux énantiomères, il est calculé par [latex].
