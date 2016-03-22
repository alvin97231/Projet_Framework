Plateforme collaborative de partage d’idées

L’objectif de ce projet est de développer un site web communautaire où

des personnes peuvent partager leurs idées, voter pour elles ou les exclure

au bout d’un certains temps. Les idées peuvent être classées par groupe sui-
vant le domaine concerné. Bien entendu l’administrateur du site web veut

pouvoir contrôler les flux d’idées qui vont s’échanger sur le site web et, par

conséquent, il souhaite avoir un système d’inscription et de connexion pour

partager les idées et voter pour celles-ci.

Les participants à ces échanges se sont aperçus que certaines idées émer-
geaient de communautés. Il est important que des idées puissent être asso-
ciées à des groupes ou des communautés mais ce n’est pas toujours le cas.

Une idée est composée d’un titre, d’un texte pouvant être formaté en HTML,

d’images, et de manière optionnel, un fichier au format PDF peut être im-
porté. Une communauté est un ensemble de membres qui peut être décrit

à l’aide d’une page contenant le nom de la communauté et une description

au format HTML. Une communauté et une idée sont associés à des com-
mentaires qui, eux aussi, sont soumis à des votes. Les commentaires les plus

pertinents et efficace seront placés en premier dans l’ordre d’affichage.

Les utilisateurs du site web peuvent voter de manière sécurisé pour des

idées et une idée peut être soutenue par une communauté mais les votes des

utilisateurs et l’appuie d’une communauté ne doivent pas être mélangés. La

page d’accueil du site web regroupera les idées avec le plus de votent et les

idées qui font beaucoup parler d’elles en termes de commentaires.

Les administrateurs se sont aperçus que des robots ont réussi à créer des

faux profils utilisateurs et à voter de manière automatique, ce qui pose un

problème majeur de validité des données et de la perspicacité des votes.

3

Les propriétaires du site web vous demandent de repenser l’architecture

du site et d’utiliser Symfony 2.8 et Angular 2 pour fournir une version plus

efficace et ergonomique. Un formulaire de recherche devra être accessible dans

l’interface cliente qui implémentera une fonction permettant de rechercher des

idées, des membres ou une communauté.