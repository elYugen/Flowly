# 📌 Flowly  

**Flowly** est une application moderne et intuitive qui combine :  
- ✅ Une **todolist intelligente** pour mieux organiser ses tâches.  
- 💰 Une **gestion simplifiée des finances personnelles**.  
- 🗂️ La possibilité de créer des **catégories personnalisées** pour adapter la todo à ton mode de vie.  


---

## 🚀 Fonctionnalités principales  

### ✅ Gestion des tâches (Todo)  
- Création, édition et suppression de tâches.  
- Marquer une tâche comme terminée ou en cours.  
- Attribution d’échéances (deadlines).  
- Catégorisation personnalisée des tâches (ex. *Vidéo*, *À faire*, *Travail*, *Santé*, etc.).  

### 🗂️ Catégories personnalisées  
- Chaque utilisateur peut créer ses propres catégories.  
- Exemple :  
  - **Catégorie Vidéo** : tourner une vidéo, monter une vidéo.  
  - **Catégorie À faire** : changer la couche du bébé, acheter du pain.  
  - **Catégorie Sport** : séance de muscu, marche 30 min.  

### 💰 Gestion financière  
- Suivi de ses revenus et dépenses.  
- Visualisation du solde disponible.  
- Classement des transactions par catégories (*loyer*, *alimentation*, *abonnements*, etc.).  
- Objectifs financiers (ex. épargner 200€/mois).  

### 📊 Visualisation & statistiques *(futur ajout)*  
- Graphiques pour analyser ses dépenses.  
- Progression des objectifs (perso & financiers).  

---

## 🛠️ Stack technique (prévisionnelle)  

- **Backend Frontend** : Laravel 12  
- **Base de données** : MySQL 

---

## 📱 Exemple d’utilisation  

1. **Organisation quotidienne**  
   - Je crée une catégorie *Maison*  
   - J’ajoute les tâches : "Changer la couche du bébé", "Faire la vaisselle"  

2. **Suivi financier**  
   - J’ajoute mes revenus : salaire, freelance  
   - J’ajoute mes dépenses : courses, abonnements, loisirs  
   - Flowly me montre mon solde et mes objectifs  

---

## 🧑‍💻 Installation (dev)  

```bash
# Cloner le projet
git clone https://github.com/tonpseudo/flowly.git

# Backend Laravel
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve

# Frontend React Native
cd ../frontend
npm install
npm run start
