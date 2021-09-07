# choisir-le-velo

Ce repository permet aux utilisateurs de collaborer avec l'association "Choisir le vélo" afin d'enrichir la carte de l'observatoire du Plan Cap Azur.

Le plan est composé de 4 axes principaux
* Axe 1 – L’Eurovélo 8
* Axe 2 – La route des Balcons d’Azur
* Axe 3 – Mougins-le-Haut – Sophia
* Axe 4 – Grasse – Mougins – Biot

Si vous souhaitez proposer une modification il suffit de suivre ces étapes et de contacter l'association via cette adresse mail `contact@choisirlevelo.org` en y ajoutant l'adresse URL avec la pull request

- Cloner le repository `git clone https://github.com/choisir-le-velo/choisir-le-velo.git` ou `gh repo clone choisir-le-velo/choisir-le-velo` en local
- Créer une branche de travail `git checkout -b my-branch`
- Récupérer le contenu du fichier geojson à modifier (cliquer sur RAW si vous avez la vue "carte") et le coller sur la partie de droite du site [geojson.io](https://geojson.io/#map=12/43.6168/7.0041)
  - Vous pouvez alors ajouter les lignes correspondant au troncon à ajouter, la partie de droite se mettra à jour en meme temps
- Une fois les segments ajoutés sur le site, copier la partie de droite dans sa totalité
- Coller le contenu dans le fichier d'origine en local
- Préparer la demande de partage
  - `git add --all`
  - `git commit -m "message"`
  - `git push` si vous avez un message d'erreur, recopier la commande proposée `git push --set-upstream origin my-branch` 
- Envoyer un email à `contact@choisirlevelo.org`

