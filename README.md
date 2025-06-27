# 🧪 Exercice technique

> Fork ce repository avant de commencer l'exercice. Ce sera la base de ton projet.

## 🎯 Objectif  
Dans une application **React Native (v0.80.0)**, tu dois créer une **Live Activity iOS** affichant une progression en temps réel vers un objectif de pas défini côté React Native.

---

## 🛠 Ce que tu dois faire

### Côté React Native
- Crée un **formulaire** permettant à l'utilisateur de :
  - Définir un **objectif de pas**
  - Lancer la Live Activity
- Une fois l'objectif soumis, envoie la valeur au **natif**
- Tu es libre pour le design du form, mais on valorise un rendu propre et clair
- **Évite dans la mesure du possible d'ajouter des dépendances externes**

### Côté iOS
- Implémente une **Live Activity**
- Cette Live Activity doit afficher :
  - Le **nombre de pas effectués aujourd'hui**
  - Une **gauge de progression** (% vers l'objectif défini)
- Le **nombre de pas doit refléter une donnée réelle**, récupérée depuis le device (via CMPedometer, HealthKit, etc.)
- L'UI est libre tant que l'expérience est fluide et soignée

---

## 💪 Bon courage !

N'hésite pas à être créatif et à montrer tes talents ! Amuse-toi bien ! 🚀