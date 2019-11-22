 1.- Des de dins de la carpeta del projecte prjava02 del teu ordinador, crea una branca de nom branca00. Entra dins de la branca00. Trobaràs informació de com fer-ho a la documentació. Comprova des de l'interpret d'ordres l'estat del projecte i a quina branca et trobes.
 
 Amb l’ordre "git checkout -b branca00" es crea la nova branca.
 Amb "git status" es comproba l'estat del projecte.
 
 
 
  5.- Torna a la branca master (*1) del projecte. Comprova l'estat del projecte. Mostra l'historial de la branca master. Quina diferència hi ha amb l'historial de la branca branca00?. 
  
 Amb l'ordre "git checkout master" es torna a la branca master
 Amb "git status" es comproba l'estat del projecte.
 Amb "git log master" es mostra l'historial.
 
 
 
 10.- Torna a la branca master. Comprova el contingut del fitxer Prjava02.java amb geany. Fusiona (merge) la branca branca00 amb la branca master. Trobaràs informació a la documentació. Comprova que passa que passa amb el contingut del fitxer Prjava02.java obert amb el geany. 
 
Amb "git checkout master" es torna a la branca master.
Amb "git merge branca00" es fa el merge.



 14.- Des de la branca01, Fes un push del dipòsit local al dipòsit remot. Des de Github, actualiza la pàgina web del projecte, i comprova que els canvis han estat realitzats correctament. Comprova que ara s'ha generat la branca01 a Github. 
 
 Amb "git push -u origin branca01" es fa un push.



6.- Des de geany, actualitza el contingut del fitxer Prjava02.java. Pots veure l'última línia afegida?. Per què? 

Ja no es pot veure la línia afegida ja que estem situats a la branca master.


7.- Torna a la branca branca00. Des de geany, actualitza el contingut del fitxer Prjava02.java. Pots veure l'última línia afegida?. Per què?. 

Sí que es veu ha ja que estem a la branca00.


12.- Fes un push del dipòsit local al dipòsit remot. Des de Github, actualitza la pàgina web del projecte, i comprova que els canvis han estat realitzats correctament. Comprova que només s'ha actualitzat la branca master únicament. Per què?. 

Perquè l'actualització s'ha realitzat desde la branca master.
