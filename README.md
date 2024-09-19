####    ####    ####    ####    ####    ####    ####    ####    ####
This project was developed by Maxime CHARDONNAY (MCAD Electronic)
####    ####    ####    ####    ####    ####    ####    ####    ####

## Description
  Ce projet consiste en une carte électronique conçue pour piloter un portail coulissant fonctionnant sous une alimentation 24VDC. La carte contrôle un moteur 24VDC et intègre plusieurs fonctionnalités :

  - Un afficheur 7 segments
  - Un bouton poussoir
  - Une sortie dédiée pour un flash lumineux ou des lumières (2A MAX)
  - La possibilité de connecter une barrière immatérielle pour la détection des personnes
  - Des entrées pour des capteurs de fin de course
  - Un module de réception radio 433MHz
    
  Le système inclut également des protections électriques :

  - Un circuit de protection contre les surtensions basé sur un montage Crowbar (avec fusible 10A)
  - Un fusible pour protéger le moteur (6.3A MAX)
  - Un fusible pour protéger les accessoires lumineux (2A MAX)

  Schéma de Branchement :

  - Alimentation : brancher une alimentation 24VDC sur les bornes d'entrée de la carte.
  - Moteur : connecter le moteur 24VDC aux bornes de sortie moteur.
  - Capteurs : Capteurs de fin de course sur les entrées dédiées (ouverture/fermeture).
  - Barrière immatérielle pour la détection d'obstacles.
  - Sortie flash lumineux : brancher une lumière ou un flash sur la sortie prévue.

``
Configuration du firmware :

Vu que la carte intègre un microcontrôleur, flasher le firmware correspondant (non disponible pour le moment).
Vérifier les connexions des différents périphériques (capteurs, moteur, lumières).

..

Utilisation :

Une fois le système branché et sous tension -->
  Utilisez le bouton poussoir pour ouvrir et fermer le portail. (ou la télécommande appairée via code décimal au récepteur 433MHz)
  L'afficheur 7 segments indiquera les différents états du portail (ouverture, fermeture, erreur).
  La barrière immatérielle arrêtera le portail en cas de détection d'une personne ou d'un obstacle, elle le réouvrira quelques secondes après.
  Si le moteur ou la sortie lumineuse dépasse une certaine charge, les fusibles protégeront les circuits.








contact@mcad-electronic.fr
www.mcad-electronic.fr
