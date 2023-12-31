Les langages XPath et XSLT existent depuis environ 2000, et ont évolué lentement :
1 release majeure tous les 10 ans. XQuery existe depuis 2010 et a mis aussi 10 ans à évoluer.

XPath 3.1, XQuery 3.1 et XSLT 3.0 ont à ce jour un niveau cohérent entre eux : XQuery 3.1 et
XSLT 3.0 s'appuient sur XPath 3.1, qui définit une syntaxe commune, et surtout une librairie
de fonctions utilisées dans les 2 langages.

XPath 3.1 a vu l'arrivée des High Order Functions : des fonctions qui prennent en paramètre
des fonctions, ou des fonctions qui renvoient des fonctions. Cela a été une évolution importante
dans le langage, car cela a permis beaucoup de développements, et principalement, cela a permis
de rendre XPath entièrement fonctionnel.

Malheureusement, peu de High Order Functions sont livrées directement dans la spécification 3.1 :
on y trouve simplement les fonctions de base qui permettent de mettre en place la programmation
fonctionnelle : fold-left, fold-right, filter, sort, for-each, etc... Et ceci a freiné l'utilisation
des High Order Functions dans les développements réalisés en XSLT 3.0 ou XQuery 3.1, malgré les
exemples proposés sur les différents fils communautaires (Stackoverflow, mailing lists, etc...).

Les différents éditeurs des spécifications XPath, XSLT et XQuery, suite à une proposition d'évolution
de Michael Kay (XML Prague 2020), se sont regroupés dans un Community Group du W3C, pour proposer des
évolutions dans ces 3 langages. Avec deux objectifs très importants : être capable de sortir une
nouvelle spécification dans un délai raisonnable (2 à 3 ans), comparé aux 10 années ayant été nécessaires
à faire évoluer les précédentes versions, et apporter des nouveautés à l'immense majorité des développeurs,
pour ne pas retomber dans les travers du stream processing en XSLT 3.0.

Ce talk a pour objectif de présenter au public le mécanisme de discussion entre les différents
éditeurs de la spécification, qui permettent de faire évoluer les standards. Puis de présenter
les évolutions déjà acceptées par les éditeurs, celles en cours de discussion, celles qui sont
au point mort, et celles qui ont été abandonnées.
