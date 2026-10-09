# L'Atelier 07

## Règle de mise en ligne

Après chaque modification du site :

1. Commit avec un message clair en français et push sur main.
2. Vérifie avec la CLI Vercel que le déploiement de production correspond au dernier commit et qu'il est en Ready. S'il échoue, lis les logs et corrige.
3. Termine toujours par une ligne : « En ligne : [message du commit] · [lien du site] ».

## Repères

- Site en production : https://atelier-07.vercel.app (Vercel publie la branche `main`).
- Projet Vercel : `atelier-07`, équipe `cocos7`.
- Lister les déploiements : `vercel ls atelier-07 --scope cocos7`
- Vérifier un déploiement : `vercel inspect <adresse-du-déploiement> --scope cocos7`
- Lire les logs d'un échec : `vercel logs <adresse-du-déploiement> --scope cocos7`
- Dépôt : https://github.com/Kokosss007/atelier-07
