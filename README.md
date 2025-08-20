# NAQ - KPI GTM

## Description

Ce document contient les métriques KPI (Key Performance Indicators) pour la stratégie GTM (Go-To-Market) de NAQ.

## Tableau des KPI GTM

| Catégorie | KPI | Définition | Guillaume | Métrique native ? |
|-----------|-----|------------|-----------|-------------------|
| **Trafic & Sessions** | Sessions | Nombre total de sessions sur le site | OK | Oui |
| | Utilisateurs uniques | Nombre de visiteurs distincts | OK | Oui |
| | Taux de rebond | % des visiteurs quittant après une seule page | OK | Oui |
| | Durée moyenne de session | Temps moyen passé par session | OK | Oui |
| | Fréquence de visite | Nombre moyen de visites par utilisateur | OK | Non |
| | Nouvelles visites | % d'utilisateurs venant pour la première fois | OK | Non |
| **Engagement & Navigation** | Pages vues | Nombre de pages consultées | OK | Oui |
| | Profondeur de visite | Nombre moyen de pages vues par session | OK | Non |
| | Temps passé sur page | Durée moyenne passée sur une page | OK | Non |
| | Scroll Depth (profondeur de scroll) | % de la page parcourue avant de quitter | OK | Non |
| | Taux de retour arrière (back) | Nombre d'utilisateurs quittant la page immédiatement via "Retour" | OK | Non |
| | Sorties par page | Pages les plus quittées du site | OK | Non |
| | Pages d'entrée | Pages sur lesquelles les visiteurs arrivent en premier | OK | Non |
| | Chemin de navigation | Parcours des utilisateurs entre les pages | OK | Non |
| **Interactions** | Clics sur CTA | Nombre de clics sur les boutons clés | OK | Non |
| | Taux de clic interne | % d'utilisateurs cliquant sur un lien interne | OK | Non |
| | Clics sur liens sortants | Nombre de clics vers des sites externes | OK | Non |
| | Vidéos visionnées | % de vidéos regardées et durée | NSP | Non |
| | Temps passé sur vidéo | Durée moyenne de visionnage | NSP | Non |
| | Téléchargements | Nombre de fichiers téléchargés (PDF, rapports, etc.) | OK | Non |
| | Copie de texte | Nombre d'utilisateurs copiant du texte du site | OK | Non |
| | Interactions avec chat | Nombre d'ouvertures et d'échanges avec un chatbot | OK | Non |
| | Activation du mode sombre | Nombre d'utilisateurs activant le mode sombre (si option) | OK | Non |
| | Changement de langue | Nombre d'utilisateurs passant d'une langue à une autre | OK | Non |
| | Ajustement du zoom | Détecte les utilisateurs zoomant sur la page | OK | Non |
| | Écriture dans les champs de formulaire | Temps passé à remplir un champ de formulaire | OK | Non |
| | Sélections de texte | Détecte les zones copiées sur le site | OK | Non |
| **Formulaires & Conversion** | Formulaires soumis | Nombre de formulaires remplis et envoyés | OK | Non |
| | Abandon de formulaire | Nombre de formulaires non terminés | OK | Non |
| | Temps passé sur formulaire | Durée moyenne pour remplir un formulaire | OK | Non |
| | Nombre de corrections dans un champ | Détecte les utilisateurs devant corriger des erreurs | OK | Non |
| | Sélection d'un champ sans remplissage | Détecte les hésitations des utilisateurs | OK | Non |
| **Performances Techniques** | Temps de chargement global | Temps total avant affichage du site | OK | Non |
| | First Contentful Paint (FCP) | Temps avant que le premier élément s'affiche | OK | Non |
| | Largest Contentful Paint (LCP) | Temps de chargement du plus grand élément visible | OK | Non |
| | Interaction to Next Paint (INP) | Temps de réponse aux interactions utilisateur | OK | Non |
| | Erreurs 404 | Nombre d'erreurs rencontrées | OK | Non |
| | Temps d'exécution des scripts | Mesure la rapidité des JavaScript | OK | Non |
| | Utilisation du cache | % des utilisateurs profitant du cache | OK | Non |
| **Accessibilité & Multi-Appareil** | Type d'appareil utilisé | Desktop, mobile, tablette | OK | Non |
| | Orientation de l'écran | Paysage vs Portrait | OK | Non |
| | Système d'exploitation | Windows, MacOS, Android, iOS | OK | Non |
| | Navigateur utilisé | Chrome, Firefox, Safari, Edge | OK | Non |
| | Taille de l'écran | Résolutions d'affichage les plus courantes | OK | Non |
| | Mode hors ligne | Détecte les utilisateurs consultant une version offline | OK | Non |
| **Comportement & Fidélisation** | Taux de visiteurs récurrents | % d'utilisateurs revenant sur le site | OK | Non |
| | Temps avant première interaction | Temps entre l'arrivée sur le site et la première action | OK | Non |
| | Nombre de visites avant conversion | Nombre moyen de sessions avant un objectif | OK | Non |
| | Engagement utilisateur par heure | Activité en fonction des horaires | OK | Non |
| | Taux de mise en favori | % d'utilisateurs ajoutant une page en favori | OK | Non |
| | Taux de partage social | Nombre de partages sur réseaux sociaux | OK | Non |
| **Événements de Désengagement** | Rage Clicks (clics répétés au même endroit) | Nombre de clics frénétiques sur un élément | OK | Non |
| | Sélections répétées | Nombre d'utilisateurs tentant plusieurs fois une action | OK | Non |
| | Taux d'interruptions | Nombre d'utilisateurs quittant une action en cours | OK | Non |
| | Temps avant sortie | Durée avant fermeture ou abandon d'une page | OK | Non |
| | Scroll-up rapide | Détecte un retour en arrière rapide dans une page | OK | Non |

## Notes et commentaires

### Points d'attention identifiés :

1. **Lycée connecté** : Sur le site jeunes, il faudra se poser la question de la place de l'lycée connecté qui phagocyte 97% du trafic et donne une vision impropre du trafic dans une approche analytique.

2. **Comparaisons** : Il faudra aussi envisager des possibles comparaisons sur certains indicateurs pour leur donner de la profondeur et plus de sens.

3. **Campagnes payantes** : Un autre souci reste notre approche des campagnes payantes. Ces campagnes (mal gérées) soulèvent des questions et des impacts sur le trafic et sa nature.

4. **Réseaux sociaux** : Voir comment remontent les RS dans nos stats. Ce pourrait être intéressant d'avoir une approche voire un dashboard.

### Recommandations :

- Mise en place d'un dashboard avec ces KPI pour donner du sens
- Possibilité de mettre en place des KPI pour remonter les performances précises des campagnes
- Approche comparative avec données internes ou externes quand cela semblera intéressant

---

## Analyse Google Tag Manager (GTM)

### Vue d'ensemble

**Container GTM :** `GTM-PHJ5HG` - nouvelle-aquitaine.fr - SEO  
**ID de mesure GA4 :** `G-3H90XSVLE9`  
**ID UA Legacy :** `UA-71857913-11`

### Statistiques

- **Tags :** 15
- **Triggers :** 32
- **Variables :** 7
- **Dossiers :** 8

### Structure des dossiers

| ID | Nom du dossier | Description |
|----|----------------|-------------|
| 135 | 01_ANALYTICS_CORE | Configuration analytique de base |
| 137 | 02_TRACKING_EVENTS | Suivi des événements utilisateur |
| 138 | 03_FORMS_CONVERSION | Conversion et formulaires |
| 139 | 04_PERFORMANCE_TECHNICAL | Performance technique |
| 140 | 05_DEVICE_CONTEXT | Contexte appareil |
| 141 | 06_BEHAVIOR_LOYALTY | Comportement et fidélisation |
| 143 | 08_CONTENT_TRAFFIC | Contenu et trafic |
| 144 | 99_SANDBOX | Tests et développement |

### Tableau des Tags

| ID | Nom | Type | Dossier | Événement GA4 | Triggers |
|----|----|----|----|----|----|
| 96 | TAG_GA4_CONFIG_ALL | googtag | 01_ANALYTICS_CORE | Configuration | 2147479553 |
| 101 | TAG_SEO_GA4_FORMULAIRE_CONTACT | gaawe | 03_FORMS_CONVERSION | generate_lead | 100 |
| 107 | TAG_SEO_GA4_CONTACT_ETAPE_1 | gaawe | 03_FORMS_CONVERSION | Contact Etape 1 | 106 |
| 109 | TAG_SEO_GA4_CONTACT_ETAPE_2 | gaawe | 03_FORMS_CONVERSION | Contact Etape 2 | 108 |
| 111 | TAG_SEO_GA4_CONTACT_ETAPE_3 | gaawe | 03_FORMS_CONVERSION | Contact Etape 3 | 110 |
| 114 | TAG_GA4_NEWSLETTER_SUBSCRIBE | gaawe | 06_BEHAVIOR_LOYALTY | Abonnement Newsletter | 113 |
| 116 | TAG_GA4_NAVIGATION_ANALYSIS | gaawe | 02_TRACKING_EVENTS | {{Click Text}} | 115 |
| 118 | TAG_SEO_GA4_LETTRE_INFO | gaawe | 06_BEHAVIOR_LOYALTY | Abonnement lettre d'info | 117 |
| 120 | TAG_GA4_CHATBOT_INTERACTION | gaawe | 02_TRACKING_EVENTS | Chatbot | 119 |
| 122 | TAG_SEO_GA4_ABONNEMENT_CP | gaawe | 06_BEHAVIOR_LOYALTY | Abonnement CP | 121 |
| 124 | TAG_SEO_GA4_ACCES_CP | gaawe | 06_BEHAVIOR_LOYALTY | {{Click Text}} | 123 |
| 126 | TAG_SEO_GA4_HP_ANALYSES | gaawe | 08_CONTENT_TRAFFIC | Analyse homepage | 125 |
| 128 | TAG_SEO_GA4_AIDES_FORM | gaawe | 03_FORMS_CONVERSION | Aides Form | 127 |
| 131 | TAG_GA4_SCROLL_DEPTH | gaawe | 02_TRACKING_EVENTS | Scrolldepth | 132 |
| 134 | TAG_GA4_FILE_DOWNLOAD | gaawe | 02_TRACKING_EVENTS | File Download | 133 |

### Tableau des Triggers

| ID | Nom | Type | Dossier | Description |
|----|----|----|----|----|
| 11 | TRG_ERREUR_404 | PAGEVIEW | 04_PERFORMANCE_TECHNICAL | Détection erreurs 404 |
| 12 | Téléphone Bordeaux | CLICK | 99_SANDBOX | Clics téléphone Bordeaux |
| 15 | TRG_ABONNEMENT_NEWSLETTER | CLICK | 06_BEHAVIOR_LOYALTY | Abonnement newsletter |
| 16 | TRG_PAGE_LETTRE_INFORMATION | PAGEVIEW | 06_BEHAVIOR_LOYALTY | Page newsletter |
| 18 | TRG_RECHERCHES_INTERNES | PAGEVIEW | 08_CONTENT_TRAFFIC | Recherches internes |
| 20 | TRG_ABONNEMENT_CP | CLICK | 06_BEHAVIOR_LOYALTY | Abonnement CP |
| 47 | TRG_ENVOI_FORMULAIRE_CONTACT | FORM_SUBMISSION | 03_FORMS_CONVERSION | Envoi formulaire contact |
| 48 | Téléphone Limoges | CLICK | 99_SANDBOX | Clics téléphone Limoges |
| 49 | Téléphone Poitiers | CLICK | 99_SANDBOX | Clics téléphone Poitiers |
| 100 | TRG_SEO_GA4_FORMULAIRE_CONTACT | CLICK | 03_FORMS_CONVERSION | Clic formulaire contact |
| 106 | TRG_SEO_GA4_CONTACT_ETAPE_1 | CLICK | 03_FORMS_CONVERSION | Contact étape 1 |
| 108 | TRG_SEO_GA4_CONTACT_ETAPE_2 | CLICK | 03_FORMS_CONVERSION | Contact étape 2 |
| 110 | TRG_SEO_GA4_CONTACT_ETAPE_3 | FORM_SUBMISSION | 03_FORMS_CONVERSION | Contact étape 3 |
| 113 | TRG_SEO_GA4_ABONNEMENT_NEWSLETTER | FORM_SUBMISSION | 06_BEHAVIOR_LOYALTY | Abonnement newsletter |
| 115 | TRG_SEO_GA4_ANALYSE_NAVIGATION | CLICK | 02_TRACKING_EVENTS | Analyse navigation |
| 117 | TRG_SEO_GA4_LETTRE_INFO | FORM_SUBMISSION | 06_BEHAVIOR_LOYALTY | Lettre d'info |
| 119 | TRG_SEO_GA4_CHATBOT | CLICK | 02_TRACKING_EVENTS | Chatbot |
| 121 | TRG_SEO_GA4_ABONNEMENT_CP | FORM_SUBMISSION | 06_BEHAVIOR_LOYALTY | Abonnement CP |
| 123 | TRG_SEO_GA4_ACCES_CP | LINK_CLICK | 06_BEHAVIOR_LOYALTY | Accès CP |
| 125 | TRG_SEO_GA4_HP_ANALYSES | LINK_CLICK | 08_CONTENT_TRAFFIC | Analyses homepage |
| 127 | TRG_SEO_GA4_AIDES_FORM | FORM_SUBMISSION | 03_FORMS_CONVERSION | Formulaire aides |
| 132 | TRG_GA4_SCROLLDEPTH | SCROLL_DEPTH | 02_TRACKING_EVENTS | Profondeur de scroll |
| 133 | TRG_GA4_FILE_DOWNLOAD | CLICK | 02_TRACKING_EVENTS | Téléchargements |

### Tableau des Variables

| ID | Nom | Type | Dossier | Description |
|----|----|----|----|----|
| 3 | document.title | j | 05_DEVICE_CONTEXT | Titre du document |
| 4 | VAR_GA4_MEASUREMENT_ID | cid | 01_ANALYTICS_CORE | ID de mesure GA4 |
| 5 | VAR_GA4_ID_LEGACY | c | 01_ANALYTICS_CORE | ID UA Legacy |
| 49 | VAR_GA_UA_SCROLL | c | 02_TRACKING_EVENTS | Variable scroll UA |
| 50 | VAR_GA4_ID_CONFIG | gas | 01_ANALYTICS_CORE | Configuration GA4 |
| 51 | VAR_GTM_START | v | 01_ANALYTICS_CORE | Variable GTM start |
| 55 | VAR_DOM_RECHERCHE_INTERNE | d | 08_CONTENT_TRAFFIC | Recherche interne |

### Problèmes identifiés

#### ⚠️ Problèmes critiques

1. **Triggers orphelins :** 18 triggers ne sont utilisés par aucun tag
   - Cela peut indiquer des configurations obsolètes ou des erreurs de configuration
   - Recommandation : Nettoyer les triggers inutilisés

2. **Variables en double :**
   - `VAR_GA4_ID_LEGACY` et `VAR_GA_UA_SCROLL` ont la même valeur (`UA-71857913-11`)
   - Recommandation : Consolider en une seule variable

#### 🔍 Problèmes mineurs

1. **Nommage incohérent :** Mélange de conventions de nommage (TAG_, TRG_, VAR_)
2. **Dossier Sandbox :** Présence de tests dans le dossier de production
3. **Événements dynamiques :** Certains tags utilisent `{{Click Text}}` comme nom d'événement

### Liste des Triggers Orphelins (Non Utilisés)

**Total : 18 triggers orphelins**

#### 📁 04_PERFORMANCE_TECHNICAL (1 trigger)
| ID | Nom | Type | Description |
|----|----|----|----|
| 11 | TRG_ERREUR_404 | PAGEVIEW | Détection erreurs 404 (titre contient "Page non trouvée") |

#### 📁 99_SANDBOX (3 triggers)
| ID | Nom | Type | Description |
|----|----|----|----|
| 12 | Téléphone Bordeaux | CLICK | Clics sur tel:0557578000 |
| 48 | Téléphone Limoges | CLICK | Clics sur tel:0555451900 |
| 49 | Téléphone Poitiers | CLICK | Clics sur tel:0549557700 |

#### 📁 06_BEHAVIOR_LOYALTY (5 triggers)
| ID | Nom | Type | Description |
|----|----|----|----|
| 15 | TRG_ABONNEMENT_NEWSLETTER | CLICK | Abonnement newsletter (ancien trigger) |
| 16 | TRG_PAGE_LETTRE_INFORMATION | PAGEVIEW | Page d'inscription newsletter |
| 20 | TRG_ABONNEMENT_CP | CLICK | Abonnement CP (ancien trigger) |
| 72 | TRG_PAGE_LETTRE_INFORMATION_VALIDATION | PAGEVIEW | Validation page newsletter |
| 102 | TRG_SEO_GA_VALIDATION_INSCRIPTION_NEWSLETTER | CLICK | Validation inscription newsletter |

#### 📁 08_CONTENT_TRAFFIC (3 triggers)
| ID | Nom | Type | Description |
|----|----|----|----|
| 18 | TRG_RECHERCHES_INTERNES | PAGEVIEW | Recherches internes (form elasticsearch) |
| 56 | TRG_HISTORY_EVENT_BACK_TO_SERP | HISTORY_CHANGE | Retour aux résultats de recherche |
| 75 | TRG_DOM_RECHERCHE_INTERNE_VALIDE | DOM_READY | Validation recherche interne |

#### 📁 03_FORMS_CONVERSION (2 triggers)
| ID | Nom | Type | Description |
|----|----|----|----|
| 47 | TRG_ENVOI_FORMULAIRE_CONTACT | FORM_SUBMISSION | Envoi formulaire contact (ancien) |
| 97 | TRG_ENVOI_FORMULAIRE_CONTACT_2 | FORM_SUBMISSION | Envoi formulaire contact v2 (form ID: naq-contact-form) |

#### 📁 02_TRACKING_EVENTS (4 triggers)
| ID | Nom | Type | Description |
|----|----|----|----|
| 69 | TRG_SCROLL_30_POURCENTS | SCROLL_DEPTH | Scroll 30% (ancien) |
| 71 | TRG_SCROLL_90_POURCENTS | SCROLL_DEPTH | Scroll 90% (ancien) |
| 73 | TRG_YOUTUBE_TRACKING_GTM2 | YOU_TUBE_VIDEO | Tracking YouTube (ancien) |
| 129 | TRG_GA_DOWNLOAD | CLICK | Téléchargements (ancien, regex .doc/.pdf/.zip) |

### Recommandations d'optimisation

#### 🧹 Nettoyage prioritaire
- **Supprimer immédiatement :** Les 3 triggers téléphone dans le dossier Sandbox
- **Consolider :** Les triggers de scroll (69, 71) avec le nouveau trigger 132
- **Vérifier :** Les triggers de formulaire contact (47, 97) - garder le plus récent
- **Nettoyer :** Les triggers YouTube et téléchargement obsolètes

#### 📊 Amélioration du tracking
- Standardiser les noms d'événements GA4
- Ajouter des paramètres personnalisés pour enrichir les données
- Implémenter le tracking des erreurs JavaScript

#### 🔧 Optimisation technique
- Utiliser des variables personnalisées pour les valeurs répétées
- Standardiser la convention de nommage
- Ajouter des commentaires dans les configurations

#### 📈 Alignement avec les KPI
- Vérifier que tous les KPI identifiés dans le tableau sont trackés
- Ajouter les métriques manquantes (temps passé sur vidéo, etc.)
- Implémenter le tracking des événements de désengagement

#### 🎯 Priorités d'implémentation

**Phase 1 - Critique :**
- Erreurs 404 (trigger orphelin à réactiver)
- Vidéos visionnées (trigger orphelin à réactiver)
- Abandon de formulaire
- Temps passé sur formulaire

**Phase 2 - Important :**
- Performances techniques (FCP, LCP, INP)
- Comportement utilisateur (fidélisation, récurrence)
- Interactions avancées (copie texte, zoom, etc.)

**Phase 3 - Amélioration :**
- Événements de désengagement
- Métriques avancées de navigation
- Mode hors ligne

---

## 📋 Tableau Synthétique des Problèmes et Manques

### 🚨 Problèmes Critiques à Résoudre

| Priorité | Problème | Impact | Solution |
|----------|----------|---------|----------|
| **URGENT** | 18 triggers orphelins | Pollution de la configuration | Nettoyer et supprimer |
| **URGENT** | Dossier Sandbox en production | Risque de déploiement accidentel | Déplacer en environnement de test |
| **ÉLEVÉ** | Variables en double | Confusion et maintenance | Consolider en variables uniques |
| **ÉLEVÉ** | Conventions de nommage incohérentes | Difficulté de maintenance | Standardiser (TAG_, TRG_, VAR_) |

### ❌ KPI Non Trackés par Catégorie

| Catégorie | KPI Manquants | % Couverture | Priorité d'implémentation |
|-----------|----------------|---------------|---------------------------|
| **Performances Techniques** | 7/7 (0%) | 0% | 🔴 **CRITIQUE** |
| **Comportement & Fidélisation** | 6/6 (0%) | 0% | 🔴 **CRITIQUE** |
| **Événements de Désengagement** | 5/5 (0%) | 0% | 🟠 **ÉLEVÉE** |
| **Engagement & Navigation** | 6/8 (75%) | 25% | 🟠 **ÉLEVÉE** |
| **Interactions** | 9/13 (69%) | 31% | 🟡 **MOYENNE** |
| **Formulaires & Conversion** | 4/5 (80%) | 20% | 🟡 **MOYENNE** |
| **Trafic & Sessions** | 2/6 (67%) | 67% | 🟢 **FAIBLE** |
| **Accessibilité & Multi-Appareil** | 1/6 (83%) | 83% | 🟢 **FAIBLE** |

### 🔧 Éléments Techniques Manquants

| Type | Élément | Description | Impact |
|-------|---------|-------------|---------|
| **Triggers** | Erreurs 404 | Détection des pages non trouvées | 🔴 Perte de données d'erreur |
| **Triggers** | Vidéos YouTube | Tracking des visionnages | 🟠 Pas de suivi vidéo |
| **Variables** | Paramètres personnalisés | Enrichissement des événements | 🟡 Données limitées |
| **Tags** | Performance Web Vitals | FCP, LCP, INP | 🔴 Pas de métriques Core Web Vitals |
| **Tags** | Erreurs JavaScript | Détection des bugs | 🟠 Pas de monitoring technique |

### 📊 Métriques de Conversion Manquantes

| Métrique | Statut | Impact Business | Priorité |
|----------|--------|-----------------|----------|
| Abandon de formulaire | ❌ Non tracké | 🔴 Perte d'opportunités | **URGENT** |
| Temps passé sur formulaire | ❌ Non tracké | 🟠 UX non optimisée | **ÉLEVÉE** |
| Taux de conversion par étape | ❌ Non tracké | 🔴 Funnel non analysé | **URGENT** |
| Nombre de corrections dans un champ | ❌ Non tracké | 🟡 Problèmes UX non détectés | **MOYENNE** |
| Sélection d'un champ sans remplissage | ❌ Non tracké | 🟡 Hésitations utilisateur | **MOYENNE** |

### 🎯 Plan d'Action Prioritaire

#### **Semaine 1-2 : Nettoyage Critique**
- [ ] Supprimer les 18 triggers orphelins
- [ ] Déplacer le dossier Sandbox hors production
- [ ] Consolider les variables en double
- [ ] Standardiser les conventions de nommage

#### **Semaine 3-4 : Implémentation Prioritaire**
- [ ] Réactiver le tracking des erreurs 404
- [ ] Implémenter le tracking des vidéos YouTube
- [ ] Ajouter l'abandon de formulaire
- [ ] Mesurer le temps passé sur formulaire

#### **Semaine 5-6 : Métriques de Performance**
- [ ] Implémenter Core Web Vitals (FCP, LCP, INP)
- [ ] Ajouter le tracking des erreurs JavaScript
- [ ] Mesurer le temps de chargement global
- [ ] Suivre l'utilisation du cache

#### **Semaine 7-8 : Comportement Utilisateur**
- [ ] Taux de visiteurs récurrents
- [ ] Temps avant première interaction
- [ ] Nombre de visites avant conversion
- [ ] Engagement utilisateur par heure

### 📈 Impact Attendu

| Métrique | Avant | Après | Amélioration |
|----------|-------|-------|--------------|
| **Couverture KPI** | 23.5% | 85% | +261% |
| **Triggers actifs** | 14/32 | 28/28 | +100% |
| **Métriques de conversion** | 1/5 | 5/5 | +400% |
| **Performance technique** | 0/7 | 7/7 | +∞% |
| **Comportement utilisateur** | 0/6 | 6/6 | +∞% |

---

*Source : Document original "NAQ - KPI GTM" et analyse GTM-PHJ5HG*

## Comparaison KPI Projetés vs Existants

### Vue d'ensemble

**Total KPI projetés :** 51  
**KPI déjà trackés :** 12 (23.5%)  
**KPI non trackés :** 39 (76.5%)

### Tableau de comparaison détaillé

| Catégorie | KPI | Statut | Implémentation |
|-----------|-----|--------|----------------|
| **Trafic & Sessions** | Sessions | ✅ Tracké | GA4 natif |
| | Utilisateurs uniques | ✅ Tracké | GA4 natif |
| | Taux de rebond | ✅ Tracké | GA4 natif |
| | Durée moyenne de session | ✅ Tracké | GA4 natif |
| | Fréquence de visite | ❌ Non tracké | À implémenter |
| | Nouvelles visites | ❌ Non tracké | À implémenter |
| **Engagement & Navigation** | Pages vues | ✅ Tracké | GA4 natif |
| | Profondeur de visite | ❌ Non tracké | À implémenter |
| | Temps passé sur page | ❌ Non tracké | À implémenter |
| | Scroll Depth (profondeur de scroll) | ✅ Tracké | TAG_GA4_SCROLL_DEPTH |
| | Taux de retour arrière (back) | ❌ Non tracké | À implémenter |
| | Sorties par page | ❌ Non tracké | À implémenter |
| | Pages d'entrée | ❌ Non tracké | À implémenter |
| | Chemin de navigation | ❌ Non tracké | À implémenter |
| **Interactions** | Clics sur CTA | ✅ Tracké | TAG_GA4_NAVIGATION_ANALYSIS |
| | Taux de clic interne | ❌ Non tracké | À implémenter |
| | Clics sur liens sortants | ❌ Non tracké | À implémenter |
| | Vidéos visionnées | ❌ Non tracké | Trigger orphelin TRG_YOUTUBE_TRACKING_GTM2 |
| | Temps passé sur vidéo | ❌ Non tracké | À implémenter |
| | Téléchargements | ✅ Tracké | TAG_GA4_FILE_DOWNLOAD |
| | Copie de texte | ❌ Non tracké | À implémenter |
| | Interactions avec chat | ✅ Tracké | TAG_GA4_CHATBOT_INTERACTION |
| | Activation du mode sombre | ❌ Non tracké | À implémenter |
| | Changement de langue | ❌ Non tracké | À implémenter |
| | Ajustement du zoom | ❌ Non tracké | À implémenter |
| | Écriture dans les champs de formulaire | ❌ Non tracké | À implémenter |
| | Sélections de texte | ❌ Non tracké | À implémenter |
| **Formulaires & Conversion** | Formulaires soumis | ✅ Tracké | TAG_SEO_GA4_FORMULAIRE_CONTACT, TAG_SEO_GA4_AIDES_FORM |
| | Abandon de formulaire | ❌ Non tracké | À implémenter |
| | Temps passé sur formulaire | ❌ Non tracké | À implémenter |
| | Nombre de corrections dans un champ | ❌ Non tracké | À implémenter |
| | Sélection d'un champ sans remplissage | ❌ Non tracké | À implémenter |
| **Performances Techniques** | Temps de chargement global | ❌ Non tracké | À implémenter |
| | First Contentful Paint (FCP) | ❌ Non tracké | À implémenter |
| | Largest Contentful Paint (LCP) | ❌ Non tracké | À implémenter |
| | Interaction to Next Paint (INP) | ❌ Non tracké | À implémenter |
| | Erreurs 404 | ❌ Non tracké | Trigger orphelin TRG_ERREUR_404 |
| | Temps d'exécution des scripts | ❌ Non tracké | À implémenter |
| | Utilisation du cache | ❌ Non tracké | À implémenter |
| **Accessibilité & Multi-Appareil** | Type d'appareil utilisé | ✅ Tracké | GA4 natif |
| | Orientation de l'écran | ✅ Tracké | GA4 natif |
| | Système d'exploitation | ✅ Tracké | GA4 natif |
| | Navigateur utilisé | ✅ Tracké | GA4 natif |
| | Taille de l'écran | ✅ Tracké | GA4 natif |
| | Mode hors ligne | ❌ Non tracké | À implémenter |
| **Comportement & Fidélisation** | Taux de visiteurs récurrents | ❌ Non tracké | À implémenter |
| | Temps avant première interaction | ❌ Non tracké | À implémenter |
| | Nombre de visites avant conversion | ❌ Non tracké | À implémenter |
| | Engagement utilisateur par heure | ❌ Non tracké | À implémenter |
| | Taux de mise en favori | ❌ Non tracké | À implémenter |
| | Taux de partage social | ❌ Non tracké | À implémenter |
| **Événements de Désengagement** | Rage Clicks (clics répétés au même endroit) | ❌ Non tracké | À implémenter |
| | Sélections répétées | ❌ Non tracké | À implémenter |
| | Taux d'interruptions | ❌ Non tracké | À implémenter |
| | Temps avant sortie | ❌ Non tracké | À implémenter |
| | Scroll-up rapide | ❌ Non tracké | À implémenter |

### Résumé par catégorie

| Catégorie | Total KPI | Trackés | Non trackés | % Trackés |
|-----------|-----------|---------|-------------|-----------|
| **Trafic & Sessions** | 6 | 4 | 2 | 66.7% |
| **Engagement & Navigation** | 8 | 2 | 6 | 25.0% |
| **Interactions** | 13 | 4 | 9 | 30.8% |
| **Formulaires & Conversion** | 5 | 1 | 4 | 20.0% |
| **Performances Techniques** | 7 | 0 | 7 | 0.0% |
| **Accessibilité & Multi-Appareil** | 6 | 5 | 1 | 83.3% |
| **Comportement & Fidélisation** | 6 | 0 | 6 | 0.0% |
| **Événements de Désengagement** | 5 | 0 | 5 | 0.0% |

### Recommandations d'optimisation

#### 🧹 Nettoyage prioritaire
- **Supprimer immédiatement :** Les 3 triggers téléphone dans le dossier Sandbox
- **Consolider :** Les triggers de scroll (69, 71) avec le nouveau trigger 132
- **Vérifier :** Les triggers de formulaire contact (47, 97) - garder le plus récent
- **Nettoyer :** Les triggers YouTube et téléchargement obsolètes

#### 📊 Amélioration du tracking
- Standardiser les noms d'événements GA4
- Ajouter des paramètres personnalisés pour enrichir les données
- Implémenter le tracking des erreurs JavaScript

#### 🔧 Optimisation technique
- Utiliser des variables personnalisées pour les valeurs répétées
- Standardiser la convention de nommage
- Ajouter des commentaires dans les configurations

#### 📈 Alignement avec les KPI
- Vérifier que tous les KPI identifiés dans le tableau sont trackés
- Ajouter les métriques manquantes (temps passé sur vidéo, etc.)
- Implémenter le tracking des événements de désengagement

#### 🎯 Priorités d'implémentation

**Phase 1 - Critique :**
- Erreurs 404 (trigger orphelin à réactiver)
- Vidéos visionnées (trigger orphelin à réactiver)
- Abandon de formulaire
- Temps passé sur formulaire

**Phase 2 - Important :**
- Performances techniques (FCP, LCP, INP)
- Comportement utilisateur (fidélisation, récurrence)
- Interactions avancées (copie texte, zoom, etc.)

**Phase 3 - Amélioration :**
- Événements de désengagement
- Métriques avancées de navigation
- Mode hors ligne

---

*Source : Document original "NAQ - KPI GTM" et analyse GTM-PHJ5HG* 
