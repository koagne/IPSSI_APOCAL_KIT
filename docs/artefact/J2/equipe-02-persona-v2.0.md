# Fiches Personas
### Les 3 utilisateurs cibles d'EduAI, dimensions de référence

**APOCAL'IPSSI · CADRAGE 2 · ARTEFACT 2 SUR 7**

Projet EduAI · Édition 2026 · Semaine immersive Scrum
Auteur : Mohamed Amine EL AFRIT · Licence CC BY-NC-SA 4.0

---

## IDENTIFICATION DU DOCUMENT

| Champ | Valeur |
|---|---|
| **Équipe n°** | 02 |
| **Membres** | Adja Fatou SAGNA, Ousmane NDIAYE, Houda OUADAH, Danielle Jamila KOAGNE NGANKAM, Wicramachine SERGIO, Krishmini KULAKRISHNA, Mohammed DERKAOUI |
| **Sprint concerné** | Cadrage (J2) |
| **Version** | v2.0 (Post-perturbation J1) |
| **Date de remise** | 29/06/2026 17h24 |
| **Statut** | ✅ Validé PO |

> **Évolution v1.0 → v2.0** : suite à la perturbation J1, l'enseignant·e devient la **cible primaire** (pivot B2B). L'étudiant·e passe en cible secondaire. Trois anti-personas ajoutés.

---

## Table des matières

1. [Persona primaire — Enseignante (émergente J1)](#1-persona-primaire--enseignante---cible-principale-émergente-j1)
2. [Persona secondaire — Étudiante du supérieur](#2-persona-secondaire--étudiante-du-supérieur)
3. [Persona tertiaire — Établissement scolaire (acheteur B2B)](#3-persona-tertiaire--établissement-scolaire-acheteur-b2b)
4. [Anti-personas (qui n'est PAS cible)](#4-anti-personas-qui-nest-pas-cible)
5. [Grille d'auto-évaluation](#grille-dauto-évaluation)
6. [Références et conventions](#références-et-conventions)

---

## PRÉAMBULE

### Pourquoi cet artefact ?

Une persona représente un utilisateur type, construit à partir de données réelles (entretiens, statistiques, observations) et non d'intuitions. Elle sert à trancher les arbitrages produit : « est-ce que Mme Lefèvre utiliserait vraiment cette fonctionnalité ? » remplace « est-ce que c'est bien ? ».

Cette version v2.0 intègre le pivot de la perturbation J1 : **l'enseignant·e devient la cible primaire** du produit. L'étudiant·e reste cible secondaire. L'établissement confirme son rôle d'acheteur B2B.

---

## 1. Persona primaire — Enseignante · Cible Principale (émergente J1)

### 1.1. Identité

| Champ | Valeur |
|---|---|
| **Nom / Prénom** | Mme Sophie Lefèvre (persona officielle perturbation J1) |
| **Âge** | 42 ans |
| **Profession** | Professeure de Communication, BTS, lycée privé sous contrat |
| **Localisation** | Lyon · trajet voiture 25 min · établissement Lyon 6ᵉ |
| **Situation** | Mariée, 2 enfants (12 et 15 ans), salaire ~2 700 € net/mois |

### 1.2. Contexte d'usage

- 28 étudiants dans sa classe BTS Communication 1ʳᵉ année
- 6h de cours/semaine + ~3h de préparation + ~3h de correction = **12h/semaine**
- Salle informatique disponible mais réseau lent (4G partagée pour les étudiants)
- Smartphones Android personnels chez les étudiants (mix de modèles 2018-2023)
- Prépare ses cours le soir chez elle sur son ordinateur portable (Asus Windows 11), connexion fibre

### 1.3. Compétences numériques

- Power user Word + Excel, autonome sur Moodle et Pronote
- Pas développeuse, allergique aux installations CLI
- Découvre l'IA générative (a testé ChatGPT 2 fois)
- Suit l'actualité edtech via Twitter/X et la newsletter Café Pédagogique
- Maîtrise visioconférence (Teams, Zoom) et génération de PDF, mais n'a jamais configuré de prompt d'IA

### 1.4. Frustrations / pain points (chiffrés)

- Corrige 28 copies × 3 quizz/semaine = **~12h de correction/mois**
- Créer 1 quiz cohérent prend **~90 minutes** de préparation
- Pas de variation des questions : les étudiants se passent les réponses entre cours
- Frustration d'avoir des quiz « plats » alors qu'elle aimerait varier types et difficultés
- **~2h par évaluation** à concevoir manuellement des grilles de correction analytiques et barèmes conformes au Ministère pour 28 étudiants

### 1.5. Objectifs (jobs-to-be-done, SMART)

- Générer 1 quiz personnalisé en **moins de 5 minutes** sur n'importe quel chapitre
- Personnaliser : niveau, nombre de questions, type (QCM / vrai-faux / questions ouvertes)
- Suivre l'engagement de la classe (qui a répondu, score moyen, lacunes communes)
- Réduire de **50%** son temps de création d'évaluations mensuelles
- Générer automatiquement une grille de correction analytique (barème) en **moins de 3 minutes**

### 1.6. Critères de succès personnels

- « Si je gagne 1h/semaine sur ma préparation, j'adopte définitivement. »
- « Si ça plante 1 fois en cours devant 28 ados, je n'y reviens jamais. »
- « Si je peux exporter en Word pour l'imprimer en salle des profs, c'est parfait. »
- « Si le barème est conforme aux critères du Ministère dès la première génération, je supprime Excel. »

---

## 2. Persona secondaire — Étudiante du supérieur

### 2.1. Identité

| Champ | Valeur |
|---|---|
| **Nom / Prénom** | Léa Martin (fictif) |
| **Âge** | 20 ans |
| **Profession** | Étudiante en L2 droit, Paris II Panthéon-Assas |
| **Localisation** | Paris 5ᵉ · trajet quotidien RER B 35 min |
| **Situation** | Boursière échelon 4, colocation 3 personnes |

### 2.2. Contexte d'usage

- Smartphone Android personnel (Samsung A53), wifi domestique fluide, 4G dans le RER
- Laptop emprunté à la BU 2 fois/semaine (pas d'ordinateur perso)
- Révise principalement en soirée 19h-22h et le dimanche après-midi
- **10h à 12h de révision/semaine**, principalement sur smartphone

### 2.3. Compétences numériques

- Power user smartphone (Instagram, TikTok, BlaBlaCar, Doctolib, ENT université)
- Autonome sur Moodle, importe fichiers PDF/Word sans souci
- A testé ChatGPT 4-5 fois pour des résumés, sans usage régulier
- Allergique aux installations CLI ou paramétrages techniques avancés

### 2.4. Frustrations / pain points (chiffrés)

- Perd **~3h/semaine** à chercher des fiches de révision, qualité aléatoire
- Les fiches trouvées en ligne sont rarement à jour avec sa promo
- Se sent surchargée à 3 semaines des partiels, sans plan de révision personnalisé
- Ne sait pas mesurer si elle « connaît » un chapitre ou si elle « croit » le connaître

### 2.5. Objectifs (jobs-to-be-done, SMART)

- Générer un quiz de révision sur n'importe quel chapitre en **moins de 5 minutes**
- Identifier ses lacunes par chapitre **2 semaines** avant les partiels (vs 3 jours avant aujourd'hui)
- Gagner **~2h/semaine** sur la recherche de supports
- Obtenir un score minimal de **80%** de bonnes réponses d'ici la fin de la 1ʳᵉ semaine de révision

### 2.6. Critères de succès personnels

- « Si je gagne au moins 1h/semaine sur ma préparation, j'adopte. »
- « Si ça plante 1 fois en bibliothèque devant mes amies, je n'y reviens jamais. »
- « Si je peux l'utiliser dans le RER sans wifi, c'est un game changer. »
- « Si l'application propose des explications claires quand je me trompe, je l'utilise tous les jours. »

---

## 3. Persona tertiaire — Établissement scolaire (acheteur B2B)

### 3.1. Identité

| Champ | Valeur |
|---|---|
| **Nom / Prénom** | M. David Chen (fictif) |
| **Âge** | 51 ans |
| **Profession** | Directeur des études d'un lycée privé sous contrat (1 200 élèves) |
| **Localisation** | Lyon 6ᵉ · même établissement que Mme Lefèvre |
| **Situation** | Marié, enfants grands, 25 ans d'expérience enseignement |

### 3.2. Contexte d'achat

- Budget edtech **~12 000 €/an** pour l'ensemble du lycée (10€/élève × 1 200)
- Cycle d'achat : **6 mois minimum** (validation pédagogique + DPO + comptabilité)
- Décide en concertation avec 3 acteurs : conseil pédagogique, DPO, gestionnaire financier
- Choisit les outils edtech 1 fois/an, en mai/juin pour la rentrée de septembre
- Rapport trimestriel d'innovation pédagogique au CA du groupe scolaire

### 3.3. Compétences numériques

- Utilisateur courant ENT/Pronote, gère les comptes profs et élèves
- Pas technique, fait confiance au DSI mutualisé du réseau d'établissements
- Lit les CGV/CGU, exige des engagements RGPD écrits
- Très sensible à la sécurité des données des mineurs

### 3.4. Frustrations / pain points

- A déjà signé pour 2 outils edtech qui ont fermé en cours d'année (risque pérennité)
- DPO refuse systématiquement les outils utilisant OpenAI ou des LLM US (transferts hors UE)
- Pression du CA pour démontrer une « stratégie IA pédagogique »
- Profs râlent quand on impose un nouvel outil → besoin d'adhésion préalable

### 3.5. Objectifs (jobs-to-be-done)

- Disposer d'un outil edtech RGPD conforme, signable sans risque juridique
- Tarification prévisible par élève / par an, sans surprise au renouvellement
- Adhésion d'au moins **30%** des profs dès la première année
- Déployer sur **2 classes pilotes** dès le premier mois avant achat global

### 3.6. Critères de succès personnels

- « Si le DPO valide les CGV en 30 min de lecture, c'est un signal positif. »
- « Si 5 profs me demandent spontanément d'élargir l'usage, je signe le renouvellement. »
- « Si je peux dire au CA "on est en avance sur l'IA" sans mentir, c'est gagné. »
- « Si l'outil est hébergé en France (souverain) et respecte le RGPD à 100%, je valide le budget sans hésiter. »

---

## 4. Anti-personas (qui n'est PAS cible)

> **Objectif.** Clarifier qui le produit NE SERT PAS volontairement. Indispensable pour trancher les arbitrages MoSCoW : si une feature ne sert que des non-cibles, c'est un Won't have.

### 4.1. Anti-persona du persona Étudiant

**Élève de primaire ou collège (< 15 ans).** EduTutor exige un cours fourni au format PDF ou texte de niveau supérieur. L'autonomie nécessaire (uploader, contextualiser, interpréter les résultats) n'est pas alignée avec ce profil. Ne pas chercher à les attirer.

### 4.2. Anti-persona du persona Enseignant

**Enseignant·e du primaire ou retraité·e en autoformation.** Le besoin de générer des supports d'évaluation à grande échelle (28 étudiants × 3 quizz) n'existe pas dans ces contextes. Élargir l'offre vers ce profil diluerait la proposition de valeur B2B.

### 4.3. Anti-persona du persona Établissement

**École internationale sans contrainte RGPD, tournée vers OpenAI/Anthropic.** Notre différenciation est précisément le local-first et la souveraineté des données. Une école qui accepte les LLM US n'a pas besoin de notre stack Ollama — nous ne sommes pas le bon choix pour eux.

---

## ✅ Grille d'auto-évaluation

| Critère qualité | Auto-évaluation | Commentaire / preuve |
|---|---|---|
| Les 3 personas couvrent les 3 niveaux cibles du PVB | ✅ Oui | Primaire (Mme Lefèvre), Secondaire (Léa Martin), Tertiaire (M. David Chen) |
| Le pivot J1 est reflété (enseignant·e = primaire) | ✅ Oui | Section 1 = Mme Lefèvre, section 2 = Léa |
| Chaque persona a les 6 dimensions (identité, contexte, compétences, frustrations, objectifs, succès) | ✅ Oui | Toutes les sections complètes |
| Frustrations et objectifs sont chiffrés | ✅ Oui | 12h/mois, 90 min/quiz, 50% gain, etc. |
| 3 anti-personas définis avec justification | ✅ Oui | Primaire, secondaire, tertiaire exclus |
| Document validé par l'équipe complète | ✅ Oui | 7 membres |

---

## 📚 Références et conventions

### Références incontournables

- Cours Agile/Scrum (Mohamed EL AFRIT) : mohamedelafrit.com/teaching/Master_Classe_Agile/cours.html
- Scrum Guide officiel FR : scrumguides.org/docs/scrumguide/v2020/2020-ScrumGuideFrench.pdf
- Site APOCAL'IPSSI : mohamedelafrit.com/teaching/APOCALIPSSI

### Convention de versionnement

- `v1.0` — personas initiaux (cadrage matinal J1) : 3 cibles, enseignant secondaire
- `v2.0` — pivot J1 : enseignant·e devient primaire, anti-personas ajoutés
- `v3.0` — mise à jour J2 : voir `perturbation/equipe-02-persona-v3.0.md`
- Chaque version est commitée séparément avec message Git explicite

---

*Mohamed Amine EL AFRIT · APOCAL'IPSSI 2026 · CC BY-NC-SA 4.0*
