# -*- makefile -*-
# Recopier ce fichier sous le nom "makefile" dans tous les repertoires
# ou vous comptez stocker des objets.


# Indiquez la liste des r�pertoires (separe par des blanc) ou vous voulez aller
# chercher les classes (biblioth�ques d'objets).
# En cas de conflit de code clavier pour la cr�ation, c'est l'ordre
# des r�pertoires qui soul�ve l'ambigu�t�.

DIRECTORY_A_AJOUTER = .

# Pour ajouter vos propre biblioth�ques
# export USER_LIB = -ltoto

# Pour ajouter vos propre Flags de compilation
# export USER_CFLAGS =  -Wno-unused -Wno-format

# Par defaut,
#   - on compile le contenu du directory courant
#   - on fait l'edition des liens
#   - on lance nanoedit.


tester:

tester_:default_
	cd .. ; $(MAKE) client
	./tests

rejoue:

rejoue_:
	./rejouer

soft_clean_::
	-rm xxx.* client
# Pour avoir l'option -g et la table des symbols, decommentez la ligne suivante
# DEBUGGAGE=oui

include ../Makefile.commun
include Makefile.dep
