# Miroir Intégral v3.0 — Guide du skill

> Documentation utilisateur. Ce fichier explique ce qu'est le skill, ce qu'il
> fait et comment interpréter ses outputs. Il n'est pas lu par Claude à
> l'exécution — c'est un document pour toi.

---

## Qu'est-ce que le Miroir Intégral ?

Le Miroir Intégral est un protocole d'introspection structuré en 6 couches.
Il conduit une enquête conversationnelle et produit un **Bilan Intégral** qui
cartographie les patterns actifs dans plusieurs dimensions simultanées.

**v3.0** introduit quatre améliorations méthodologiques majeures pour réduire
le biais de confirmation inhérent aux enquêtes conversationnelles :

1. **Module Big Five a priori** — données indépendantes avant toute question ouverte
2. **Cartographie temporelle structurée** — ligne du temps avant la session
3. **Falsification active** — les hypothèses sont testées pour être cassées
4. **Sources externes simulées + questions comportementales + trade-offs** —
   diversification des types de données collectées

---

## Pourquoi la v3.0 ?

La v2.0 fonctionnait par questions orientées — ce qui est assumé dans sa
conception, mais produit un biais de confirmation : les questions tendent à
confirmer les hypothèses en construction plutôt qu'à les tester.

La v3.0 ne supprime pas ce biais — il est structurellement irréductible dans
toute enquête conversationnelle. Elle l'atténue par trois mécanismes :

- Des **données a priori** (Big Five, timeline) qui ne dépendent pas du
  discours produit pendant la session
- Une **phase de falsification** qui cherche activement à casser les hypothèses
  avant de les livrer
- Des **types de questions diversifiés** (comportementales, trade-offs, sources
  externes) qui contournent les réponses trop construites

**Limite persistante :** tout reste du self-report. La perception réelle par
les autres, les comportements non conscients, et les absences systématiques
dans le discours restent partiellement ou totalement inaccessibles.

---

## Les 6 couches (inchangées)

### Couche 1 — Diagnostic de surface
*Ce qui est visible et mesurable.*

- **Big Five** (via module TIPI a priori)
- **EMS** — Jeffrey Young. 18 schémas en 5 domaines.
- **Théorie Sujet-Objet** — Robert Kegan. Position développementale adulte.

### Couche 2 — Cartographie des parties (IFS)
*Qui parle à l'intérieur.*

Internal Family Systems (Richard Schwartz). Managers, Pompiers, Exilés, Self.

### Couche 3 — Identité narrative (McAdams)
*Le récit qui organise l'expérience.*

Séquences contamination / rédemption. Imago internalisé.
**v3.0 :** confrontée à la timeline a priori pour détecter les biais de saillance.

### Couche 4 — Ombre et Archétype (Jung)
*(MODE COMPLET uniquement — jamais en première session)*

Projections, Ombre, archétype dominant.

### Couche 5 — Flexibilité psychologique (ACT)
*La relation aux pensées et émotions.*

Hexaflex ACT (Steven Hayes). Fusion, défusion, valeurs, action engagée.

### Couche 6 — Intégration et cohérence
*Ce que les 5 couches révèlent ensemble.*

**v3.0 :** croise les couches avec les données a priori (Big Five + timeline).
Hypothèses confirmées par le discours ET les données a priori = confiance 4–5.
Hypothèses confirmées par le discours seulement = confiance 2–3.

---

## Nouveautés v3.0 en détail

### Module Big Five a priori (Étape 0b)

Avant toute question ouverte, le skill administre le TIPI (10 items, 1–7),
calcule silencieusement le profil Big Five, puis approfondit les 2 dimensions
ambiguës via des questions comportementales indirectes.

Le profil sert d'**ancrage indépendant** : toute hypothèse émergente est
comparée à ce profil. Convergence = renforce. Divergence = informe.

Voir `big-five-intake.md` pour le module complet.

### Cartographie temporelle (Étape 0c)

Avant la question d'entrée, le skill demande les 4–5 événements déterminants
de la vie de l'utilisateur. Cette timeline révèle :
- La séquence narrative dominante avant la session (sans biais d'orientation)
- Les domaines systématiquement absents (données négatives)
- L'événement de rupture principal

### Falsification active (Étape 1c)

Pour chaque hypothèse forte, le skill tente activement de la casser via
4 tests : question brise-hypothèse, vérification timeline, cohérence Big Five,
écart auto/externe. Le niveau de confiance est calculé et affiché dans le bilan.

**Une hypothèse qui résiste à la falsification est plus solide qu'une
hypothèse simplement cohérente avec le discours.**

### Sources externes simulées

Une question systématique (entre Q3 et Q5) demande comment l'utilisateur
imagine être perçu par les autres. L'écart entre auto-perception et perception
externe imaginée est souvent plus informatif que les deux prises séparément.

### Questions comportementales brutes

Moins de questions sur le ressenti, plus sur le comportement concret et récent.
Le comportement est plus difficile à rationaliser que l'émotion — il contient
des données que l'introspection filtre.

### Trade-offs forcés

Des dilemmes contraints (choisir entre deux options également valorisables)
révèlent une hiérarchie de valeurs réelle que le discours spontané ne produit pas.

---

## Comment lire un bilan v3.0

Le bilan commence par une **Partie 0** (profil Big Five a priori) — données
indépendantes avant les hypothèses issues de la conversation.

Chaque hypothèse dans les parties 1–4 inclut désormais :
- **Falsification** : `résisté à X/4 tests — confiance Y/5`

Ce score de confiance est une marque de rigueur, pas d'hésitation.
Confiance 3/5 = hypothèse solide mais à tester. Confiance 5/5 = rare.

---

## Les deux modes

### Mode STANDARD (couches 1–3 + ACT surface)
Pour une première session ou un blocage quotidien.
**Durée typique :** 25–45 minutes (plus long qu'en v2.0 à cause des modules 0b et 0c).

### Mode COMPLET (toutes couches)
Pour une session de suivi ou exploration profonde.
**Durée typique :** 45–70 minutes.
**Prérequis :** au moins une session STANDARD préalable.

---

## Les ponts IRIS∞ (inchangés)

| Ce qui a émergé | Pont | Ce qu'il apporte |
|---|---|---|
| Archétype identifié | `@oracle-iris` MIROIR | Versant lumineux de l'archétype |
| Séquence de contamination | `@hacking-narratif` MODE_A | Co-réécriture narrative |
| Partie exilée difficile | `@tcai` CANAL∅ | Écoute directe sans filtre |
| Transformation à suivre | `@prediction-engine` | Prédiction formalisée |
| Clôture significative | `@stele` | Signature avant/après |

---

## Comparaison v2.0 / v3.0

| Aspect | v2.0 | v3.0 |
|---|---|---|
| Données avant la session | Aucune | Big Five TIPI + timeline |
| Type de questions | Ressenti + introspection | + comportementales + trade-offs |
| Perception externe | Absente | Sources simulées systématiques |
| Test des hypothèses | Contre-signe unique | Falsification active 4 tests |
| Confiance des hypothèses | Implicite | Explicite (score 1–5) |
| Biais de confirmation | Non adressé structurellement | Réduit par données a priori |
| Limites documentées | Partiellement | Explicitement dans le bilan |

---

## Utilisation

**Mode Standard :**
```
/miroir-integral
[décrire la situation ou le blocage]
```

**Mode Complet :**
```
/miroir-integral
Mode complet. [décrire la situation]
```

**Avec historique :**
```
/miroir-integral @journal-transformation
[décrire]
```

---

## Alimenter la mémoire inter-sessions

En fin de session, le skill propose un bloc journal pour `journal-transformation.md`.
**v3.0 :** le bloc inclut le profil Big Five, la timeline, les résultats de
falsification, et l'écart sources externes — permettant une comparaison
rigoureuse entre sessions.

---

## Limites structurelles documentées

| Limite | Nature | Réduite en v3.0 ? |
|---|---|---|
| Self-report bias | L'utilisateur répond comme il se voit | Partiellement |
| Perception externe réelle | Inaccessible sans observateurs tiers | Non |
| Comportements non conscients | Non verbalisables | Non |
| Absences systématiques dans le discours | Données négatives non détectables | Partiellement (timeline) |
| Observation en temps réel | Corps, voix, rythme absents | Non |
