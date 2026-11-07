# Trace

Application personnelle de **médiation thérapeutique** — projet de **mémoire Master 2** (développement web / produit), **en cours**.

Ce dépôt documente pour l’instant le cadrage produit et les personas UX. Il est **public** volontairement : travail académique partageable, sans données cliniques réelles.

## Qu’est-ce que Trace ?

Trace aide une personne en psychothérapie à **capturer et conserver** des souvenirs, pensées, ressentis ou expériences (texte, photo, audio…) pour y revenir quand elle le souhaite — y compris le jour d’une séance.

Trace permet de garder de petits fragments vécus entre les séances, sans les transformer en monitoring ni en diagnostic. L’outil appartient à la personne : elle décide ce qui reste privé et ce qu’elle peut apporter en séance. Déposer une trace est un choix, non une obligation de tout documenter.

- **Utilisateur direct unique :** la personne en suivi (le « patient » au sens du parcours de soin).
- **Le thérapeute n’a pas de compte**, pas d’accès aux contenus, pas de notifications.
- **Le partage est volontaire et en séance** : montrer le téléphone, raconter une trace, ou ne rien montrer.

## Ce que Trace n’est pas

- Pas une messagerie patient–thérapeute
- Pas un dispositif de surveillance clinique
- Pas un outil d’urgence / de crise
- Pas un carnet d’exercices obligatoires ni une méthode de psychothérapie
- Pas un scoring, une analyse algorithmique des contenus, ni un outil de diagnostic

## Filiation M1 → M2

### Problématique (héritage M1)

Comment concevoir un dispositif numérique qui soutienne l’exploration de la mémoire personnelle dans un contexte thérapeutique, tout en respectant le caractère subjectif et sensible de l’expérience — sans la réduire à une donnée à traiter ?

### Apports de la recherche

Le travail de recherche a mis en évidence plusieurs points structurants :

- entre les séances, la mémoire se présente souvent sous forme de **fragments** (images, mots, sensations, moments) plutôt que de récits complets ;
- il faut pouvoir **déposer vite**, au moment où quelque chose apparaît, sans formalisme lourd ;
- le **partage** avec le thérapeute doit rester **choisi**, jamais automatique ;
- le passage conceptuel de la « **donnée** » à la « **trace** » : ce qui compte n’est pas une information exploitable, mais une marque subjective que la personne conserve et peut, si elle le souhaite, mobiliser en séance.

Contrairement aux applications de suivi d’humeur, Trace accueille des traces subjectives et fragmentaires, au rythme de la personne. Trace n’interprète pas les contenus et ne se substitue pas à la relation thérapeutique.

### Ce que Trace exclut

Par construction, Trace refuse : le scoring, l’analyse algorithmique des contenus, la surveillance clinique, et toute prétention diagnostique.

### Pivot M1 → M2

En M1, le dispositif imaginait encore **deux espaces** (côté patient et côté thérapeute). En M2, **Trace** recentre le produit : **espace patient seul** ; le thérapeute n’a ni compte ni accès ; le partage, s’il a lieu, est **volontaire et en séance**.

### Ce que le « faire » M2 doit démontrer

Le mémoire M2 (conception / développement) doit montrer qu’un tel outil peut :

1. permettre un **dépôt rapide** de fragments vécus ;
2. laisser à la personne la **maîtrise** de ce qui reste privé et de ce qui peut être montré ;
3. soutenir un **partage en séance** sans canal numérique vers le thérapeute ;
4. tenir ses **limites** : ni monitoring, ni interprétation, ni remplacement du cadre thérapeutique.

## Statut

| Élément | État |
| --- | --- |
| Cadrage produit | En cours |
| Personas UX V1.0 | Documentés (hypothétiques) |
| Conception UI / app | En cours (hors de ce dépôt pour l’instant) |
| Code applicatif | Pas encore dans ce dépôt |

Les personas sont des **profils hypothétiques** destinés à guider la conception. Ils devront être **confrontés et affinés** avec des entretiens / recherches utilisateurs réelles. Aucune citation d’entretien présentée ici n’est une donnée terrain authentique.

## Contenu du dépôt

- [`docs/personas.md`](docs/personas.md) — note méthodologique (P0), personas patients (P1–P6) et secondaires thérapeutes (S1–S3)
- [`docs/exports/`](docs/exports/) — exports visuels (PNG) du board Personas V1.0

## Conception

Synthèse textuelle : [`docs/personas.md`](docs/personas.md).  
Exports visuels du board Personas V1.0 : [`docs/exports/`](docs/exports/) (ex. [`personas-overview.png`](docs/exports/personas-overview.png)).

## Auteure

Emilie De Duyver — mémoire M2, projet Trace (filiation recherche M1 → conception / développement M2).

## Licence / usage

Documentation de travail académique. Réutilisation possible avec attribution ; ne pas présenter les personas comme des cas cliniques réels.
