# Outils et pratiques de productivité d’équipe

> Guide du wiki — partager un calendrier, coordonner une petite équipe et gérer le cycle de vie d’un événement, du privé au public.
> Dernière mise à jour : juillet 2026. Les interfaces (Google, Teamup…) changent souvent : si un écran diffère, se fier à la logique plutôt qu’au libellé exact.

-----

## 1. Pourquoi un calendrier partagé

Un calendrier partagé, c’est la **source unique de vérité** sur le *quand* : qui fait quoi, quand, et où. Même à deux, ça règle trois problèmes récurrents :

- **Les conflits d’horaire** — deux affaires bookées en même temps, une date de tournage qui tombe sur une autre.
- **Le « t’as-tu vu mon invitation ? »** — les allers-retours pour trouver une date qui marche pour les deux.
- **La perte de mémoire collective** — plus personne se rappelle ce qui a été publié, ni quand.

Règle d’or : le calendrier gère le **quand**, un gestionnaire de tâches (ou un doc) gère le **quoi** et le **comment**. On mélange pas les deux.

-----

## 2. Le paysage des outils (Google, mais pas juste)

Deux grandes familles d’outils, qu’on confond souvent :

- **Calendriers d’équipe** (Google Calendar, Outlook, Teamup) → pour *voir* les horaires, partager, réserver.
- **Outils de prise de rendez-vous** (Calendly, Cal.com, Koalendar) → pour *automatiser* la réservation : on envoie un lien, la personne pige un créneau dans nos disponibilités réelles. Utile pour les appels clients, les entrevues, les onboardings.

### Comparatif rapide

|Outil                             |Idéal pour                                                                                     |Partage                                                      |Coût                                                               |
|----------------------------------|-----------------------------------------------------------------------------------------------|-------------------------------------------------------------|-------------------------------------------------------------------|
|**Google Calendar**               |Équipes déjà sur Gmail / Google Workspace                                                      |Par courriel + niveaux de permission ; public via lien/iframe|Gratuit avec compte Google ; Workspace à partir de ~6 $/usager/mois|
|**Microsoft Outlook / Teams**     |Organisations sur Microsoft 365                                                                |Intégré au niveau de l’org                                   |Inclus dans un abonnement 365                                      |
|**Apple Calendar**                |Usagers 100 % Apple                                                                            |Partage seulement dans l’écosystème Apple                    |Gratuit                                                            |
|**Teamup**                        |Plusieurs **niveaux d’accès** + collaborateurs **sans compte** (partenaires, clients, pigistes)|Liens par sous-calendrier + comptes ; 9 niveaux de permission|Gratuit de base ; plans payants pour + de sous-calendriers         |
|**Morgen**                        |Combiner Google + Outlook + iCloud dans une seule vue                                          |Partage par « ensemble » de calendriers                      |Payant après essai                                                 |
|**Notion Calendar**               |Équipes déjà sur Notion                                                                        |Se branche sur Google Calendar                               |Gratuit                                                            |
|**Calendly / Cal.com / Koalendar**|Rendez-vous externes (clients, entrevues)                                                      |Lien de réservation                                          |Gratuit / freemium                                                 |
|**BCalendar, TimeTree…**          |Partage ultra-léger, sans création de compte                                                   |Lien à partager                                              |Gratuit                                                            |

### Ce qui compte au moment de choisir

- **L’écosystème que vous utilisez déjà.** Le meilleur calendrier, c’est souvent celui qui se branche sur les courriels que vous avez déjà. Si les deux associés sont sur Gmail, Google Calendar est le chemin le plus court.
- **Les niveaux de permission.** Peut-on montrer *juste les disponibilités* à certains, et *tous les détails* à d’autres ? (voir §4)
- **Les collaborateurs sans compte.** Un partenaire, un client, un pigiste : est-ce qu’il doit se créer un compte pour participer ? Teamup et les outils « à lien » brillent ici.
- **La séparation privé / public.** Peut-on garder une vue privée pour l’équipe *et* une vue publique propre pour l’audience ? (voir §5)
- **Le multi-plateforme.** Desktop, iPhone, Android. Quasi tous synchronisent avec Google/Apple/Outlook.

### Recommandation

Base de départ : **Google Calendar**, sur le compte Google de votre choix (ou un compte partagé). Zéro migration, ça s’intègre à Gmail et Meet, et le calendrier public s’intègre direct au site.

À garder en tête pour plus tard : **Teamup**, *si* on veut laisser des partenaires ou des clients **soumettre ou consulter des dates sans leur donner de compte Google** — son système de liens par sous-calendrier est fait exactement pour ça.

-----

## 3. Pratiques de productivité d’équipe

Des habitudes qui valent plus que n’importe quel outil :

1. **Une seule source de vérité.** Un calendrier officiel, pas trois. On ne duplique pas l’info à la main.
1. **Des conventions de nommage.** Un titre lisible d’un coup d’œil, ex. : `[PUBLIC] Live Instagram — 19 h` vs `[INTERNE] Prod capsule`.
1. **Le code de couleur.** Une couleur = une catégorie (interne, public, contenu réseaux, dispo client, congé). On lit l’horaire d’un coup d’œil.
1. **La bonne permission, la plus basse possible.** On donne l’accès minimal nécessaire, puis on monte si besoin. (Quelqu’un qui veut corriger une coquille peut modifier *toute* une série récurrente par accident : ça arrive.)
1. **L’hygiène des accès.** On révise la liste des accès de temps en temps. Une collaboration se termine → on retire l’accès (ou on supprime le lien de partage).
1. **Le calendrier ≠ la liste de tâches.** Le calendrier dit *quand*. Les préparatifs et suivis vivent dans un gestionnaire de tâches ou dans la description de l’événement.
1. **Des rituels récurrents.** Un point d’équipe hebdo, un bilan mensuel : on les met en événements récurrents pour qu’ils existent pour vrai.
1. **Des rappels (nudges).** On configure les notifications sur les moments critiques (montage, mise en ligne, ouverture des portes) pour ne pas se fier à sa mémoire.

-----

## 4. Comprendre les permissions Google Calendar

Avant de bâtir quoi que ce soit, il faut comprendre **qui voit quoi**. Google offre des niveaux d’accès étagés (mis à jour en juillet 2026) :

|Niveau                                                                                             |La personne peut…                                                                                    |
|---------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
|**Voir uniquement les disponibilités** (masquer les détails)                                       |Voir *libre / occupé*, sans les titres ni détails                                                    |
|**Voir tous les détails de l’événement**                                                           |Voir titres, lieux, descriptions — sans rien modifier                                                |
|**Apporter des modifications (voir les événements privés comme occupés)** *(nouveau, juillet 2026)*|Modifier les événements, mais les événements marqués **privés** restent masqués (affichés « occupé »)|
|**Apporter des modifications aux événements**                                                      |Créer, modifier, supprimer des événements                                                            |
|**Gérer les modifications et le partage**                                                          |Tout ce qui précède + gérer qui a accès et à quel niveau                                             |

En plus du partage personne par personne, il y a l’option **« Rendre disponible publiquement »** : on choisit alors de montrer *seulement les disponibilités* ou *tous les détails*. C’est ce réglage qui rend un calendrier consultable par n’importe qui — la base de la vue « publique ».

Bon à savoir :

- Pour partager avec un **groupe**, on peut partager avec une **adresse de groupe Google** : on gère les membres à une seule place.
- Un **événement privé** dans un calendrier partagé reste masqué pour ceux qui n’ont pas le niveau « tous les détails ». Pratique pour cacher une note interne dans un calendrier autrement public.

-----

## 5. Mettre en place un calendrier d’événements (privé vs public)

L’idée maîtresse : **deux calendriers Google distincts**, pas un seul. Ça règle proprement la tension interne / externe.

### Architecture proposée

**A. - `Interne` (calendrier privé)**

- Contient : la planification, les *holds* (dates réservées mais pas confirmées), la prod de contenu, la logistique, les notes.
- Partagé entre **les associés** au niveau *« Apporter des modifications aux événements »*.
- **Jamais rendu public.**

**B. — `Public` (calendrier public)**

- Contient : **seulement les événements confirmés**, avec titres et descriptions propres, visuel, lien d’inscription.
- Rendu public via *« Rendre disponible publiquement → Voir tous les détails »*.
- **Intégrable sur horizon-ia.studio** (code iframe) et partageable par une **URL publique** sur les réseaux.
- Modifiable par 1-2 personnes seulement, le reste en lecture.

**C. (optionnel) `Ressources`**

- Un calendrier par lieu/équipement (studio, salle louée, matériel) pour éviter les doubles réservations. On y bloque le temps de chaque événement, montage et remise en état inclus.

### Comment créer tout ça (survol)

1. Dans Google Calendar (sur ordi) → colonne de gauche → **Autres agendas → + → Créer un agenda**. Nommer `Interne`. Répéter pour `Public`.
1. Pour chacun : passer la souris sur le nom → **⋮ → Paramètres et partage**.
1. **Partager avec l’équipe** : section *Partager avec des personnes ou des groupes* → ajouter les courriels (ou l’adresse de groupe) → choisir le niveau (§4).
1. **Rendre public** (calendrier `Public` seulement) : section *Autorisations d’accès aux événements* → cocher *Rendre disponible publiquement* → choisir *Voir tous les détails*.
1. **Intégrer au site** : section *Intégrer l’agenda* → copier le **code iframe** → le coller dans l’éditeur HTML du site. Pour les réseaux, copier plutôt l’**URL publique de l’agenda**.

-----

## 6. Le cycle de vie d’un événement (branché sur le calendrier)

Cinq phases, alternant interne et externe. Pour chacune : ce qu’on fait *dans le calendrier*.

### 1️⃣ Planification — **interne**

- Créer l’événement sur **`Interne`**, statut **provisoire** (*tentative*), en **hold** sur la date.
- Mettre la checklist des préparatifs dans la **description** (ou un lien vers un doc).
- Inviter l’associé concerné. Visibilité **privée**.
- Bloquer le **lieu / matériel** sur le calendrier ressource dès que la date est verrouillée.

### 2️⃣ Promotion — **externe**

- Une fois **confirmé** : créer (ou copier) une version *propre* sur **`Public`**.
- Titre clair, description publique, **visuel**, **lien d’inscription/billetterie**.
- L’événement apparaît alors automatiquement sur le **site (iframe)** et via l’**URL publique** à partager sur les réseaux.
- Utiliser le bouton *« Ajouter à l’agenda »* dans les publications pour que l’audience l’ajoute à son propre calendrier.

### 3️⃣ Tenue de l’événement — **organisation physique**

- Sur le calendrier **interne** : ajouter des blocs **montage** et **démontage** autour de l’événement (pas juste l’heure publique).
- Réserver **lieu + équipement** sur le calendrier ressource, remise en état incluse.
- Configurer des **rappels** (ex. 1 jour avant, 2 h avant l’ouverture).
- Assigner les rôles du jour J dans la description (accueil, technique, animation).

### 4️⃣ Promotion post-événement — **externe**

- Créer une **tâche/rappel** (2-3 jours après) sur le calendrier interne : publier le *récap*, les photos, un mot de remerciement.
- Programmer la publication réseaux ; lier les photos/vidéos dans l’événement.

### 5️⃣ Bilan — **interne**

- Événement récurrent **« Bilan »** ~1 semaine après, avec l’équipe.
- Lier un **doc de rétro** : ce qui a marché, les chiffres (inscriptions vs présences, portée réseaux), les leçons pour la prochaine fois.
- Archiver : l’événement reste dans l’historique du calendrier interne — c’est votre mémoire collective.

```
1. Planification  →  2. Promotion  →  3. Tenue  →  4. Promo post  →  5. Bilan
   (interne)          (externe)        (physique)   (externe)         (interne)
   Cal. INTERNE       Cal. PUBLIC      RESSOURCE + INTERNE   PUBLIC     INTERNE
```

-----

## 7. Checklist de démarrage

- [ ] Créer les 2 calendriers Google (`Interne`, `Public`).
- [ ] (Optionnel) Créer un calendrier par lieu/ressource.
- [ ] Partager l’interne avec l’associé (*Modifier les événements*).
- [ ] Rendre le calendrier public *Public → Voir tous les détails*, réservé à 1-2 éditeurs.
- [ ] Intégrer le calendrier public au site (iframe) + récupérer l’URL publique pour les réseaux.
- [ ] Définir le code de couleur et les conventions de titres (`[PUBLIC]` / `[INTERNE]`).
- [ ] Créer les événements récurrents : point d’équipe + bilan.
- [ ] Réviser les accès une fois par trimestre.

-----

*Guide rédigé pour horizon-ia.studio · outil de base : Google Calendar · alternative à surveiller : Teamup · interfaces susceptibles de changer.*
