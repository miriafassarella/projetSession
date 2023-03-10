```mermaid
---
title: MSS
---
classDiagram

class Entrepot{
#int numero
#int nbCouloirs
+Entrepot()
+Entrepot(int, int)
}

class Femme (){
#string type
#string couleur
#char taille
+Femme()
+Femme(string type, string couleur, char taille)
+getType() string;
+getCouleur() string;
+getTaille() char;
}

class Homme{
#string type
#string couleur
#char taille
+Homme()
+Homme(string type, string couleur, char taille)
+getType() string
+getCouleur() string
+getTaille() char
}


