# Product Vision Board
### La direction du produit EduTutor IA en 6 sections

**APOCAL'IPSSI · CADRAGE · ARTEFACT 1 SUR 7**

Projet EduTutor IA · Édition 2026 · Semaine immersive Scrum
Auteur : Mohamed Amine EL AFRIT · Licence CC BY-NC-SA 4.0

---

## IDENTIFICATION DU DOCUMENT

| Champ | Valeur |
|---|---|
| **Équipe n°** | 02 |
| **Membres** | Danielle Jamila KOAGNE NGANKAM, Krishmini KULAKRISHNA, Wicramachine SERGIO, Houda OUADAH, Adja Fatou SAGNA, Mohammed DERKAOUI, Ousmane NDIAYE |
| **Sprint concerné** | Cadrage (J2) |
| **Version** | v2.1 (Post-perturbation Technique) |
| **Date de remise** | 30/06/2026 13h00 |
| **Statut** | En itération |

---

## Table des matières

1. [Vision](#1-vision)
2. [Target Group (cibles utilisateurs)](#2-target-group-cibles-utilisateurs)
3. [Needs (besoins résolus)](#3-needs-besoins-résolus)
4. [Product (le produit en 3-5 traits)](#4-product-le-produit-en-3-5-traits)
5. [Business Goals (objectifs de succès)](#5-business-goals-objectifs-de-succès)
6. [Différenciateurs vs concurrents](#6-différenciateurs-vs-concurrents)
7. [Grille d'auto-évaluation](#grille-dauto-évaluation)
8. [Références et conventions](#références-et-conventions)

---

## PRÉAMBULE

### Pourquoi cet artefact ?

Le Product Vision Board, formalisé par Roman Pichler, condense en une seule page la direction stratégique du produit. Il répond à cinq questions : quelle est l'ambition long terme (Vision) ? pour qui (Target Group) ? pour quels besoins (Needs) ? avec quel produit (Product) ? et comment saurons-nous que c'est un succès (Business Goals) ?

Cette version v2.1 intègre les ajustements techniques issus de la perturbation J2 (latence inacceptable) : migration vers Llama 3.2 3B et mise à jour des KPI de performance.

---

## 1. Vision

> **Objectif.** Décrire l'impact long terme du produit en 1 à 2 phrases. La Vision survit aux releases.
>
> **Format attendu.** Une seule phrase mémorisable, orientée bénéfice utilisateur, pas fonctionnalité.

### 1.1. Vision EduTutor IA : version équipe

Permettre à chaque étudiante du supérieur de transformer n'importe quel cours en quiz de révision personnalisé en moins de 15 secondes, et offrir aux enseignant·e·s un gain de 10h/mois de préparation de supports d'évaluation avec suivi de classe, le tout sans qu'aucune donnée pédagogique ne quitte le territoire européen.

---

## 2. Target Group (cibles utilisateurs)

> **Objectif.** Décrire qui utilise réellement le produit. Un produit qui parle à « tout le monde » ne parle à personne.
>
> **Format attendu.** 3 niveaux de cibles : primaire (acteur principal), secondaire (acteur émergent), tertiaire (acheteur B2B).

### 2.1. Cible primaire — Étudiant·e du supérieur

| Champ | Valeur |
|---|---|
| **Profil** | Léa Martin, 20 ans, L2 droit Paris II. Smartphone Android personnel (Samsung A53). Révise 8h/semaine, dont 3h perdues à chercher des fiches. |
| **Volume FR** | ~2,7M d'étudiants dans le supérieur (Chiffres MESR 2024) |
| **Pain point** | 5h à 15h/semaine à chercher des supports |
| **Critère clé** | Gratuite/freemium + confidentialité des cours déposés + rapidité (< 15 s par quiz — seuil revu post-J2) |

### 2.2. Cible secondaire — Enseignant·e (persona émergente J1 : Mme Lefèvre)

| Champ | Valeur |
|---|---|
| **Profil** | Mme Sophie Lefèvre, 42 ans. Enseignante BTS Communication Lyon |
| **Volume FR** | ~770 000 enseignants tous niveaux (Éducation nationale 2024) |
| **Pain point** | ~12h/mois en correction et préparation de supports d'évaluation variés |
| **Critère clé** | Interface ultrasimple + conformité RGPD contractuelle + export Word/PDF des quiz + suivi de classe |

### 2.3. Cible tertiaire — Établissement scolaire (acheteur B2B)

| Champ | Valeur |
|---|---|
| **Profil** | M. David Chen, 51 ans, directeur des études d'un lycée privé à Lyon. Décide pour 1 200 élèves |
| **Volume FR** | ~7 500 lycées + ~3 500 établissements supérieurs |
| **Pain point** | Budget edtech contraint (~12 000 €/an, soit 10€/élève) + obligation RGPD non négociable |
| **Critère clé** | Hébergement UE souverain + facturation prévisible + appel d'offres < 6 mois |

---

## 3. Needs (besoins résolus)

> **Objectif.** Décrire les besoins concrets que le produit résout pour chaque cible.
>
> **Format attendu.** 3 à 5 besoins par cible, formulés comme des verbes d'action utilisateur, mesurables.

### 3.1. Besoins de la cible primaire (Étudiant)

- Générer en **12,4 s** un quiz de révision sur n'importe quel chapitre d'un cours fourni *(benchmark post-J2)*
- Identifier ses lacunes par chapitre avant un examen (sans correcteur humain)
- Réviser hors-ligne (transports, lieu sans wifi)
- Retrouver et rejouer ses anciens quiz via un historique persisté
- Obtenir un retour immédiat sur ses erreurs avec explications pédagogiques

### 3.2. Besoins de la cible secondaire (Enseignant·e — Mme Lefèvre)

*Besoins émergents J1 :*

- Préparer des supports d'évaluation variés (quiz, QCM, questions ouvertes) en gain de temps mesurable
- Adapter automatiquement le niveau de difficulté au niveau de la classe
- Suivre l'engagement de la classe (qui a répondu, score moyen, lacunes communes)
- Exporter le quiz en format imprimable (PDF/Word) pour distribution en classe
- Réduire de 50% son temps de création d'évaluations mensuelles
- Générer automatiquement une grille de correction analytique (barème) en moins de 3 minutes

### 3.3. Besoins de la cible tertiaire (Établissement)

- Disposer d'un outil edtech RGPD conforme, sans transfert de données hors UE
- Tarification prévisible par élève / par an, sans surprise
- Adhésion d'au moins 30% des profs dès la première année
- Déployer la solution sur 2 classes pilotes dès le premier mois

---

## 4. Product (le produit en 3-5 traits)

> **Objectif.** Décrire le produit lui-même en 3 à 5 caractéristiques différenciantes. C'est la « signature » du produit, pas le scope MVP.

### 4.1. Caractéristiques signature d'EduTutor IA

- Génération de 10 QCM ultra-rapide et optimisée (**12,4 s p50** via Llama 3.2 3B — pivot post-J2)
- Fonctionnement 100% local et performant via **Llama 3.2 3B** pour garantir latence faible et souveraineté
- Interface mobile-first et hors-ligne friendly
- Questions pédagogiques traçables à leur source (préparation RAG en Release 2)
- Mode enseignant : suivi de classe + export PDF/Word des quiz + corrigés

### 4.2. MVP must-have (Release 1) — rappel imposé

| Feature | Description |
|---|---|
| **F1** | Inscription et connexion utilisateur (Django Auth standard) |
| **F2** | Saisie d'un cours : upload PDF ≤ 5 Mo ou texte ≥ 200 caractères |
| **F3** | Génération automatique d'un quiz de 10 QCM via LLM local *(Optimisation Llama 3.2 3B intégrée — mise à jour J2)* |
| **F4** | Soumission et correction automatique (une bonne réponse par QCM) |
| **F5** | Affichage du score /10 + détail bonnes/mauvaises réponses |
| **F6** | Historique persisté des quizz par utilisateur (date, cours, score) |

### 4.3. Pistes Release 2 envisagées (validées via Note MoSCoW)

- **Export Word/PDF** des quiz + corrigé — répond directement au besoin de Mme Lefèvre (distribution en classe)
- **Compte enseignant + multi-classes** — essentiel pour gérer les 28 étudiants de la classe
- **Génération automatique de barème** — gain de temps pour l'enseignant

---

## 5. Business Goals (objectifs de succès)

> **Objectif.** Définir les indicateurs permettant de dire, dans 6 ou 12 mois, si le produit est un succès.

### 5.1. Objectifs d'adoption

| KPI | Cible |
|---|---|
| Étudiants actifs hebdomadaires (WAU) | 1 000 d'ici T+6 mois |
| Rétention semaine 1 | ≥ 40% des utilisateurs reviennent dans la semaine après inscription |
| Quiz générés/jour | 500 d'ici T+4 mois |
| Enseignants actifs hebdomadaires | 50 d'ici T+6 mois *(nouveau KPI post-J1)* |

### 5.2. Objectifs de satisfaction

| KPI | Cible |
|---|---|
| NPS | > 30 d'ici T+9 mois |
| Qualité contenu | < 5% de quiz signalés « erreur factuelle » |
| Performance génération | **Temps médian réduit à 12,4 s (p50)** via Llama 3.2 3B *(mis à jour post-J2)* |
| Satisfaction enseignant | 80% des enseignants testeurs recommandent l'outil à un collègue *(nouveau KPI post-J1)* |

### 5.3. Objectifs business (long terme)

| KPI | Cible |
|---|---|
| Conversion B2B | ≥ 10 établissements scolaires sous contrat dans 12 mois |
| Coût acquisition | CAC < 8€ par utilisateur converti |
| Modèle économique | Freemium étudiant (3 quiz/jour gratuit) + licence B2B établissement (10€/élève/an) |

---

## 6. Différenciateurs vs concurrents

> **Objectif.** Cartographier la concurrence et formuler ce qui distingue EduTutor IA.

### 6.1. Cartographie des concurrents

| Concurrent | Positionnement | Limite identifiée |
|---|---|---|
| **Wilgo.ai** | Compagnon IA français pour étudiants | Cloud, dépendance OpenAI, données hors UE |
| **Leo (iamleo.ai)** | Tuteur IA Bac/sup ancré sur programmes français | Cible étudiants uniquement, pas d'angle enseignant |
| **Quizlet AI** | Cartes mémoire et quiz IA, pionnier US | Pas d'ancrage cours fourni, focus marché US |
| **Khanmigo** | Tuteur IA Khan Academy, lancé 2023 | US-first, conformité RGPD UE floue |

### 6.2. Nos 3 différenciateurs argumentés

1. **Prompts métier enseignants (enseignant-first)** : l'outil produit des supports d'évaluation prêts à distribuer, ouvrant la porte au B2B établissement.

2. **Pédagogie ancrée (RAG sur cours fourni)** : EduTutor s'engage à ancrer ses générations dans le manuel fourni, garantissant la fiabilité pédagogique.

3. **RGPD, local-first & Performance** : en plus d'être strictement souverain (contrairement à OpenAI/Anthropic), le benchmark post-J2 offre une latence locale compétitive (Llama 3.2 3B : **12,4 s p50**) face aux solutions cloud — un prérequis non négociable pour maintenir l'engagement en classe (décisions CNIL 2024).

---

## ✅ Grille d'auto-évaluation

| Critère qualité | Auto-évaluation | Commentaire / preuve |
|---|---|---|
| La Vision tient en 1 phrase mémorable et survit aux Releases | ✅ Oui | Vision ajustée temporellement pour refléter la nouvelle performance visée (« moins de 15 secondes ») |
| Les 3 niveaux de cibles sont décrits avec profil + volume + pain point | ✅ Oui | Critère clé étudiant durci (exigence de rapidité < 15 s post-J2) |
| Au moins 3 besoins par cible formulés en verbes d'action mesurables | ✅ Oui | Premier besoin étudiant indique précisément « Générer en 12,4 s un quiz » suite aux benchmarks |
| Le produit est décrit en 3 à 5 caractéristiques signature | ✅ Oui | Llama 3.2 3B cité explicitement comme moteur local garantissant latence faible |
| Les 6 features F1-F6 du MVP sont rappelées et 2-3 pistes Release 2 identifiées | ✅ Oui | F3 mise à jour pour mentionner Llama 3.2 3B |
| Les Business Goals comportent au moins 3 KPI chiffrés et datés | ✅ Oui | KPI de performance chiffré : « Temps médian de génération réduit à 12,4 s (p50) » |
| Les 4 concurrents sont cartographiés avec positionnement + limite identifiée | ✅ Oui | Wilgo, Leo, Quizlet, Khanmigo |
| Les 3 différenciateurs EduTutor IA sont argumentés au-delà du slogan | ✅ Oui | Argument #3 renforcé : latence compétitive locale face au cloud |
| Le document a été relu et validé par l'équipe complète | ✅ Oui | 7 membres : toutes les voix entendues |

---

## 📚 Références et conventions

### Références incontournables

- Cours Agile/Scrum (Mohamed EL AFRIT) : mohamedelafrit.com/teaching/Master_Classe_Agile/cours.html
- Scrum Guide officiel FR : scrumguides.org/docs/scrumguide/v2020/2020-ScrumGuideFrench.pdf
- Site APOCAL'IPSSI : mohamedelafrit.com/teaching/APOCALIPSSI

### Références spécifiques à ce document

- Roman Pichler, Product Vision Board (canvas original) : romanpichler.com/tools/product-vision-board/
- Wilgo.ai : wilgo.ai
- Leo (iamleo.ai) : iamleo.ai/fr
- Quizlet AI : quizlet.com
- Khanmigo : khanmigo.ai

### Convention de versionnement

- `v1.0` — version initiale produite lors du cadrage matinal
- `v1.1`, `v1.2` — révisions mineures (typo, ajout d'item) après revue PO
- `v2.0` — révision majeure suite à une perturbation (changement de scope)
- `v2.1` — mise à jour technique post-perturbation J2 (migration Llama 3.2 3B, KPI performance)
- Chaque version est commitée séparément avec message Git explicite
- Le statut « Validé PO » nécessite une trace écrite (commentaire, mail, Teams)

---

*Mohamed Amine EL AFRIT · APOCAL'IPSSI 2026 · CC BY-NC-SA 4.0*
