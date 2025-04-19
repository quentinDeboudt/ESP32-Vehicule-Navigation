# Solution envisagée ?

## 1. Projet : Création d'une application mobile + montre ESP32

### Option 1 : Réutilisation d'applications existantes

La solution la plus simple consisterait à réutiliser des applications déjà développées, capables **d’écouter les notifications du téléphone**.  
Cependant, plusieurs limitations rendent cette option peu adaptée :

- Ces applications **ne couvrent pas l'ensemble du besoin initial** (par exemple, la prise en charge simultanée des notifications de **Google Maps** et **Waze**).
- Elles **ne sont pas libres de modification**, ce qui empêche toute personnalisation ou adaptation du code pour répondre aux exigences spécifiques du projet.

### Option 2 : Développement d'une application dédiée (solution retenue)

La solution la plus adaptée consiste à développer une **application Android personnalisée** permettant :

- La récupération des notifications émises par **Google Maps** et **Waze**.
- Le **filtrage et le traitement** des données reçues.
- L’**envoi des données** à la montre **ESP32** via le protocole **BLE** (Bluetooth Low Energy).

Cette approche garantit une **maîtrise totale** du flux de données ainsi qu'une **flexibilité maximale** pour évoluer selon les besoins du projet.
