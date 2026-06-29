# APCAL'IPSSI — Product Backlog

> **Cadrage Matinal · Artefact 6 sur 7**
>
> 20 user stories organisées en 6 epics, avec critères INVEST et MoSCoW

---

## 🗂️ Identification du Document

> À compléter par l'équipe avant chaque remise

| Champ               | Valeur                                          |
|---------------------|-------------------------------------------------|
| **Équipe n°**       | 2                                               |
| **Membres**         | Adja Fatou SAGNA, Ousmane NDIAYE, Ouda OUADAH, Danielle Jamila KOAGNE NGANKAM, Wicramachine SERGIO, Krishmini KULAKRISHNA, Mohammed DERKAOUI |
| **Sprint concerné** | `[ Cadrage / Sprint 1 / ... / Sprint 7 ]`       |
| **Version**         | `[ v1.0 · v1.1 · v2.0 ]`                       |
| **Date de remise**  | `[ JJ/MM/AAAA HHhMM ]`                         |
| **Statut**          | `[ Draft · En revue PO · Validé PO · Archivé ]` |

> 💡 **Convention de nommage du fichier :**
> `equipe-XX-nom-document-vY.Z.xlsx` *(ex. equipe-03-product-backlog-v1.0.xlsx)*

---

## 🗺️ Epics — EduTutor IA

> 6 épopées correspondant aux activités utilisateur de la Story Map

> 💡 **Objectif :** Une Epic regroupe plusieurs user stories qui partagent une intention commune. Permet la vue d'ensemble du scope et facilite la priorisation.

| ID    | Epic                          | Activité utilisateur (Story Map) | Stories incluses             | SP total |
|-------|-------------------------------|----------------------------------|------------------------------|----------|
| EP-01 | Identification utilisateur    | S'inscrire                       | US-01, US-07, US-13, US-18   | n.c.     |
| EP-02 | Gestion de contenu            | Uploader un cours                | US-02, US-08, US-14          | n.c.     |
| EP-03 | Génération de quiz            | Générer un quiz                  | US-03, US-09, US-15, US-19   | n.c.     |
| EP-04 | Passage de quiz               | Passer le quiz                   | US-04, US-05, US-10, US-20   | n.c.     |
| EP-05 | Suivi de progression          | Consulter résultats              | US-06, US-11, US-16          | n.c.     |
| EP-06 | Conformité & administration   | Gérer son compte (RGPD)          | US-12, US-17                 | n.c.     |

---

## 📋 Product Backlog — EduTutor IA

> **20 user stories :** 6 MUST (MVP F1–F6) + 6 SHOULD R2 + 5 COULD R2 + 3 WON'T

> 💡 **Objectif :** Liste ordonnée et priorisée de TOUTES les fonctionnalités du produit. Source unique de vérité du scope.

> 📐 **Format INVEST :** Independent · Negotiable · Valuable · Estimable · Small · Testable
> Format de phrase : *« En tant que [persona], je veux [action] afin de [bénéfice]. »*

> ✅ **BON :** « En tant qu'étudiante, je veux générer un quiz en moins de 60 s à partir de mon PDF, afin de réviser efficacement avant les partiels. »
>
> ❌ **À ÉVITER :** « On veut une fonctionnalité de génération » *(pas INVEST, ni persona ni bénéfice clair)*

---

### 🔴 MUST — MVP (Sprint 1 à 4)

#### US-01 · EP-01 · `MUST` · 3 SP · Sprint 1

**En tant qu'étudiant·e**, je veux créer un compte avec email et mot de passe, afin de sauvegarder mes quizz et y revenir.

- **Persona :** Étudiant·e
- **Critères d'acceptation (Given / When / Then) :**
  - **G :** visiteur non authentifié sur `/signup`
  - **W :** soumet email valide + mdp ≥ 8 caractères
  - **T :** compte créé, email envoyé, redirect `/upload`
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Statut :** Todo

---

#### US-02 · EP-02 · `MUST` · 5 SP · Sprint 1

**En tant qu'étudiant·e**, je veux uploader un PDF ou saisir un texte de cours, afin de ne pas avoir à recopier mon support.

- **Persona :** Étudiant·e
- **Critères d'acceptation (Given / When / Then) :**
  - **G :** user authentifié sur `/upload`
  - **W :** dépose PDF ≤ 5 Mo OU texte ≥ 200 car
  - **T :** contenu extrait, stocké, bouton « Générer » visible
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Statut :** Todo

---

#### US-03 · EP-03 · `MUST` · 8 SP · Sprint 2

**En tant qu'étudiant·e**, je veux générer un quiz de 10 QCM en moins de 60 s, afin de réviser rapidement un chapitre.

- **Persona :** Étudiant·e
- **Critères d'acceptation (Given / When / Then) :**
  - **G :** un cours stocké pour l'user
  - **W :** clique « Générer un quiz » sur `/quiz`
  - **T :** 10 QCM générés en < 60 s via Llama 3.1 8B local
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Statut :** Todo

---

#### US-04 · EP-04 · `MUST` · 3 SP · Sprint 3

**En tant qu'étudiant·e**, je veux soumettre mes réponses et obtenir une correction automatique, afin de savoir où je me situe.

- **Persona :** Étudiant·e
- **Critères d'acceptation (Given / When / Then) :**
  - **G :** un quiz généré et affiché
  - **W :** user soumet ses 10 réponses
  - **T :** chaque réponse comparée, statut bon/mauvais enregistré
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Statut :** Todo

---

#### US-05 · EP-04 · `MUST` · 3 SP · Sprint 3

**En tant qu'étudiant·e**, je veux voir mon score /10 et le détail bonnes/mauvaises réponses, afin de mesurer ma progression.

- **Persona :** Étudiant·e
- **Critères d'acceptation (Given / When / Then) :**
  - **G :** un quiz soumis
  - **W :** user arrive sur `/resultat`
  - **T :** score /10 affiché + 10 questions avec corrections détaillées
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Statut :** Todo

---

#### US-06 · EP-05 · `MUST` · 3 SP · Sprint 4

**En tant qu'étudiant·e**, je veux consulter l'historique de mes quizz passés, afin de suivre mon évolution dans le temps.

- **Persona :** Étudiant·e
- **Critères d'acceptation (Given / When / Then) :**
  - **G :** user authentifié sur `/historique`
  - **W :** la page se charge
  - **T :** liste des quizz triés par date desc, avec titre/date/score/refaire
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Statut :** Todo

---

### 🟡 SHOULD — Release 2 (Sprint 5 à 7)

#### US-07 · EP-01 · `SHOULD` · 3 SP · Sprint 6

**En tant qu'étudiant·e**, je veux réinitialiser mon mot de passe via email, afin de pouvoir récupérer mon compte sans support.

- **Persona :** Étudiant·e
- **Critère type :** lien magique valide 24 h, redirect `/reset-password`
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Statut :** Backlog

---

#### US-08 · EP-02 · `SHOULD` · 5 SP · Sprint 6

**En tant qu'étudiant·e**, je veux une bibliothèque pour mes cours uploadés, afin de retrouver vite mes PDF d'un semestre.

- **Persona :** Étudiant·e
- **Critère type :** page `/library` liste cours avec date, titre, nb quizz
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Statut :** Backlog

---

#### US-09 · EP-03 · `SHOULD` · 5 SP · Sprint 6

**En tant qu'étudiant·e**, je veux choisir le niveau de difficulté et le nombre de questions (5–20), afin d'adapter à mon temps disponible.

- **Persona :** Étudiant·e
- **Critère type :** 3 niveaux (facile/moyen/dur) + slider 5–20 sur `/quiz`
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Statut :** Backlog

---

#### US-10 · EP-04 · `SHOULD` · 3 SP · Sprint 7

**En tant qu'étudiant·e**, je veux un mode timer optionnel par question, afin de m'entraîner aux conditions d'examen.

- **Persona :** Étudiant·e
- **Critère type :** toggle ON/OFF + slider 10–30 s configurable
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Statut :** Backlog

---

#### US-11 · EP-05 · `SHOULD` · 5 SP · Sprint 7

**En tant qu'étudiant·e**, je veux un dashboard de progression par chapitre, afin de cibler mes révisions sur mes lacunes.

- **Persona :** Étudiant·e
- **Critère type :** page `/dashboard` avec graphique en barres score / chapitre
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Statut :** Backlog

---

#### US-12 · EP-06 · `SHOULD` · 5 SP · Sprint 5

**En tant qu'utilisateur·trice**, je veux exporter toutes mes données en JSON et CSV, afin d'exercer mon droit d'accès Art. 15 RGPD.

- **Persona :** Tous personas
- **Critère type :** bouton export → ZIP avec `quizz.json` + `reponses.csv` + `audit.json`
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Statut :** Backlog

---

### 🔵 COULD — Si capacité disponible

#### US-13 · EP-01 · `COULD` · 5 SP

**En tant qu'étudiant·e**, je veux me connecter via Google ou Apple OAuth, afin d'éviter de gérer un énième mot de passe.

- **Persona :** Étudiant·e
- **Critère type :** boutons OAuth + provider Django allauth
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Sprint :** n.c. &emsp; **Statut :** Backlog

---

#### US-14 · EP-02 · `COULD` · 8 SP

**En tant qu'étudiant·e**, je veux importer un cours depuis une URL web (article, blog), afin d'enrichir mes sources de révision.

- **Persona :** Étudiant·e
- **Critère type :** champ URL + scraping article + filtrage textes parasites
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Sprint :** n.c. &emsp; **Statut :** Backlog

---

#### US-15 · EP-03 · `COULD` · 13 SP

**En tant qu'enseignant·e**, je veux générer des questions ouvertes corrigées par le LLM, afin de varier les types d'évaluation.

- **Persona :** Enseignant·e
- **Critère type :** mode « question ouverte » avec barème indicatif et correction LLM
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Sprint :** n.c. &emsp; **Statut :** Backlog

---

#### US-16 · EP-05 · `COULD` · 8 SP

**En tant qu'étudiant·e**, je veux que l'app identifie mes lacunes par chapitre, afin de me concentrer sur ce qui pèche.

- **Persona :** Étudiant·e
- **Critère type :** algo agrégation scores < 5/10 + tag chapitre concerné
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Sprint :** n.c. &emsp; **Statut :** Backlog

---

#### US-17 · EP-06 · `COULD` · 5 SP

**En tant qu'utilisateur·trice**, je veux supprimer mon compte et toutes mes données, afin d'exercer mon droit à l'oubli Art. 17 RGPD.

- **Persona :** Tous personas
- **Critère type :** bouton avec confirmation 2-étapes + cron purge 30 j
- **DoR :** ☐ &emsp; **DoD :** ☐ &emsp; **Sprint :** n.c. &emsp; **Statut :** Backlog

---

### ⚫ WON'T — Hors scope (décision volontaire)

#### US-18 · EP-01 · `WON'T` · 13 SP

**En tant que DSI d'établissement**, je veux un SSO entreprise SAML/OIDC, afin d'intégrer EduTutor à mon AD/ENT.

- **Persona :** Établissement
- **Décision :** Reporté Release 3+ *(cible B2B post-prototype)*
- **DoR :** n.c. &emsp; **DoD :** n.c. &emsp; **Sprint :** n.c. &emsp; **Statut :** Won't

---

#### US-19 · EP-03 · `WON'T` · 21 SP

**En tant qu'étudiant·e**, je veux discuter avec un chatbot IA pour explorer un sujet, afin d'apprendre par dialogue.

- **Persona :** Étudiant·e
- **Décision :** Hors cible primaire *(concurrent direct Khanmigo). Ne pas y aller.*
- **DoR :** n.c. &emsp; **DoD :** n.c. &emsp; **Sprint :** n.c. &emsp; **Statut :** Won't

---

#### US-20 · EP-04 · `WON'T` · 13 SP

**En tant qu'étudiant·e**, je veux affronter d'autres étudiants en mode compétition, afin d'ajouter du fun à la révision.

- **Persona :** Étudiant·e
- **Décision :** Hors scope vision *(apprentissage personnalisé, pas gamification compétitive)*
- **DoR :** n.c. &emsp; **DoD :** n.c. &emsp; **Sprint :** n.c. &emsp; **Statut :** Won't

---

### 📊 Récapitulatif

| Priorité | Stories | SP      |
|----------|---------|---------|
| MUST     | 6       | 25      |
| SHOULD   | 6       | 26      |
| COULD    | 5       | 39      |
| WON'T    | 3       | 47      |
| **TOTAL**| **20**  | **137** |

> 20 stories · 137 SP scope total · à arbitrer contre vélocité cible ~56 SP

---

## ✅ Definition of Ready & Definition of Done

> Critères partagés par toute l'équipe, à respecter pour chaque story

### 🟢 Definition of Ready (DoR) — avant Sprint Planning

Une story est **READY** (tirable en sprint) si **TOUS** ces critères sont cochés :

- [ ] User story rédigée au format INVEST *(En tant que ... je veux ... afin de ...)*
- [ ] Persona identifié *(Étudiant·e / Enseignant·e / Établissement)*
- [ ] Priorité MoSCoW assignée et justifiée *(Must / Should / Could / Won't)*
- [ ] Critères d'acceptation explicites et testables *(format Given/When/Then de préférence)*
- [ ] Story estimée par l'équipe en story points *(Planning Poker recommandé)*
- [ ] Dépendances avec d'autres stories identifiées *(et non-bloquantes au moment du sprint)*
- [ ] Pas de question ouverte côté Product Owner *(clarté du besoin)*
- [ ] Maquettes / wireframes disponibles si la story comporte une interface *(Figma, Excalidraw)*

---

### 🟢 Definition of Done (DoD) — pour clôturer une story

Une story est **DONE** (validée Sprint Review) si **TOUS** ces critères sont cochés :

- [ ] Tous les critères d'acceptation de la story sont satisfaits *(vérifiables en démo)*
- [ ] Code reviewé par au moins 1 autre membre de l'équipe *(Pull Request approuvée)*
- [ ] Tests pertinents ajoutés *(pytest pour backend, vitest pour frontend, minimum unitaires)*
- [ ] Lint et tests verts en CI *(pipeline GitHub Actions au vert)*
- [ ] Documentation à jour *(README, docstrings, /docs/ si concept nouveau)*
- [ ] Pas de TODO/FIXME laissé sans ticket de suivi *(créer une issue si nécessaire)*
- [ ] Story démontrée et acceptée par le PO en Sprint Review
- [ ] Code mergé sur la branche principale + tag Git si fin de release
- [ ] Pas de régression introduite *(suite de tests intégrale au vert)*

---

## 📝 Grille d'auto-évaluation

> À remplir par l'équipe avant soumission au PO

| Critère qualité                                                                      | Auto-évaluation                     | Commentaire / preuve |
|--------------------------------------------------------------------------------------|-------------------------------------|----------------------|
| 20 user stories pré-remplies (6 MUST + 6 SHOULD + 5 COULD + 3 WON'T)               | ☐ Oui &emsp; ☐ Partiel &emsp; ☐ Non |                      |
| Toutes les stories sont au format INVEST *(En tant que ... je veux ... afin de ...)*| ☐ Oui &emsp; ☐ Partiel &emsp; ☐ Non |                      |
| Chaque story a une priorité MoSCoW assignée et un persona ciblé                     | ☐ Oui &emsp; ☐ Partiel &emsp; ☐ Non |                      |
| Les 6 MUST correspondent exactement aux 6 features F1–F6 imposées                   | ☐ Oui &emsp; ☐ Partiel &emsp; ☐ Non |                      |
| Les 6 MUST ont des critères d'acceptation Given/When/Then complets                  | ☐ Oui &emsp; ☐ Partiel &emsp; ☐ Non |                      |
| Chaque story est rattachée à une Epic (EP-01 à EP-06)                               | ☐ Oui &emsp; ☐ Partiel &emsp; ☐ Non |                      |
| Les story points sont estimés (au moins indicatifs)                                 | ☐ Oui &emsp; ☐ Partiel &emsp; ☐ Non |                      |
| La DoR et la DoD sont rédigées et partagées par l'équipe                            | ☐ Oui &emsp; ☐ Partiel &emsp; ☐ Non |                      |
| Le Product Backlog a été ordonné par valeur business + dépendances                  | ☐ Oui &emsp; ☐ Partiel &emsp; ☐ Non |                      |
| Toutes les stories ont été passées au crible INVEST en équipe                       | ☐ Oui &emsp; ☐ Partiel &emsp; ☐ Non |                      |
