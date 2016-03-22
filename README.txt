Plateforme collaborative de partage d�id�es

L�objectif de ce projet est de d�velopper un site web communautaire o�

des personnes peuvent partager leurs id�es, voter pour elles ou les exclure

au bout d�un certains temps. Les id�es peuvent �tre class�es par groupe sui-
vant le domaine concern�. Bien entendu l�administrateur du site web veut

pouvoir contr�ler les flux d�id�es qui vont s��changer sur le site web et, par

cons�quent, il souhaite avoir un syst�me d�inscription et de connexion pour

partager les id�es et voter pour celles-ci.

Les participants � ces �changes se sont aper�us que certaines id�es �mer-
geaient de communaut�s. Il est important que des id�es puissent �tre asso-
ci�es � des groupes ou des communaut�s mais ce n�est pas toujours le cas.

Une id�e est compos�e d�un titre, d�un texte pouvant �tre format� en HTML,

d�images, et de mani�re optionnel, un fichier au format PDF peut �tre im-
port�. Une communaut� est un ensemble de membres qui peut �tre d�crit

� l�aide d�une page contenant le nom de la communaut� et une description

au format HTML. Une communaut� et une id�e sont associ�s � des com-
mentaires qui, eux aussi, sont soumis � des votes. Les commentaires les plus

pertinents et efficace seront plac�s en premier dans l�ordre d�affichage.

Les utilisateurs du site web peuvent voter de mani�re s�curis� pour des

id�es et une id�e peut �tre soutenue par une communaut� mais les votes des

utilisateurs et l�appuie d�une communaut� ne doivent pas �tre m�lang�s. La

page d�accueil du site web regroupera les id�es avec le plus de votent et les

id�es qui font beaucoup parler d�elles en termes de commentaires.

Les administrateurs se sont aper�us que des robots ont r�ussi � cr�er des

faux profils utilisateurs et � voter de mani�re automatique, ce qui pose un

probl�me majeur de validit� des donn�es et de la perspicacit� des votes.

3

Les propri�taires du site web vous demandent de repenser l�architecture

du site et d�utiliser Symfony 2.8 et Angular 2 pour fournir une version plus

efficace et ergonomique. Un formulaire de recherche devra �tre accessible dans

l�interface cliente qui impl�mentera une fonction permettant de rechercher des

id�es, des membres ou une communaut�.