# catia-scan-to-solid-dm

# Reconstruction de surfaces à partir de scans 3D

## Contexte

Ce devoir a pour objectif d’évaluer votre capacité à **reconstruire un modèle solide à partir de données de scan 3D** en utilisant **CATIA**.

Vous disposerez de deux nuages de points fournis au format ASCII :

- **`objet1.asc`** : scan d’une **portière de voiture**
- **`objet2.asc`** : scan d’un **objet mécanique**

L’objectif est d’appliquer les méthodes vues lors des **trois travaux pratiques précédents** afin de transformer un nuage de points brut en :

1. un **modèle surfacique cohérent**
2. un **modèle solide final**

La reconstruction doit être réalisée à l’aide des modules CATIA :

- **DSE — Digitized Shape Editor**
- **QSR — Quick Surface Reconstruction**

La création finale du solide doit être réalisée dans :

- **Part Design**

---

# Données fournies

Deux fichiers de scan sont fournis :

| Fichier | Description |
|------|-------------|
| `objet1.asc` | Scan 3D d’une **portière de voiture** |
| `objet2.asc` | Scan 3D d’un **objet mécanique** |

Ces fichiers contiennent des **nuages de points issus d’un système de numérisation 3D**.

---

# Objectif

Le but est de **reconstruire un modèle CAO solide** à partir du nuage de points en suivant les étapes suivantes :

1. Nettoyer le nuage de points si nécessaire  
2. Identifier les surfaces géométriques principales  
3. Reconstruire les surfaces canoniques  
4. Définir les intersections entre les surfaces (limites du solide)  
5. Générer le solide final

Ces étapes doivent être réalisées en appliquant les méthodes vues lors des TP.

---

# Critères d’évaluation

L’évaluation sera réalisée selon les critères suivants :

| Étape | Description | Points |
|------|-------------|------|
| **1** | Filtrage du nuage de points (si nécessaire) | 2 |
| **2** | Suppression de points parasites (si nécessaire) | 1 |
| **3** | Reconnaissance des **surfaces canoniques** (plans, cylindres, etc.) | 10 |
| **4** | Définition des **intersections entre les surfaces** (limites du solide) | 5 |
| **5** | Création du **solide final dans Part Design** | 2 |

**Total : 20 points**

---

# Contraintes méthodologiques

Les étapes **1 à 4 doivent être réalisées exclusivement avec :**

- **DSE (Digitized Shape Editor)**
- **QSR (Quick Surface Reconstruction)**

La création du solide final doit être réalisée dans :

- **Part Design**

---

# Livrables attendus

Vous devrez rendre :

- le **projet CATIA complet**
- le **modèle surfacique reconstruit**
- le **modèle solide final**

Le modèle doit être :

- géométriquement cohérent  
- correctement limité (trim)  
- sans points parasites inutiles

---

# Conseils

- Commencez par **observer le nuage de points**
- Identifiez les **surfaces dominantes**
- Ajustez les surfaces progressivement
- Vérifiez les **intersections entre surfaces**
- Assurez-vous que le modèle forme **un volume fermé avant la création du solide**
