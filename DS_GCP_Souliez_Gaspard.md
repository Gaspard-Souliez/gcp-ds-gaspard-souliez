## Questions Ouvertes

### Création d'un Service Account :
● « Décrivez les étapes pour créer un Service Account dans GCP. Quelles sont les
bonnes pratiques à suivre en matière de gestion des clés et de sécurité ? »

Pour créer un service account il faut se rendre dans la console gcp puis dans l'onglet "IAM & admin" puis "service accounts". Une fois dans cet onglet vous pouvez créer un service account et lui donner un nom. Vous pouvez lui attribuer des rôles et ensuite générer une clé json si besoin et ensuite la stocker(attention de bien la sécuriser). Pour finir vous pouvez activer la rotation régulière et supprimer les clé inutiles.

### Création d'un Bucket :
● « Comment créer un bucket sur Google Cloud Storage ? Précisez les configurations
importantes à définir (localisation, politique de conservation, etc.) et comment celles-ci
impactent la sécurité et la performance. »

Pour créer un bucket il faut se rendre dans la console gcp puis dans l'onglet "Cloud storage" puis "bucket". Une fois dans cette onglet vous pouvez créer votre bucket, il faut lui mettre un nom unique, une localisation(région), ensuite il faut lui définir sa classe de stockage et pour finir vous pouvez chiffrer ce bucket et limiter les personnes qui peuvent y accéder

### Gestion des droits (IAM) :
● « En quoi consiste la gestion des identités et des accès (IAM) sur GCP ? Donnez un
exemple concret de configuration des droits pour limiter l'accès à une ressource critique.
»

L'onglet "IAM" permet de contrôler les accès aux ressources. Par exemple vous pouvez attribuer seulement les droits de lecture a certaines personnes qui ne doivent pas faire de modification sur un bucket et a d'autre personnes vous pouvez leur affecter des droits qui leur permettent de faire des modifications sur les bucket.

### Configuration de la facturation :
● « Expliquez comment configurer la facturation sur GCP. Quelles précautions
recommanderiez-vous pour éviter des coûts imprévus lors du déploiement de projets ?
»

Pour configurer la facturation, il faut se rendre dans l'onglet "facturation" puis "lier un compte de facturation", ensuite vous pouvez configurer des budgets et des alertes pour éviter tout dépassement imprévu. Pour plus de détails sur vos dépenses vous pouvez également activer la facturation détaillée, il faut tout de même surveiller vos dépenses même si vous avez des alertes mise en place. Vous pouvez également utiliser des quotas pour éviter toute dépense excessive.

### Règles de vie :
● « Quelle est la chose importante que l'on dit à la fin du cours en quittant la salle de TP ?
»

Au revoir, bonne journée.

## Lien vers le github = https://github.com/Gaspard-Souliez/gcp-ds-gaspard-souliez

## info pour la correction

les images sont dans le dossier "/img"

le nom du projet gcp est "DS-GCP-Gaspard-Souliez"
le nom du bucket est "bucket-ds-gcp-gaspard-souliez"
