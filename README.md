Début addition (réel Argent, réel Prix)

+ Si argent < 0   (pas de bonbon)
+ Si prix < 0   (pas de bonbon)

+ Tant que argent > prix
+ Si argent > prix     (un bonbon)
+ Si argent < prix     (pas de bonbon)

+ Faire argent ← argent - prix
+ Nombre de bonbon ← nombre de bonbon +1
  
Retourner jusqu'à ce que argent < prix

Fin quand argent < prix

Retourner nombre (entier) de bonbon
