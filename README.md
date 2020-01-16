Ce compilateur a été réalisé sous netbeans, nous avons utilisé le plugin "WindowBuilder" pour l'interface graphique.
Il permet d'analyser un fichier qu’on doit charger avec l'extension .COMPILA puis d'effectuer l'une des 3 analyses (lexicale, syntaxique ou sémantique)
Le rôle de l’Analyseur lexicale : 
il va lire le fichier .COMPILA et reconnaitre tous les mots de type identificateur, nombre entier, nombre réel et les mots réserve comme la virgule, symbole « <, >» ,les guillemets, Snl_Start, Snl_Int, %., Set, Snl_Real, if, %, Else, Start, Get, From, Finish, Snl_Put, %.., Snl_Close.
Dans l'analyseur syntaxique il doit s'avoir si les mots qui sont reconnu par l'Analyseur lexicale suivent une grammaire définie qui permet de reconnaitre la déclaration des entiers, les commentaires, les conditions, les affectations des nombre entier ou réel, l’affichage du message, l’affichage des valeurs, le début et la fin du bloc, du programme.
Et l’analyseur sémantique qui va associer à la grammaire que nous allons vu dans analyseur syntaxique un ensemble des règles sémantiques (représente une suite algorithmiques) d’où une traduction dirige par la syntaxe en c.



 


