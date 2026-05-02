# 🛰️ NEXUS REAL ULTIME

<div align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/190/190411.png" width="120" alt="NEXUS Logo">
  <h3>Station de surveillance mondiale en temps réel</h3>
  <p>100% données réelles • 0% simulation</p>
</div>

---

## 🚀 À propos

**NEXUS REAL** est une station de surveillance mondiale ultramoderne qui agrège des données en temps réel provenant de multiples sources officielles :

- ✈️ **Avions** - OpenSky Network (ADS-B)
- 🛸 **Drones** - Détection automatique par altitude/vitesse
- 🛰️ **Satellites** - N2YO API
- 🚢 **Navires** - Trafic maritime (AIS)
- 🔥 **Feux de forêt** - Surveillance environnementale
- 🌡️ **Météo & Qualité air** - Open-Meteo API

## ✨ Fonctionnalités

| Fonctionnalité | Description |
|----------------|-------------|
| 📡 **Radar longue portée** | Jusqu'à 500km de couverture |
| 📈 **Prédictions IA** | Trajectoires à 1h, 2h et 4h |
| 🗺️ **Carte interactive** | Visualisation Leaflet + OpenStreetMap |
| 🤖 **Assistant vocal** | Commandes vocales et IA intégrée |
| 📱 **Application mobile** | Installation PWA possible |
| 🌓 **Thème clair/sombre** | Interface adaptable |
| 📊 **Export données** | CSV et PDF |
| 📸 **Capture d'écran** | Sauvegarde du radar |

## 🎯 Sources de données 100% réelles

| Source | Données | API |
|--------|---------|-----|
| [OpenSky Network](https://opensky-network.org) | Avions / Drones | ADS-B |
| [N2YO](https://www.n2yo.com) | Satellites | Space API |
| [USGS](https://earthquake.usgs.gov) | Séismes | Earthquake API |
| [Open-Meteo](https://open-meteo.com) | Météo / Qualité air | Weather API |

## 🚀 Démo en ligne

👉 [**https://brainbkms.github.io/Nexus_final/**](https://brainbkms.github.io/Nexus_final/)

## 📱 Installation

### Option 1 : En ligne
1. Ouvre le lien ci-dessus dans **Chrome**
2. Autorise la géolocalisation
3. Crée un compte ou connecte-toi avec `admin` / `admin123`

### Option 2 : Application mobile
1. Ouvre le lien dans **Chrome**
2. Menu (3 points) → **"Installer l'application"**
3. L'icône apparaît sur ton écran d'accueil

### Option 3 : Installation locale
```bash
git clone https://github.com/brainbkms/Nexus_final.git
cd Nexus_final
python -m http.server 8000
# Ouvre http://localhost:8000
