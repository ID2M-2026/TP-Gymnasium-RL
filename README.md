# Atelier Gymnasium - Apprentissage par Renforcement

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VOTRE_USERNAME/Gymnasium-RL-Workshop/blob/main/notebooks/Gymnasium_Workshop_French.ipynb)

Atelier pratique d'introduction à l'apprentissage par renforcement (Reinforcement Learning) avec **Gymnasium**, **Q-Learning** et **Deep Q-Learning (DQN)**.

---

## **Contenu du Workshop**

Cet atelier vous apprendra à :
1. Créer un environnement personnalisé avec Gymnasium
2. Implémenter un agent Q-Learning
3. Implémenter un agent Deep Q-Network (DQN)
4. Tester vos agents sur des environnements Gymnasium intégrés (`FrozenLake`, `CartPole`)

---

## **Installation et Configuration**

### **Option 1 : Utiliser Google Colab (Recommandé)**
#### **Étapes :**

1. **Ouvrir le notebook dans Colab :**
   - Cliquez sur le badge ci-dessous pour la version **française** :
   
     [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VOTRE_USERNAME/Gymnasium-RL-Workshop/blob/main/notebooks/Gymnasium_Workshop_French.ipynb)
   
   - Pour la version **anglaise** :
   
     [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VOTRE_USERNAME/Gymnasium-RL-Workshop/blob/main/notebooks/Gymnasium_Workshop_English.ipynb)

2. **Connectez-vous à votre compte Google pas compte Google de classe**

3. **Faire une copie du notebook :**
   - Dans Colab, allez dans : `Fichier` → `Enregistrer une copie dans Drive`
   - Cela crée votre propre version éditable

4. **Exécuter les cellules :**
   - Cliquez sur `▶️` à gauche de chaque cellule pour l'exécuter
   - Ou utilisez `Ctrl+Enter` pour exécuter la cellule actuelle
   - Ou utilisez `Shift+Enter` pour exécuter et passer à la suivante
   - Ou utilisez `Exécution` → `Tout exécuter`

---

### **Option 2 : Installation Locale (Optionnel)**

Si vous préférez travailler en local sur votre machine, utilisez Jupyter.

---

## ⚠️**Important : Préparation Avant le Cours en cas Sans WiFi**⚠️

### **Si vous n'aurez pas de WiFi en classe :**

#### **Méthode 1 : Télécharger les Résultats Pré-calculés**
Les résultats de l'entraînement sont déjà disponibles dans le dossier `outputs/` :
- Télécharger les fichiers Jupyter précalculés disponibles
- Logs des récompenses
- Vous pouvez les consulter même sans exécuter le code

#### **Méthode 2 : Exécuter Tout Avant le Cours (Recommandé)**

1. **Ouvrez le notebook dans Colab** (avec WiFi)
2. **Exécutez TOUTES les cellules** en une fois :
   - Dans Colab : `Exécution` → `Tout exécuter`
   - Cela prendra environ **10-15 minutes**
3. **Attendez que tout soit terminé**
4. **Les résultats resteront affichés** dans le notebook
5. **Google Colab garde les résultats** même en mode hors ligne après exécution

---

## **Structure du Workshop**

### **Partie 1 : Environnement Personnalisé (Cellules 1-6)**
- Installation de Gymnasium
- Création d'un environnement de grille 5×5
- Implémentation des méthodes `reset()`, `step()`, `render()`
- Test avec un agent aléatoire

### **Partie 2 : Q-Learning (Cellules 7-9)**
- Création d'un agent Q-Learning
- Entraînement sur l'environnement personnalisé (1000 épisodes)
- Test de l'agent entraîné

### **Partie 3 : Deep Q-Learning (Cellules 10-14)**
- Architecture de réseau neuronal avec PyTorch
- Buffer de replay d'expérience
- Entraînement DQN (1000 épisodes)
- Comparaison avec Q-Learning

### **Partie 4 : Environnements Gymnasium (Cellules 16-19)**
- Test sur `FrozenLake-v1` avec Q-Learning
- Test sur `CartPole-v1` avec DQN
- **Vous pouvez changer les environnements**

---

## **Résolution de Problèmes**

### **Erreur: "RuntimeError: CUDA out of memory"**
- **Solution** : DQN utilise le CPU par défaut, pas de GPU nécessaire
- Si vous voulez utiliser le GPU dans Colab : `Exécution` → `Modifier le type d'exécution` → `CPU`

### **Les cellules prennent trop de temps**
- L'entraînement Q-Learning prend **~30 secondes**
- L'entraînement DQN prend **~2-6 minutes**
- Si c'est trop long, réduisez `num_episodes` à 500

### **Bugs?**
- Contact "ziededucation@gmail.com" **screenshot** + **copy de fichier jupyter**
  
---

## **Ressources Supplémentaires**

### **Documentation Officielle**
- [Gymnasium Documentation](https://gymnasium.farama.org/)
- [PyTorch Tutorials](https://pytorch.org/tutorials/)
- [Sutton & Barto - RL Book (gratuit)](http://incompleteideas.net/book/RLbook2020.pdf)

### **Articles de Recherche**
- Deep Reinforcement Learning: A Chronological Overview and Methods - Juan Terven
- Reinforcement learning algorithms: A brief survey - Ashish Kumar Shakya, Gopinatha Pillai, Sohom Chakrabarty

### **Playlist Important**
- [Apprentissage par renforcement - Thibault Neveu](https://youtube.com/playlist?list=PLpEPgC7cUJ4YPZlfUu0vQTwPraVKPASUa&si=WS_Yh_-hu-7sQ_g1)

---

## **Auteurs**

**Zied Zaafrani**  
- Email: ziededucation@gmail.com

**Montassar Lemjid**  
- Email: lemjidmontassar@gmail.com
---
