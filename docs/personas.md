# Personas Trace - UX V1.0

> **Source :** board Trace - Personas V1.0 (export figé). Visuels : [`docs/exports/`](exports/) (ex. [`personas-overview.png`](exports/personas-overview.png)).  
> **Statut :** profils **hypothétiques** pour la conception. À valider et ajuster avec des entretiens / recherches utilisateurs.  
> **Rappel :** le patient est le seul utilisateur direct. Les psychothérapeutes sont des personas **secondaires** sans compte ni accès aux contenus.

Ces personas prolongent la problématique M1→M2 : concevoir un espace personnel de traces subjectives (dépôt rapide, partage choisi en séance), sans surveillance ni diagnostic, voir le [README](../README.md#filiation-m1--m2).

---

## P0 - Note méthodologique

**Badges :** P0 · Tous les personas patients  
**Titre :** Fiche 0 - Scope personas patients

### Qui est concerné

Adultes majeurs de tout âge, genre et orientation ; mode de vie urbain comme rural ; tous niveaux socio-économiques ; utilisation du numérique variable ; situations familiales diverses ; rapports différents à la psychothérapie (début, suivi long, interruptions).

**V1 :** pas de mineurs.

### États et contextes transversaux

Fatigue, anxiété, détresse, distractibilité, évitement des souvenirs, pré-séance, pendant la séance, hors ligne… Ces états peuvent toucher n’importe quel persona un jour donné. Ce n’est pas un persona séparé : c’est un **scope à croiser** avec chaque fiche.

### Ce que Trace ne doit pas faire

Réduire une personne à un diagnostic ; imposer une préparation de séance ; surveiller ; notifier un thérapeute ; transformer chaque souvenir en document à transmettre.

---

## Personas principaux - patients

Utilisateurs directs de Trace.

---

### P1 - Camille · Conserver et retrouver

| | |
| --- | --- |
| **Rôle** | Principal prioritaire |
| **Profil** | 34 ans · Chargée de communication · Suivi depuis 8 mois · Séances toutes les 2 semaines · Autonome avec le numérique |

**Tension centrale**  
Le décalage entre le moment où quelque chose prend du sens et le moment où elle pourrait en parler en séance.

**Motivation**  
Capturer vite une pensée, un événement ou un ressenti pour y revenir quand elle veut, comme le jour de la consultation, sans faire de la thérapie un travail à faire.

**Besoins**

- Création en quelques secondes (texte, photo, audio)
- Retrouver ses traces
- Sélection pour les aborder en séance, modifiable
- Garder des traces uniquement pour elle
- Ne pas se sentir obligée

**Frictions**

- Trop d’étapes
- Catégories obligatoires
- Notifications
- Impression de devoir préparer chaque séance
- Pression d’« être une bonne patiente » en arrivant avec une sélection complète

**Implication Trace**  
Prioriser capture rapide, sélection légère, et la liberté de ne rien montrer le jour J.

**Priorité UX**  
Rapidité, simplicité, et ne pas culpabiliser l’usage irrégulier.

---

### P2 - Maxime · Exprimer autrement

| | |
| --- | --- |
| **Rôle** | Principal |
| **Profil** | 28 ans · Technicien du son · Vit seul · Suivi depuis 4 mois · Hebdomadaire · Très à l’aise au numérique |

**Tension centrale**  
Ressent fort sans toujours pouvoir l’expliquer : l’expression doit précéder l’explication.

**Motivation**  
Conserver des éléments significatifs (audio, image, un mot) sans les transformer tout de suite en écrit explicite.

**Besoins**

- Audio et photo accessibles
- Trace d’un seul mot possible
- Pas de titre ni d’émotion obligatoires
- Traces incomplètes OK
- Montrer depuis son téléphone
- Changer d’avis jusqu’au dernier moment

**Frictions**

- Le « Comment vous sentez-vous ? » + listes d’émotions
- Une interface trop textuelle
- Obligation de trier / ranger
- Sentiment que la trace doit être compréhensible par quelqu’un d’autre

**Implication Trace**  
Référence pour les formats de traces et la création d’une trace. Éviter les formulaires qui forcent une interprétation.

**Priorité UX**  
Liberté des formats ; capture simple et immédiate possible.

---

### P3 - Sarah · Protéger son intimité

| | |
| --- | --- |
| **Rôle** | Principal |
| **Profil** | 41 ans · Enseignante · Vit avec conjoint et enfants · Suivi depuis 1 an · Toutes les 3 semaines · Bon rapport au numérique |

**Tension centrale**  
Un espace personnel où elle maîtrise ce qu’elle garde, et ce qu’elle choisit de montrer, ou seulement de dire.

**Motivation**  
Conserver des pensées intimes sans craindre qu’elles soient découvertes à la maison, ni accessibles à sa thérapeute du seul fait qu’elles existent.

**Besoins**

- Accès sécurisé
- Aperçus masqués
- Pas de notifications révélatrices
- Comprendre stockage / sauvegardes
- Suppression claire
- Affichage isolé d’une seule trace en séance
- Pouvoir refermer immédiatement
- Préférer parfois raconter plutôt que tendre l’écran

**Frictions**

- Permissions obscures
- Cloud opaque
- Session ouverte
- Navigation accidentelle vers d’autres traces devant le thérapeute
- Partage involontaire via son téléphone
- Inconfort à laisser le thérapeute regarder son téléphone

**Implication Trace**  
Référence pour la confidentialité + mode présentation en séance. Concevoir un affichage isolé, sans exposer le reste de son espace Trace.

**Priorité UX**  
Confidentialité, contrôle, et maîtrise de ce qui est vu pendant une séance.

---

### P4 - Léa · Utiliser sans pression

| | |
| --- | --- |
| **Rôle** | Principal |
| **Profil** | 32 ans · Employée administrative · Vit seule · Suivi depuis 2 ans · Fréquence variable · Capacités d’attention variables |

**Tension centrale**  
Pouvoir utiliser Trace quand elle le veut, sans que l’app augmente sa détresse ni impose de revenir sur des contenus difficiles à revoir.

**Motivation**  
Conserver ce qu’elle ressent certaines périodes, mais pouvoir s’éloigner d’autres souvenirs - pas d’objectif de régularité qui serait stressant et décourageant.

**Besoins**

- Interface simple quand elle est fatiguée
- Pouvoir arrêter une action en cours
- Aucun contenu imposé à la relecture
- Traces privées par défaut
- Messages clairs
- Accès discret aux infos d’aide d’urgence (non dramatiques, pour ne pas augmenter l’angoisse)
- Retirer facilement une trace de la sélection
- Confirmations non culpabilisantes pour les suppressions ou l’arrêt en cours

**Frictions**

- Apps d’humeur quotidiennes culpabilisantes
- Réapparition inattendue d’un souvenir
- Notifications
- Trop de décisions à prendre
- Confusion Trace avec un dispositif d’urgence
- Relecture qui accentue la détresse psychique

**Implication Trace**  
Référence vulnérabilité et parcours d’exception. L’outil s’adapte à la disponibilité psychique, pas l’inverse. Ne pas la réduire à un diagnostic.

**Priorité UX**  
Sécurité psychologique et absence de pression d’usage ; ne pas présenter l’outil comme un dispositif d’urgence.

---

### P5 - Nicolas · Organiser et analyser

| | |
| --- | --- |
| **Rôle** | Complémentaire |
| **Profil** | 39 ans · Ingénieur · Vit seul · Suivi depuis 3 ans · Toutes les 2 semaines · Excellent rapport au numérique |

**Tension centrale**  
Retrouver ses réflexions pour alimenter son travail thérapeutique, sans que Trace entraîne une sur-intellectualisation qui remplacerait le contact émotionnel en séance.

**Motivation**  
Conserver, relier et retrouver ses notes pour préparer ses séances: utile, mais à risque de sur-utilisation.

**Besoins**

- Recherche par date ou mot-clé
- Regrouper / compléter
- Sélection de séance distincte
- Pouvoir limiter volontairement le temps passé dans l’app

**Frictions**

- Recherche insuffisante
- Classement rigide non personnalisable
- Accumulation
- Difficulté à choisir
- Pression d’apporter « tout » en séance
- Insights / stats qui encouragent l’analyse compulsive

**Implication Trace**  
Garde-fou produit : organisation souple, pas d’outil de productivité thérapeutique. Utile pour les limites de la recherche sans aller trop loin.

**Priorité UX**  
Recherche et maîtrise des catégories, sans alimenter les ruminations.

---

### P6 - Jeanne · Utiliser simplement

| | |
| --- | --- |
| **Rôle** | Complémentaire |
| **Profil** | 61 ans · Bibliothécaire · Vit en couple · Suivi depuis 6 mois · Toutes les 3 semaines · Rapport au numérique modéré |

**Tension centrale**  
Conserver quelques éléments et les retrouver sans devoir apprendre une application difficile à utiliser.

**Motivation**  
Une alternative simple au papier, encadrée et éventuellement proposée par son thérapeute (en qui elle a confiance), **à condition** que ce soit immédiatement facile à prendre en main.

**Besoins**

- Libellés explicites
- Peu d’actions pour créer
- Texte lisible
- Boutons bien identifiables
- Pas de classement obligatoire
- Corriger une erreur facilement
- Comprendre une suppression
- Compatibilité accessibilité téléphone

**Frictions**

- Icônes obscures
- Texte trop petit
- Messages d’erreur flous
- Peur de supprimer
- Navigation peu claire

**Implication Trace**  
Référence utilisabilité et accessibilité. Les mêmes frictions touchent aussi des utilisateurs plus jeunes, avec ou sans handicap.

**Priorité UX**  
Compréhension immédiate et accessibilité.

---

## Personas secondaires - psychothérapeutes

Ils influencent l’expérience **sans utiliser Trace**.

- Pas de compte
- Pas d’accès aux contenus
- Pas de notification

**Rôle :** cadrer ce que l’app ne doit jamais imposer à la séance ; mener la psychothérapie (ce que l’app ne fait pas) ; évaluer l’état psychique et les urgences (ce que l’app ne fait pas).

---

### S1 - Sophie · Préserver le cadre thérapeutique

| | |
| --- | --- |
| **Rôle** | Secondaire prioritaire |
| **Profil** | 48 ans · Psychologue clinicienne · 17 ans d’expérience · Cabinet libéral · Approche intégrative · Séances 45–50 min |

**Tension centrale**  
L’essentiel se joue dans la relation et la parole. Les supports sont acceptés seulement s’ils aident le patient, jamais de façon systématique et obligatoire.

**Motivation**  
Accueillir ce que le patient apporte (notes, photo, récit), mais Trace ne doit pas transformer la séance en revue de notes, ni créer une obligation de « rendu » pour le patient.

**Besoins**

- Spontanéité
- Rythme du patient respecté
- Pouvoir parler d’une trace sans la montrer
- Aucun contenu transmis au thérapeute entre les séances
- Pas de confusion sur la disponibilité d’une trace
- Le patient doit se sentir libre de parler d’autre chose

**Frictions**

- Patient qui croit devoir produire des traces pour « bien faire » (le bon élève)
- Liste de notes qui dirigent la séance
- Responsabilité d’un suivi numérique pour le thérapeute qui dépasse la juste distance et ne favorise pas l’autonomie psychique du patient

**Implication Trace**  
Référence compatibilité avec la pratique libérale. Trace doit s’effacer derrière le cadre clinique ; Trace n’est pas un dispositif de psychothérapie.

**Priorité UX**  
Ne jamais imposer de méthode de travail au professionnel ni au patient. L’outil n’a pas à dire comment travailler comme psychothérapeute ni comment s’impliquer dans une psychothérapie.

---

### S2 - Julien · Utiliser des supports thérapeutiques

| | |
| --- | --- |
| **Rôle** | Secondaire |
| **Profil** | 36 ans · Psychologue · 8 ans · Cabinet libéral · TCC / intégratif · Très bon rapport au numérique |

**Tension centrale**  
Peut proposer Trace comme support **facultatif** selon les objectifs pour chaque patient, sans en faire une prescription d’exercices pour tous.

**Motivation**  
Permettre au patient de retrouver ses observations et de les montrer s’il le désire, en restant compatible avec des approches structurées telles que les TCC.

**Besoins**

- Suggestion facultative
- Consultation facile quand le patient veut montrer
- Respect des objectifs sans structurer toute l’app comme un carnet d’exercices (qui reste le travail entre soignant et soigné)

**Frictions**

- Tentation de sur-structurer le travail entre séances
- Confusion patient entre Trace et devoirs à faire à la maison

**Implication Trace**  
Vérifier que Trace soutient différentes pratiques sans imposer une méthode clinique unique.

**Priorité UX**  
Adaptabilité aux différentes approches thérapeutiques sans transformer les traces en exercices obligatoires.

---

### S3 - Claire · Accompagner des situations complexes

| | |
| --- | --- |
| **Rôle** | Secondaire |
| **Profil** | 53 ans · Psychologue · 24 ans · Cabinet + travail en réseau · Intégratif, formée au psychotraumatisme |

**Tension centrale**  
Conserver plus de traces n’est pas toujours une bonne chose. Trace peut aider, mais aussi être temporairement déconseillée.

**Motivation**  
Adapter l’usage à la personne : discuter des effets de Trace, éviter toute promesse de prise en charge en crise, préserver son jugement clinique face à une situation de crise ou non.

**Besoins**

- Liberté d’adapter
- Pas de surveillance
- Conseiller une utilisation limitée
- Pas de pression à produire / relire
- Pouvoir proposer une autre façon de travailler

**Frictions**

- Rumination ou réactivation émotionnelle
- App qui ferait la promesse d’une aide clinique en crise
- Sur-implication du thérapeute dans l’activité numérique

**Implication Trace**  
Garde-fou sur la promesse de l’app. Trace ne remplace jamais le jugement clinique ; les ressources d’urgence restent externes et clairement présentées.

**Priorité UX**  
Ne pas encourager des comportements potentiellement inadaptés ou dangereux (sous / sur-interprétation, sous / sur-réaction). Ne pas se positionner comme le travail de la psychothérapie ni comme une évaluation des urgences.

---

## Avertissement

Ces fiches sont des **artefacts de conception**. Elles ne constituent pas des études de cas cliniques, ni des transcriptions d’entretiens réels. Toute validation terrain doit être documentée séparément et anonymisée.
