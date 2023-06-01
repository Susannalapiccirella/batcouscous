CAHIER DE SUIVI DU PROJET DE SUSANNA LAPICCIRELLA

Dans ce projet nous somme deux, mon binôme Adama Cisse et moi. On a décidé de construire une voiture qui puisse suivre une ligne, une couleur, un objet ou un visage. Mon binôme et moi avons choisi de lui faire suivre une ligne.

SÉANCE DU 3 AVRIL 2023
Pendant cette séance en présentiel avec Adama on a mis les câbles en suivant les instructions du tutoriel du robot.

SÉANCE DU 15 AVRIL 2023(séance autonome) 
J'ai téléchargé le code de HUSKYLENS tout en suivant les instructions du tutoriel de la caméra HUSKYLENS, j'ai ensuite branché le robot à mon ordinateur pour téléverser le code sur la carte UCA. Après j'ai débranché de mon ordi le robot et je l'ai allumé pour voir ce qui ce passait sauf que le robot ne bougeait pas parce que le protocole de communication de la caméra n'était pas réglé sur I2C. Une fois cela réglé j'ai éteint le robot et rebranché à mon ordi pour retéléversé le code sur la carte, une fois fait je l'ai à nouveau débranché de mon PC, j'ai allumé pour une deuxième fois le robot et cette fois il bougeait, alors je lui ais mis un fil épais devant d'abord qui allait tout droit puis une fois constaté que ça marchait j'ai mis un virage à droite. Sauf que quand le robot reconnaissait le virage à droite il tournait à gauche, donc il y avait quelque chose qui n'allait pas.

SÉANCE DU 16 AVRIL 2023 (séance autonome) 
J'ai relu tout le code et aussi regardé les câblages du robot et après un certain temps j'ai constaté que le code pour les roues était inversé en effet le DFMobile Robot était 7,6,4,5 et devait être 4,5,7,6 par conséquent si la caméra reconnaissait un virage à droite elle tournait à gauche et vice-versa . Donc j'ai ajusté cette partie du code, je l'ai retéléversé sur la carte UCA, j'ai placé un fil épais toujours avec le virage à droite, j'ai allumé le robot et j'ai remarqué que cette fois la voiture tournait à droite mais arrivait pas à faire totalement le virage car elle allait trop vite, ainsi j'ai changé le ZUMO_FAST de 255 à 80.

SÉANCE DU 30 MAI 2023 (séance en autonomie) 
J'ai placé le code que Adama a fait sur le code LINE_TRACKING qu'on utilise. Pour le faire fonctionner j'ai dû un peu l'ajuster.
