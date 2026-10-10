# Transmissions

Application Android pour infirmières à domicile. Les vocaux de transmissions
reçus sur WhatsApp deviennent une fiche par patient : ce qui a été fait, ce qui
reste à faire, les points de vigilance et l'évolution de santé sur plusieurs
jours. Chaque point est relié à son passage dans le vocal, qu'on peut réécouter.

**Tout se fait sur le téléphone.** La transcription et l'analyse tournent en
local, rien n'est envoyé sur internet. Seuls les modèles d'IA se téléchargent,
une fois, au premier lancement.

## Installer

1. Sur le téléphone Android, ouvrez ce lien :
   **https://github.com/MorlotN/transmissions-app/releases/latest/download/transmissions.apk**
2. Ouvrez le fichier téléchargé. Android demande d'autoriser l'installation
   depuis le navigateur : acceptez pour cette fois.
3. Ouvrez Transmissions. L'app mesure le téléphone et propose un niveau
   d'analyse, puis télécharge ses modèles (de 0,9 à 5,5 Go selon le niveau).
   Choisissez **Wi-Fi seulement** ou **Wi-Fi ou 4G** : en Wi-Fi seulement,
   le téléchargement se met en pause quand le téléphone passe en 4G et
   repart tout seul au retour du Wi-Fi. Gardez l'app ouverte ; une coupure ne
   fait rien perdre, le téléchargement reprend où il en était.

Il faut Android 10 ou plus récent, sur un téléphone 64 bits (tous ceux vendus
depuis 2017 environ).

## Utiliser

- Dans WhatsApp, appuyez longuement sur un vocal, sélectionnez les autres,
  puis **Partager** et **Transmissions**.
- L'app transcrit et prépare les fiches ; gardez-la ouverte pendant ce temps.
- Onglet **Tournée** : une fiche par patient, les consignes à cocher, les
  alertes en tête. Touchez ▶ pour réentendre le passage.
- Onglet **Patients** : ajoutez vos patients avec les noms et surnoms employés
  par vos collègues. Ceux qu'on entend dans les vocaux apparaissent aussi, à
  confirmer.

## À savoir

C'est un aide-mémoire, pas le dossier de soins : c'est le vocal qui fait foi.
Les doses et les mesures sont recopiées du vocal, jamais reformulées, mais une
transcription peut se tromper. Au moindre doute, réécoutez le passage.

Les données sont chiffrées sur le téléphone, protégées par l'empreinte ou le
code, et exclues des sauvegardes en ligne. Le son des vocaux s'efface au bout
de quelques jours (réglable) ; l'historique d'un patient, après la fin de ses
soins.

## Mettre à jour

Ouvrez à nouveau le lien d'installation : la nouvelle version s'installe
par-dessus l'ancienne, les patients et l'historique sont gardés. Si une version
change de modèles, l'app le dit au lancement et télécharge seulement ce qui
manque, après avoir effacé les anciens.

Version d'essai : merci de signaler tout ce qui cloche.
