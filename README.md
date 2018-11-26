# Welcome

Description : Présentation du projet et Règles de conduite

## Arborescence d'un projet

**Pas de commit sur la branche master.** Seuls les commits de merge et de mise en place par l'auteur du projet sont autorisés, jusqu'au moment
où le projet est considéré comme <u>*opérable*</u>.

Les branches doivent être nommées de la façon suivante : `user/feature-name` ou `user/I-issuenumber`.

**Ex :** `neil/add-new-task-command` ou `neil/I-#13` où 13 est le numéro de l'issue correspondant à la feature.

## Fusion de code

**Tout code à fusionner dans `master` doit passer dans une pull request.**

Les pulls requests se font à [https://github.com/DEV-2020/\<repo>/compare](https://github.com/DEV-2020/welcome/compare) où `<repo>`
correspond au dépôt dans lequel vous souhaitez faire une pull request. **Faites attention aux branches que vous souhaitez fusionner.**

Les pulls requests doivent être validées par au minimum 2 personnes ayant accès au dépôt. Même si une personne a déjà donné son accord,
une autre peut toujours demander des modifications et donner son véto. Tout refus de pull request doit être justifié d'un ou de plusieurs
commentaires expliquant quelle(s) portion(s) de code nécessitent des modifications.

## Bonnes pratiques

+ Si votre pull request est composée de plusieurs commits, un rebase interactif afin de réduire votre pull request à un commit unique serait le bienvenu.
+ Pensez à rebaser votre branche de temps en temps sur sa branche parente, afin d'éviter les gros conflits insolvables à la fin :smile:
+ Supprimez les branches qui ont été fusionnées, à moins que vous ne comptiez vous en resservir plus tard.