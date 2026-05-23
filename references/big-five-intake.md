# big-five-intake.md
## Module d'entrée psychométrique — Miroir Intégral

---

## Objectif

Établir une **baseline indépendante** du discours de l'utilisateur avant toute
question ouverte. Ce module réduit le biais de confirmation en fournissant des
données structurées *a priori* que l'enquête conversationnelle ne peut pas
contaminer rétrospectivement.

---

## PHASE 1 — TIPI (Ten Item Personality Inventory)

### Instructions à présenter à l'utilisateur

> *"Avant de commencer, je vais te soumettre 10 paires de traits. Pour chacune,
> indique dans quelle mesure elle te décrit — même si un trait correspond mieux
> que l'autre. Utilise l'échelle suivante :*
>
> **1** = Ne me décrit pas du tout
> **2** = Me décrit très peu
> **3** = Me décrit un peu
> **4** = Ni oui ni non
> **5** = Me décrit assez bien
> **6** = Me décrit bien
> **7** = Me décrit très bien
>
> *Il n'y a pas de bonnes ou mauvaises réponses. Réponds spontanément."*

---

### Les 10 items

| # | Paire de traits | Note (1–7) |
|---|---|---|
| 1 | Extraverti(e), enthousiaste | ___ |
| 2 | Critique, porté(e) à trouver des défauts | ___ |
| 3 | Fiable, autodiscipliné(e) | ___ |
| 4 | Anxieux(se), facilement perturbé(e) | ___ |
| 5 | Ouvert(e) aux nouvelles expériences, complexe | ___ |
| 6 | Réservé(e), peu expansif(ve) | ___ |
| 7 | Chaleureux(se), de confiance facile | ___ |
| 8 | Désorganisé(e), peu rigoureux(se) | ___ |
| 9 | Calme, émotionnellement stable | ___ |
| 10 | Conventionnel(le), peu créatif(ve) | ___ |

---

### Scoring silencieux (ne pas afficher à l'utilisateur)

```
Extraversion (E)       = (Item1 + (8 − Item6)) / 2
Agréabilité (A)        = ((8 − Item2) + Item7) / 2
Conscience (C)         = (Item3 + (8 − Item8)) / 2
Stabilité émotionnelle = ((8 − Item4) + Item9) / 2
Ouverture (O)          = (Item5 + (8 − Item10)) / 2
```

**Interprétation des scores :**

| Score | Niveau |
|---|---|
| 1.0 – 2.9 | Faible |
| 3.0 – 4.4 | Modéré |
| 4.5 – 5.9 | Élevé |
| 6.0 – 7.0 | Très élevé |

---

### Profil rapide par dimension

**Extraversion**
- Faible → énergie puisée dans la solitude, préférence pour l'écrit et le virtuel
- Élevée → énergie puisée dans le contact, expressivité naturelle

**Agréabilité**
- Faible → pensée critique forte, indépendance, possible friction interpersonnelle
- Élevée → orientation vers l'autre, sensibilité aux conflits

**Conscience**
- Faible → pensée associative, désorganisation productive, aversion à la routine
- Élevée → discipline, planification, perfectionnisme possible

**Stabilité émotionnelle**
- Faible → forte réactivité émotionnelle, richesse intérieure, vulnérabilité au stress
- Élevée → régulation solide, peut sous-estimer l'impact émotionnel des situations

**Ouverture**
- Faible → ancrage concret, pragmatisme, résistance au changement abstrait
- Élevée → curiosité intellectuelle large, tolérance à l'ambiguïté, vie imaginaire riche

---

## PHASE 2 — Questions comportementales indirectes

### Quand les activer

Activer sur les **2 dimensions les plus ambiguës** du profil TIPI —
soit celles dont le score est entre 3.5 et 5.0 (zone médiane, moins fiable
en self-report), soit celles qui semblent en tension interne.

Ne pas nommer la dimension mesurée. Ne pas présenter comme un test.

---

### Banque de questions par dimension

#### Extraversion
> *"Après une journée chargée en interactions — comment tu récupères ?
> Qu'est-ce qui se passe dans ton corps et dans ton envie ?"*

Signal Faible : besoin de solitude, décharge progressive, fatigue sociale
Signal Élevé : envie de continuer, énergie restante, impression d'avoir été "rechargé"

---

#### Agréabilité
> *"Quelqu'un que tu respectes exprime un avis que tu trouves clairement
> erroné. Qu'est-ce que tu fais — et qu'est-ce que tu ressens avant de
> décider ?"*

Signal Faible : réfutation directe, inconfort modéré, besoin de rectifier
Signal Élevé : accommodation probable, inconfort à contrarier, recherche de consensus

---

#### Conscience
> *"Décris comment tu gères un projet qui t'importe — de l'idée à la
> livraison. Qu'est-ce qui se passe naturellement, sans effort ?"*

Signal Faible : démarrage fort, finitions difficiles, structure émergente plutôt que planifiée
Signal Élevé : planification préalable, jalons, difficulté si structure absente

---

#### Stabilité émotionnelle
> *"Un événement imprévu vient perturber quelque chose d'important pour toi.
> Que se passe-t-il dans les premières minutes — avant que tu ne décides
> comment réagir ?"*

Signal Faible : activation forte, rumination possible, temps de retour à la baseline long
Signal Élevé : traitement rapide, peu de débordement, retour au calme spontané

---

#### Ouverture
> *"Une idée ou un domaine totalement étranger à ce que tu connais croise
> ton chemin. Quelle est ta réaction naturelle — avant toute évaluation
> utilitaire ?"*

Signal Faible : prudence, évaluation pratique d'abord, scepticisme initial
Signal Élevé : curiosité immédiate, absorption, connexions spontanées avec d'autres domaines

---

## PHASE 3 — Synthèse et intégration dans le Miroir

### Ce que le module produit

À l'issue des phases 1 et 2, le skill dispose de :

```
Profil Big Five estimé :
  E : [score] — [Faible / Modéré / Élevé / Très élevé]
  A : [score] — [...]
  C : [score] — [...]
  N : [score] — [...]  (Note : N = 8 − Stabilité émotionnelle)
  O : [score] — [...]

Dimensions ambiguës ayant nécessité approfondissement comportemental :
  [liste]

Tensions internes détectées (scores contradictoires) :
  Ex. O très élevé + C faible → créativité forte, exécution fragmentée
  Ex. E faible + A élevé → besoin de contact choisi, pas de socialisation diffuse
```

---

### Point d'intégration dans SKILL.md

Ce module s'insère à **l'ÉTAPE 0** du protocole, avant toute question ouverte.

```markdown
## ÉTAPE 0b — Module Big Five (obligatoire en première session)

Avant de poser la question d'entrée (Étape 1), lancer `big-five-intake.md`.

1. Présenter le TIPI — attendre les 10 réponses
2. Calculer le profil silencieusement
3. Identifier les 2 dimensions ambiguës (score 3.5–5.0)
4. Poser les questions comportementales correspondantes (une à la fois)
5. Construire le profil synthétique
6. Utiliser ce profil comme ancrage tout au long de l'enquête :
   — Confirmer ou infirmer les hypothèses de surface (Couche 1)
   — Calibrer la profondeur des questions (Couche 2–3)
   — Signaler les tensions internes profil/discours
```

---

## Limites persistantes du module

| Limite | Nature | Réductible ? |
|---|---|---|
| Self-report bias | L'utilisateur répond comme il se voit | Partiellement (choix forcé réduit mais n'élimine pas) |
| Absence de données comportementales réelles | Aucune observation directe | Non |
| Variance situationnelle | Le Big Five varie légèrement selon le contexte de vie | Partiellement (noter le contexte actuel) |
| Perception externe absente | Comment les autres voient l'utilisateur reste inaccessible | Non |

---

## Note sur l'usage

Ce module produit une **hypothèse structurée**, pas un diagnostic.
Formuler systématiquement ainsi :
> *"Sur la base du profil TIPI et des questions comportementales,
> l'hypothèse est [X]. Contre-signe à vérifier : [Y]."*

Ne jamais présenter le profil Big Five comme une vérité — le présenter
comme un repère qui mérite d'être confronté à l'expérience réelle.
