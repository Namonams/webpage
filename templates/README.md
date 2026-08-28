# Templates NK — prêts à vendre

Deux fichiers, aucune dépendance, aucun build. On ouvre `index.html`, on change le bloc `:root`,
le site est au couleurs du client.

## NK-01 · « Atelier » — site vitrine artisan
`nk-01-artisan/index.html`

Charpente / couverture pris en exemple, mais la structure vaut pour tout métier manuel local :
plombier, électricien, paysagiste, menuisier.

- Barre collante + téléphone toujours visible
- Hero avec créneaux restants (rareté vraie, pas inventée)
- 4 chiffres de preuve · 3 métiers avec prix de départ · 3 chantiers · 4 étapes · 2 avis · zone d'intervention · 4 questions · formulaire
- Palette verdure nocturne, contrastes AAA
- Personnalisation : **6 variables CSS** en tête de fichier

Prix conseillé : **149 €** en libre-service · **890 €** posé et rédigé (done-for-you).

## NK-02 · « Devis Express » — calculateur intégrable
`nk-02-devis/index.html`

Le bloc à coller dans NK-01 (ou dans le site existant du client). Il donne le prix **avant**
de demander le numéro, et il dit ce qu'il ne sait pas chiffrer.

- Grille de tarifs isolée dans un objet `TARIFS` : une ligne à changer par métier
- Fourchette ± 12 %, TVA paramétrable, arrondi au palier de 50 €
- Capture du lead en 2 champs, une fois le prix affiché
- Point de branchement commenté : `/api/lead` ou webhook n8n

Prix conseillé : **59 €** en order bump au checkout de NK-01 · **240 €** réglé sur la grille du client.

## Licence de vente

Usage sur un site par licence. Revente du fichier interdite. La licence agence (usage illimité
sur les sites livrés aux clients) se vend **490 €**.
