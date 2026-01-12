# Dashboard Node-RED pour Station Météo ESP32

## 📊 Aperçu
Dashboard complet pour visualiser le monitoring de température et d’humidité, couplé à un contrôle interactif de périphériques (LED, servomoteur, bande Neopixel.

## 🚀 Installation Rapide

### Prérequis
- Node.js 14+ et npm
- Node-RED (`npm install -g node-red`)

### Installation

# 1. Cloner le repository
```bash
git clone https://github.com/zikoelj/esp32-dashboard.git
```
# 2. Se déplacer dans le dossier
```bash
cd esp32-dashboard
```
# 3. Installer les dépendances
```bash
npm install
```
# 4. Lancer Node-RED avec ce dashboard
```bash
npm start
```
# 5. Accès
**Éditeur Node-RED :**
```bash
 http://localhost:1880
``` 
**Interface Dashboard :**
```bash
http://localhost:1880/ui
``` 

## Problème : "Cannot GET /ui"
- Solution : Vérifiez que node-red-dashboard est installé
```bash
npm install node-red-dashboard
``` 

