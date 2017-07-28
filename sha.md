//Author : Hack The Life

LE SHA

Le SHA ou SHA-0 pour Secure Hash Algorithm est un algorithme de hachage cryptographique qui existe depuis 1993.
Pour bien comprendre, le mot anglais hash veut dire : recouper / mélanger.

Le hashage est une fonction, qui, à partir d'une donnée fournie en entrée, calcule une empreinte unique servant à l'identifier rapidement de
façon fiable.

Un premier exemple concret pour entrer dans le vif du sujet.

Le cryptage / hachage permet de transporter une information sensible qui ne pourra être lue si elle était interceptée.
Si vous entrez un identifiant et mot de passe sur un réseau sécurisé, cette technique cryptographique va permettre de vérifier que vous saississez
bien les bonnes données sans qu'elles soient visibles / lisibles pour autant.

La différence entre le le SHA(ou SHA-0), SHA1, SHA2,SHA3..., c'est que ce sont les différentes versions qui, plus sont plus ou moins sécurisés.


Un deuxième exemple :

J'ai un fichier ISO très volumineux constitué de nombreux fichiers hétéroclites que je veux le mettre à disposition. J'utilise alors cet
algorithme pour qu'il me génère une synthèse / empreinte unique de ces nombreuse informations.

A la fin du hashage, toute ces données on obtient une clé / valeur unique de vérification, exmple d'une clef SHA-1 :
1AB5BCF44C7AE40EB4CE56EF3C849E4BF279F7CA.

Si quelqu'un télécharge ce fichier ISO, il lui suffit de comparer cette clef originale avec la clef fournie par le fichier téléchargé, ainsi il
sera sûr à 100% qu'entre le fichier original sur le serveur et le fichier téléchargé sur le disque il n'y pas de variations, altérations ou pertes
de données.
