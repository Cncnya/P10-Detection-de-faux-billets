# P10-Detection-de-faux-billets
Sur une base de données, avec les mesures géométriques de billets on essayera de détecter les vrais des faux billets


## Contexte du projet

L’Organisation nationale de lutte contre le faux-monnayage, ou ONCFM,
est une organisation publique ayant pour objectif de mettre en place des
méthodes d’identification des contrefaçons des billets en euros. Dans le
cadre de cette lutte, nous souhaitons mettre en place un algorithme qui
soit capable de différencier automatiquement les vrais des faux billets.

## Objectifs

Lorsqu’un billet arrive, nous avons une machine qui consigne l’ensemble
de ses caractéristiques géométriques. Au travers de nos années de lutte,
nous avons observé des différences de dimensions entre les vrais et les
faux billets. Ces différences sont difficilement notables à l’œil nu, mais une
machine devrait sans problème arriver à les différencier.
Ainsi, il faudrait construire un algorithme qui, à partir des caractéristiques
géométriques d’un billet, serait capable de définir si ce dernier est un vrai
ou un faux billet.
