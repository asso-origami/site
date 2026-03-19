+++
date = '2026-03-19T16:03:39+01:00'
draft = false
title = 'Fauteuil Motorise'
h1 = 'Fauteuil Motorisé'
description = "Conception d'un fauteuil roulant motorisé à faible coût, intégrant la motorisation d'un hoverboard pilotée par sa carte électronique dédiée — une alternative concrète aux solutions onéreuses du marché."

tags = ["Handicap moteur", "Fauteuil roulant", "Hoverboard"]

[[intervenants]]
nom = "Mickaël"
prenom = ""
role = "Fab Manager"

[[intervenants]]
nom = "Jacques"
prenom = ""
role = "Concepteur"

[[intervenants]]
nom = "Arnaud"
prenom = ""
role = "Graphiste"

[[intervenants]]
nom = "Gilles"
prenom = ""
role = "Électricien"

[[intervenants]]
nom = "Magali"
prenom = ""
role = "Céramiste"

[[etapes]]
titre = "Réunir le matériel"
texte = "Deux objets du quotidien suffisent : un fauteuil roulant standard et un hoverboard d'occasion. Pas besoin de pièces rares ni de budget conséquent — c'est précisément ce qui rend ce projet accessible à tous."

[[etapes]]
titre = "Démontage de l'hoverboard"
texte = "L'hoverboard est démonté pour en extraire l'essentiel : les roues motrices avec leurs paliers, la carte électronique, la batterie et son chargeur. Chaque composant récupéré est une brique du système de propulsion à venir."

[[etapes]]
titre = "Câblage de la carte électronique"
texte = "Les connexions sont établies sur la carte mère de l'hoverboard pour permettre un pilotage adapté au fauteuil. C'est ici que l'électronique prend son nouveau rôle : non plus équilibrer un hoverboard, mais propulser un utilisateur en toute sécurité."

[[etapes]]
titre = "Flash du firmware"
texte = '''Le firmware open source du projet <a href="https://github.com/lucysrausch/hoverboard-firmware-hack"><u>hoverboard-firmware-hack</u></a> est flashé sur la carte. Ce hack communautaire permet de reprogrammer entièrement le comportement des moteurs, ouvrant la voie à un contrôle sur mesure.'''

[[etapes]]
titre = "Fixation sur le fauteuil"
texte = "Les éléments moteurs sont fixés de manière amovible sous le fauteuil roulant, permettant de retrofitter n'importe quel modèle standard sans modification irréversible. Le fauteuil reste démontable, transportable, et adaptable."

[[resources]]
src = "fauteuil-demonstration.jpg"
name = "cover"
title = "Le fauteuil"
[resources.params]
  alt = "un fauteuil roulant motorisé à bas coût réalisé par l'associatio norigam"
  featured = true

[[resources]]
src = "hoverboard-origami.jpg"
name = "galerie-01"
title = "L'hoverboard"
[resources.params]
  alt = "un hoverboard qui sera démonté pour récupérer les différents éléments"
  group = "galerie"

[[resources]]
src = "hoverboard-fauteuil-origami-02.jpg"
name = "galerie-02"
title = "Hoverboard démonté - 1"
[resources.params]
  alt = "L'hoverboard démonté avec ses connexions, photo 1"
  group = "galerie"

[[resources]]
src = "hoverboard-fauteuil-origami-03.jpg"
name = "galerie-03"
title = "Hoverboard démonté - 2"
[resources.params]
  alt = "L'hoverboard démonté avec ses connexions, photo 2"
  group = "galerie"

[[resources]]
src = "hoverboard-fauteuil-origami-04.jpg"
name = "galerie-04"
title = "Hoverboard démonté - 3"
[resources.params]
  alt = "L'hoverboard démonté avec ses connexions, photo 3"
  group = "galerie"

[[resources]]
src = "hoverboard-fauteuil-origami-01.jpg"
name = "galerie-05"
title = "Mise en place"
[resources.params]
  alt = "Mise en place de l'hoberboard sur le fauteuil roulant"
  group = "galerie"

[[resources]]
src = "fauteuil-motorise-hoverboard-origami-1.jpg"
name = "galerie-06"
title = "Le fauteuil vu de dos"
[resources.params]
  alt = "Le fauteuil avec sa motorisation montée, vue de dos"
  group = "galerie"

[[resources]]
src = "fauteuil-motorise-hoverboard-origami-2.jpg"
name = "galerie-07"
title = "Le fauteuil vu de face"
[resources.params]
  alt = "Le fauteuil avec sa motorisation montée, vue de face"
  group = "galerie"




+++
## Un fauteuil motorisé à bas coût
Parce que la liberté de mouvement ne devrait pas avoir de prix, ce projet est né d'une conviction simple : l'ingénierie peut être au service de tous, sans que cela nécessite un budget hors de portée. Un hoverboard, un fauteuil roulant standard, une carte électronique reprogrammée — et une idée qui change concrètement la vie d'une personne en situation de handicap.

### Étape 1 — Réunir le matériel
Deux objets du quotidien suffisent : un fauteuil roulant standard et un hoverboard d'occasion. Pas besoin de pièces rares ni de budget conséquent — c'est précisément ce qui rend ce projet accessible à tous. L'hoverboard peut être récupéré en seconde main pour une poignée d'euros, et le fauteuil est celui que l'utilisateur possède déjà. Le point de départ est volontairement humble, car c'est l'intelligence de l'assemblage qui fait toute la différence.

### Étape 2 — Démontage de l'hoverboard
L'hoverboard est démonté méthodiquement pour en extraire l'essentiel : les roues motrices avec leurs paliers, la carte électronique, la batterie et son chargeur. Chaque composant récupéré est une brique du système de propulsion à venir. Ce démontage, accessible à quiconque dispose d'un tournevis et d'un peu de patience, révèle une électronique étonnamment bien conçue — et largement sous-exploitée dans son usage d'origine.

### Étape 3 — Câblage de la carte électronique
Les connexions sont établies sur la carte mère de l'hoverboard pour permettre un pilotage adapté au fauteuil. C'est ici que l'électronique prend son nouveau rôle : non plus équilibrer un hoverboard, mais propulser un utilisateur en toute sécurité. Le câblage demande rigueur et précision, mais reste dans les cordes d'un maker ou d'un électronicien amateur. Chaque fil connecté rapproche un peu plus le projet de son objectif.

### Étape 4 — Flash du firmware
Le firmware open source du projet hoverboard-firmware-hack, initié par Lucy Rausch, est flashé sur la carte. Ce hack communautaire permet de reprogrammer entièrement le comportement des moteurs, ouvrant la voie à un contrôle sur mesure, fluide et sécurisé. C'est la pièce maîtresse du projet : sans cette reprogrammation, les moteurs resteraient esclaves de leur logique d'équilibre d'origine. Avec elle, ils deviennent de véritables actionneurs au service de la mobilité.

### Étape 5 — Fixation sur le fauteuil
Les éléments moteurs sont fixés de manière amovible sous le fauteuil roulant, permettant de retrofitter n'importe quel modèle standard sans modification irréversible. Le fauteuil reste démontable, transportable, et adaptable. Cette réversibilité est un choix fort : l'utilisateur conserve son fauteuil d'origine, sa garantie, et la possibilité de revenir à un usage manuel à tout moment. La motorisation s'ajoute, elle ne remplace pas.

### Un projet ouvert, une démarche partagée  
Ce fauteuil motorisé s'inscrit dans une logique de fabrication ouverte et collaborative. Le firmware est libre, la documentation est accessible, et le coût total reste une fraction de celui d'un fauteuil motorisé commercial. L'objectif n'est pas de concurrencer l'industrie médicale, mais de proposer une alternative concrète là où les solutions existantes restent financièrement inaccessibles.
C'est le sens même du mouvement maker appliqué au handicap : mettre les outils, le savoir et l'ingéniosité collective au service de ceux qui en ont le plus besoin.  
Pour en savoir plus, rendez-vous sur la [page de Mickaël](https://mpstlvc.github.io/Hack_Hoverboard/)
