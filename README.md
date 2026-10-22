# CutView

Logiciel de montage vidéo pour Windows 10 et 11 : couper et assembler des clips sur une ligne de temps, ajouter
transitions, titres animés et sous-titres (y compris en arabe et en hébreu), régler la couleur, stabiliser une vidéo
tremblée, nettoyer une voix, puis exporter, avec des préréglages tout prêts pour les réseaux sociaux. Le montage et
l'export se font sur l'ordinateur, sans intelligence artificielle.

## Télécharger

La dernière version est dans **Releases**, à droite de cette page, et toujours à la même adresse :
https://github.com/Axel-sell/cutview-mises-a-jour/releases/latest

- `CutView-<version>-installateur.exe` installe CutView pour la personne connectée, sans droits
  d'administrateur, avec un raccourci dans le menu Démarrer. Pour passer à une nouvelle version, fermer CutView
  et lancer le nouvel installateur, sans désinstaller l'ancien.
- `CutView-<version>-portable.exe` fait tourner CutView sans rien installer : un double-clic suffit. Ses
  réglages vont dans un dossier `CutView-donnees` créé à côté du fichier. Garder « -portable » dans le nom du
  fichier.

Depuis la 0.15.0, CutView regarde à chaque ouverture si une nouvelle version est publiée ici, la propose et l'installe à la place de l'ancienne (Aide ▸ Rechercher des mises à jour…). Chaque version est
accompagnée d'une fiche signée (`cutview-version.json`) : CutView n'installe une mise à jour que si la signature de la fiche et l'empreinte du fichier concordent.

Windows ne connaît pas encore CutView : le navigateur peut dire que le fichier est rarement téléchargé
(choisir « Conserver »), puis Windows afficher « Windows a protégé votre ordinateur » (cliquer sur
« Informations complémentaires », puis « Exécuter quand même »).

Ce dépôt ne contient que les versions publiées ; le code source n'est pas ici.

CutView est tiré de FilmCraft 0.6.0 (© ArtCraft Team et les contributeurs de FilmCraft, licence MIT ou
Apache 2.0, au choix). Ces licences, la notice de FilmCraft et celles des polices livrées (SIL Open Font
License 1.1) accompagnent chaque copie : dans le dossier d'installation, ou dans `CutView-donnees\Licences`
pour la version portable.

Conçu par Alex NGASSA.
