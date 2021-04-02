# Dossier de documentation du projet School Run (Parcours scolaire)

Dans ce dossier, on retrouve:

* La préproduction;
* Les journaux de création individuels de chaque membre de l'équipe;
* Les ressources utilisées pour le projet. C'est dans ce dossier que se retrouve les fichiers nécessaires pour refaire le projet.
* Le contenu pour la page Web (https://tim-montmorency.com/2021/projets/school_run/docs/index.html)
* Les étapes pour refaire le projet (expérience interactive)

## Pour ouvrir le projet (expérience interactive)
*Vous aurez besoin d'*[Unity](https://unity3d.com/fr/get-unity/download), [Max MSP](https://cycling74.com/downloads), [Spout](https://leadedge.github.io/spout-download.html) *et* [MadMapper](https://madmapper.com/madmapper/). *Les fichiers mentionnés se trouvent dans le dossier **ressources***.
1. Cloner le repository. 
2. Créer un nouveau projet avec Unity et importer, dans le menu **Assets**, le fichier **school_run_experience_final.unitypackage**.
3. Dans le menu **File**, aller dans **Build Settings** et ajouter les scènes au build.
3. Une fois le Raspberry Pi branché, suivre les indications de la vidéo **tuto_tapis.mov**. (La seule différence est que le dossier _shared est dans le dossier **ressources**)
4. Exécuter le fichier **max_final.maxpat**.
5. Dans le menu **Options**, cliquer sur **File Preferences**.
    * Faire le lien avec le dossier **sons**.
    * Faire le lien avec le dossier **medias**.
6. Installer l'extension de Spout sur Max.
5. Suivre les instructions de la vidéo **tuto_son.mp4**.
6. Ouvrir Madmapper et ajuster les *quads*, si applicable.
7. Dans le menu de droite, il y a la liste des Spouts. Glisser **testschoolrun** sur les *quads* de droite et de gauche. Pour celui du milieu, glisser **sendSchool**.
8. Mettre en **Full Screen**.
9. Dans Max, activer le jit.world et le output_texture $1 en cliquant sur les deux ''x''.
10. Dans Unity, lorsque vous cliquez sur le bouton **play**, la projection dans Madmapper va commencer.
12. Amusez-vous !

## Pour ouvrir le projet (jeu seulement)
Suivre le lien suivant : https://play.unity.com/mg/other/jeu-090pc 