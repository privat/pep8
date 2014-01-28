##########################################
#Notes de compilation de pep8 pour linux #
##########################################
####################
Version des outils #
####################
QT SDK 5 ou plus
gcc/g++ 4.8 et +

###################################
Étapes préalables à la compilation#
###################################
s'assurer d'avoir les librairies suivante installées
*libgl-dev
*libxslt-dev
*libgstreamer1.0-dev
*libgstreamer0.10-dev
*libgstreamer-plugins-base1.0-dev
*libgstreamer-plugins-base0.10-dev

#############
#compilation#
#############
*Dans QT-Creator; Faire Fichier>nouveau projet>importer>clone de dépôt GIT
*Remplir les  champs avec les infos GIT (URL du repository, branche)
*Laisser finir l'importation
*Choisir le mode release
*puis compiler

Si tout se passe bien, pep8 est compilé, prêt à être utilisé.

S'il y a des erreurs c'est qui manque une librairie ou que le code a été modifié depuis l'écriture de ce texte

Voià!



