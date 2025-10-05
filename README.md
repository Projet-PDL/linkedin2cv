# LinkedIn2CV

## Contexte & Objectif

  La création et la mise à jour d’un CV professionnel peuvent être longues et sujettes à des incohérences, notamment lorsque les informations ne sont pas alignées avec le profil LinkedIn de l’utilisateur.
Le projet **LinkedIn2CV** vise à automatiser ce processus en permettant la génération d’un CV au format PDF à partir des données LinkedIn d’un utilisateur.
  L’objectif est de fournir une application web intuitive et rapide, offrant plusieurs modèles de CV personnalisables et garantissant la cohérence entre les données LinkedIn et le document final.
  
---

## Fonctionnalités du système

Le système **LinkedIn2CV** doit permettre à l’utilisateur de :

1. **Authentification et gestion de profil**
   - Se connecter ou créer un compte utilisateur de manière sécurisée.
   - Insérer le lien de son profil LinkedIn ou importer un fichier d’export LinkedIn (.json).
   - Synchroniser automatiquement les informations de son profil LinkedIn.

2. **Gestion des informations personnelles**
   - Récupérer et afficher les informations personnelles (nom, prénom, photo, contact, titre professionnel).
   - Récupérer et afficher les expériences professionnelles (poste, entreprise, période, description).
   - Récupérer et afficher les formations (établissements, diplômes, dates).
   - Récupérer les compétences, langues, et certifications du profil LinkedIn.

3. **Personnalisation du CV**
   - Modifier ou compléter les informations importées via un formulaire dynamique.
   - Ajouter manuellement de nouvelles expériences, formations ou compétences.
   - Choisir un modèle de CV (template) parmi plusieurs styles disponibles.
   - Personnaliser le design du CV (couleurs, polices, mise en page).
   - Prévisualiser en temps réel le rendu du CV avant la génération finale.

4. **Génération et gestion des CV**
   - Générer automatiquement un CV au format PDF à partir des informations saisies.
   - Télécharger ou imprimer le CV généré.
   - Sauvegarder plusieurs CV dans le compte utilisateur.
   - Mettre à jour un CV existant lorsque les données LinkedIn changent.

5. **Consultation et historique**
   - Accéder à la liste de tous les CV déjà créés.
   - Visualiser, modifier ou supprimer un CV existant.
   - Consulter la date de création et de dernière mise à jour de chaque CV.

6. **Administration et maintenance**
   - Ajouter ou mettre à jour les templates de CV par les administrateurs.
   - Vérifier automatiquement la cohérence des données importées.
   - Gérer les erreurs de parsing ou d’import (fichier invalide, données manquantes, etc.).

---

##  Fonctionnalités futures
-  Mise à jour automatique du CV à chaque changement sur LinkedIn.  
-  Support multi-langues (FR / EN / ES).  
-  Suggestions automatiques d’amélioration de CV basées sur l’IA.  
-  Exportation vers d’autres formats (DOCX, HTML).  
-  Espace cloud personnel pour stocker plusieurs CV.  


---

## Stack technique

| Composant | Technologie |
|------------|--------------|
| **Backend** | FastAPI (Python) |
| **Base de données** | PostgreSQL / SQLite |
| **Frontend** | VueJS + Bootstrap |
| **Génération PDF** | iText5 |
| **Conteneurisation** | Docker / Docker Compose |
| **Contrôle de version** | GitHub |
| **CI/CD** | GitHub Actions |
| **Déploiement** | Google Cloud Platform |
| **Tests** | Pytest, Jest, Postman |

---

## Couverture de tests
- **Tests unitaires** : vérification du parsing JSON, de la validation des données et des conversions PDF.  
- **Tests d’intégration** : vérification du workflow complet (import → affichage → génération PDF).  
- **Tests frontend** : validation des formulaires et de la prévisualisation du CV.  
- **Objectif de couverture** :  
  - 50 % minimum à la première livraison (21 novembre 2025)  
  - 70 % minimum à la version finale (19 décembre 2025)  

---

##  Organisation de l’équipe



---

## Planification (jalons)

### 🔹 24 Octobre 2025
- Prototype fonctionnel 
- Documentation technique initiale

### 🔹 21 Novembre 2025
- Application complète (50%+ de couverture de test)
- Première validation client

### 🔹 19 Décembre 2025
- Version stabilisée et optimisée
- Tests complets et déploiement 

---

