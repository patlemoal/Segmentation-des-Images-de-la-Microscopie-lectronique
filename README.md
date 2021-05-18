# Segmentation des Images de la Microscopie Electronique

L’IA permet de simplifier et d’accélérer le travail des équipes d’imagerie, aujourd’hui majoritairement sur les étapes précliniques, en facilitant la lecture des images. Le CHRU a donc besoin d'un outil IA pour segmenter un tel type d'images. Il vous demande de l'aide pour cet objectif.


# Contexte du projet

L’IA est aujourd’hui omniprésente dans la littérature scientifique de l’imagerie médicale, d’autant plus depuis le développement de nouveaux algorithmes appelés réseaux de neurones convolutifs

En effet, à ce jour, l’IA est très utile dans le domaine de l’imagerie, sur deux volets : la classification des images et la segmentation des organes. Les algorithmes pour classifier les images peuvent permettre d’aider au diagnostic en classant une image dans une catégorie particulière de pathologie. Les algorithmes pour segmenter les images sont couramment utilisés sur tous les types d’imagerie et en routine au CHRU. C’est ainsi que l’IA permet un gain de temps aux praticiens à la fois pour le diagnostic ou lors d’interventions. Elle présente aussi l’avantage de contourner certains biais liés à l’interprétation de l’opérateur.


# Segmentation d'images



Lorsqu'un seul objet est présent dans une image, nous utilisons une technique de localisation d'image pour dessiner un cadre de délimitation autour de cet objet. Dans le cas de la détection d'objet, il fournit des étiquettes avec les cadres de délimitation; par conséquent, nous pouvons prédire l'emplacement ainsi que la classe à laquelle appartient chaque objet.

La segmentation d'image donne des informations plus granulaires sur la forme d'une image et donc une extension du concept de détection d'objet.

Nous segmentons, c'est-à-dire divisons les images en régions de couleurs différentes, ce qui aide à distinguer un objet de l'autre à un niveau plus fin



# Transformer les images .tiff en .png

Le format TIFF est un format raster qui signifie : Tagged Image File Format. Ce format est principalement utilisé en PAO et en photographie.Le format est conçu pour maintenir l’intégrité du contenu du fichier lors de la compression, sans en sacrifier la qualité.

"pourquoi convertir les images tiff en png"?

Ces deux formats sont des fichiers graphiques matriciels à compression sans perte, mais la conversion au format PNG permet d'obtenir une taille de fichier plus facile à gérer .


#Jeu de données

Le jeu de données correspond à des images de drosophile.

Une drosophile est un Insecte de l'ordre des Diptères, surnommée « mouche du vinaigre ». Le genre Drosophila comporte environ 400 espèces, retrouvées sur l'ensemble du globe. Vie de la drosophile

Elles atteignent une longueur de 1 à 2 millimètres. Les drosophiles sont attirées par les fruits, dans lesquels elles pondent leurs œufs et où les larves se développent. Elles possèdent la propriété de se multiplier très rapidement et en très grand nombre. Drosophila melanogaster

La drosophile la plus connue est certainement Drosophila melanogaster, qui est l'un des organismes modèles des biologistes, et plus particulièrement en génétique. Son génome est entièrement séquencé et comporte 4 paires de chromosomes, soit 165 millions de paires de bases

Nous disposons de 30 images test, train et label.

![image](exemplejeudedonnneesdedepartindex0.JPG)

exemplejeudedonnneesdedepartindex0.JPG

exemplejeudedonnneesdedepartindex0.JPG




#la Data augmentation




#choix de l'architecture utilisée dans le modèle
