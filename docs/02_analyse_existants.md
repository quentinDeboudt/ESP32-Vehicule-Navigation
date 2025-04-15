# Existe-t-il un projet équivalent ?

## 1. Projet : ESP32 + Sygic

Ce projet utilise une application mobile pour envoyer les instructions de navigation à l'ESP32 via **Bluetooth Low Energy (BLE)**.

- **Le téléphone** joue le rôle de **BLE Central** (aussi appelé *client* ou *maître*).
- **L'ESP32** agit comme un **périphérique BLE** (aussi appelé *serveur* ou *esclave*).

🔗 **GitHub du projet :** [BLE-HUD-navigation-ESP32](https://github.com/alexanderlavrushko/BLE-HUD-navigation-ESP32/blob/main/README.md)

🎥 **Vidéo de démonstration :** [YouTube - Chronos ESP32](https://www.youtube.com/watch?v=LHUQlj09ZNA&ab_channel=Sygica.s.)

>⚠️ <span style="color:rgb(255, 0, 0)">**Limite actuelle :** </span>
>Ce projet n’est compatible qu’avec l’application **Sygic GPS Navigation & Maps**, disponible uniquement sur **iOS**.

---

## 2. Projet : ESP32 (Montre) + Chronos App

Ce projet repose sur une **montre ESP32** qui communique avec l’application **Chronos App** via **BLE**. L’application permet de contrôler plusieurs fonctions de la montre.

### Fonctionnalités principales :

- Synchronisation de **l’heure**
- Réception de **notifications** et alertes d’**appel**
- Synchronisation de la **météo**
- Transmission de liens QR et de **contacts**
- Contrôle de la **musique**, de l’appareil **photo**, et fonction **"recherche du téléphone"**
- **Envoi des instructions de navigation**

🔗 **GitHub du projet :** [Chronos ESP32](https://github.com/fbiego/esp32-c3-mini)  
🎥 **Vidéo de démonstration :** [YouTube - Chronos ESP32](https://www.youtube.com/watch?v=qGODX6ALO_U&t=9s&ab_channel=fbiego)

>⚠️ <span style="color:rgb(255, 0, 0)">**Remarque importante :** </span>
>Ce projet offre un grand nombre de fonctionnalités, mais cela peut entraîner une **surcharge du système**, affectant les **performances** et réduisant considérablement **l'autonomie de la batterie**.
