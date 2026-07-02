# Fiches Personas
### Les 3 utilisateurs cibles d'EduAI, dimensions de référence

**APOCAL'IPSSI · PERTURBATION J2 · ARTEFACT 2 SUR 7**

Projet EduAI · Édition 2026 · Semaine immersive Scrum
Auteur : Mohamed Amine EL AFRIT · Licence CC BY-NC-SA 4.0

---

## IDENTIFICATION DU DOCUMENT

| Champ | Valeur |
|---|---|
| **Équipe n°** | 02 |
| **Membres** | Adja Fatou SAGNA, Ousmane NDIAYE, Houda OUADAH, Danielle Jamila KOAGNE NGANKAM, Wicramachine SERGIO, Krishmini KULAKRISHNA, Mohammed DERKAOUI |
| **Sprint concerné** | Sprint 2 (Perturbation J2 — Technique) |
| **Version** | v3.0 (Post-perturbation J2) |
| **Date de remise** | 30/06/2026 |
| **Statut** | À compléter |

> **Évolution v2.0 → v3.0** : suite à la perturbation J2 (latence inacceptable), mise à jour des critères utilisateurs impactés par la migration Llama 3.2 3B. Le pivot technique impacte les critères de succès (temps de génération < 15 s désormais garanti).
>
> **Source** : `equipe-02-persona-v3.0.pdf` — à compléter avec le contenu du PDF.

---

## Table des matières

1. [Persona primaire — Enseignante (Mme Lefèvre)](#1-persona-primaire--enseignante-mme-lefèvre)
2. [Persona secondaire — Étudiante (Léa Martin)](#2-persona-secondaire--étudiante-léa-martin)
3. [Persona tertiaire — Établissement scolaire (M. David Chen)](#3-persona-tertiaire--établissement-scolaire-m-david-chen)
4. [Anti-personas](#4-anti-personas)
5. [Évolutions v2.0 → v3.0](#5-évolutions-v20--v30)
6. [Grille d'auto-évaluation](#grille-dauto-évaluation)
7. [Références et conventions](#références-et-conventions)

---

## PRÉAMBULE

### Pourquoi cette version v3.0 ?

La perturbation J2 (technique) a révélé une latence de **42,3 s** inacceptable pour les utilisateurs. La décision ADR-0002 (migration vers Llama 3.2 3B) ramène la latence à **12,4 s p50**, ce qui modifie les critères de succès des personas et leur niveau de tolérance.

Cette v3.0 met à jour les personas en conséquence et consolide les apprentissages terrain.

---

## 1. Persona primaire — Enseignante · Mme Lefèvre

### 1.1. Identité

| Champ | Valeur |
|---|---|
| **Nom / Prénom** | Mme Sophie Lefèvre |
| **Âge** | 42 ans |
| **Profession** | Professeure de Communication, BTS, lycée privé sous contrat |
| **Localisation** | Lyon · trajet voiture 25 min · établissement Lyon 6ᵉ |
| **Situation** | Mariée, 2 enfants (12 et 15 ans), salaire ~2 700 € net/mois |

### 1.2. Contexte d'usage

*(À compléter depuis le PDF source)*

### 1.3. Compétences numériques

*(À compléter depuis le PDF source)*

### 1.4. Frustrations / pain points (chiffrés)

*(À compléter depuis le PDF source)*

### 1.5. Objectifs (jobs-to-be-done, SMART)

*(À compléter depuis le PDF source)*

### 1.6. Critères de succès personnels — mis à jour post-J2

- « Si le quiz est généré en moins de 15 secondes devant ma classe, j'adopte définitivement. » *(seuil durci post-benchmark J2)*
- « Si je peux exporter en Word pour l'imprimer en salle des profs, c'est parfait. »
- « Si le barème est conforme aux critères du Ministère dès la première génération, je supprime Excel. »
- « Si ça plante 1 fois en cours devant 28 ados, je n'y reviens jamais. »

---

## 2. Persona secondaire — Étudiante · Léa Martin

### 2.1. Identité

| Champ | Valeur |
|---|---|
| **Nom / Prénom** | Léa Martin (fictif) |
| **Âge** | 20 ans |
| **Profession** | Étudiante en L2 droit, Paris II Panthéon-Assas |
| **Localisation** | Paris 5ᵉ · trajet quotidien RER B 35 min |
| **Situation** | Boursière échelon 4, colocation 3 personnes |

### 2.2. Contexte d'usage

*(À compléter depuis le PDF source)*

### 2.3. Compétences numériques

*(À compléter depuis le PDF source)*

### 2.4. Frustrations / pain points (chiffrés)

*(À compléter depuis le PDF source)*

### 2.5. Objectifs (jobs-to-be-done, SMART)

*(À compléter depuis le PDF source)*

### 2.6. Critères de succès personnels — mis à jour post-J2

- « Si le quiz est prêt en moins de 15 secondes, je l'utilise même dans le RER. » *(seuil durci post-benchmark J2)*
- « Si ça plante 1 fois en bibliothèque devant mes amies, je n'y reviens jamais. »
- « Si l'application propose des explications claires quand je me trompe, je l'utilise tous les jours. »

---

## 3. Persona tertiaire — Établissement scolaire · M. David Chen

### 3.1. Identité

| Champ | Valeur |
|---|---|
| **Nom / Prénom** | M. David Chen (fictif) |
| **Âge** | 51 ans |
| **Profession** | Directeur des études d'un lycée privé sous contrat (1 200 élèves) |
| **Localisation** | Lyon 6ᵉ · même établissement que Mme Lefèvre |
| **Situation** | Marié, enfants grands, 25 ans d'expérience enseignement |

### 3.2. Contexte d'achat

*(À compléter depuis le PDF source)*

### 3.3. Compétences numériques

*(À compléter depuis le PDF source)*

### 3.4. Frustrations / pain points

*(À compléter depuis le PDF source)*

### 3.5. Objectifs (jobs-to-be-done)

*(À compléter depuis le PDF source)*

### 3.6. Critères de succès personnels

*(À compléter depuis le PDF source)*

---

## 4. Anti-personas

### 4.1. Anti-persona du persona Étudiant

**Élève de primaire ou collège (< 15 ans).** EduTutor exige un cours fourni au format PDF ou texte de niveau supérieur. L'autonomie nécessaire n'est pas alignée avec ce profil.

### 4.2. Anti-persona du persona Enseignant

**Enseignant·e du primaire ou retraité·e en autoformation.** Le besoin de générer des supports d'évaluation à grande échelle n'existe pas dans ces contextes.

### 4.3. Anti-persona du persona Établissement

**École internationale sans contrainte RGPD.** Notre différenciation est le local-first et la souveraineté des données — pas le bon choix pour les établissements acceptant les LLM US.

---

## 5. Évolutions v2.0 → v3.0

| Élément | v2.0 | v3.0 (post-J2) |
|---|---|---|
| Seuil de tolérance latence (Mme Lefèvre) | < 5 min pour générer | **< 15 s** (benchmark 12,4 s p50) |
| Seuil de tolérance latence (Léa) | < 5 min | **< 15 s** |
| Modèle LLM référencé | Llama 3.1 8B | **Llama 3.2 3B** (ADR-0002) |
| KPI qualité quiz | 8,2/10 | **8,0/10** (perte 2% assumée) |
| Critères de succès | Généralistes | Chiffrés post-benchmark |

---

## ✅ Grille d'auto-évaluation

| Critère qualité | Auto-évaluation | Commentaire / preuve |
|---|---|---|
| Les 3 personas couvrent les 3 niveaux cibles du PVB | ⬜ À vérifier | Compléter depuis PDF source |
| Le pivot technique J2 est reflété dans les critères de succès | ✅ Oui | Seuil 15 s mis à jour dans 1.6 et 2.6 |
| Chaque persona a les 6 dimensions | ⬜ Partiel | Sections 1.2 à 2.5 à compléter depuis PDF |
| Frustrations et objectifs sont chiffrés | ⬜ Partiel | À compléter depuis PDF source |
| Tableau d'évolution v2.0 → v3.0 présent | ✅ Oui | Section 5 |
| Document validé par l'équipe complète | ⬜ À confirmer | |

---

## 📚 Références et conventions

### Références incontournables

- Cours Agile/Scrum (Mohamed EL AFRIT) : mohamedelafrit.com/teaching/Master_Classe_Agile/cours.html
- Scrum Guide officiel FR : scrumguides.org/docs/scrumguide/v2020/2020-Scrum-Guide-French.pdf
- Site APOCAL'IPSSI : mohamedelafrit.com/teaching/APOCALIPSSI

### Historique des versions

| Version | Date | Résumé des changements |
|---|---|---|
| v1.0 | 29/06/2026 | Personas initiaux, enseignant secondaire |
| v2.0 | 29/06/2026 | Pivot J1 : enseignant·e = primaire, anti-personas |
| v3.0 | 30/06/2026 | Pivot J2 : seuils latence < 15 s, modèle Llama 3.2 3B |

---

*Mohamed Amine EL AFRIT · APOCAL'IPSSI 2026 · CC BY-NC-SA 4.0*
