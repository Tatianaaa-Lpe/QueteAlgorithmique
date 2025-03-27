Début addition (réel Argent, réel Prix)

+ Si argent < 0   (pas de bonbon)
+ Si prix < 0   (pas de bonbon)

+ Si argent > prix     (un bonbon)
+ Si argent < prix     (pas de bonbon)

+ Tant que argent > prix
+ Faire argent ← argent - prix
+ Nombre de bonbon ← nombre de bonbon +1

Retourner jusqu'à ce que argent < prix

Fin quand argent < prix

Retourner nombre de bonbon
