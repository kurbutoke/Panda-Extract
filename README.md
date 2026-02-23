<div align="center">

# 🐼 Panda Extract — Ultimate Web Scraper

**Version améliorée & déverrouillée de l'extension [Ultimate Web Scraper](https://ultimatewebscraper.com/) (anciennement PandaExtract)**

> Extrayez instantanément du texte, des images, des emails et des liens depuis n'importe quel site web, en un seul clic.

![Chrome](https://img.shields.io/badge/Chrome-Compatible-4285F4?logo=googlechrome&logoColor=white)
![Edge](https://img.shields.io/badge/Edge-Compatible-0078D7?logo=microsoftedge&logoColor=white)
![Brave](https://img.shields.io/badge/Brave-Compatible-FB542B?logo=brave&logoColor=white)
![Manifest V3](https://img.shields.io/badge/Manifest-V3-00C853)
![Version](https://img.shields.io/badge/Version-5.9.3-blue)

</div>

---

## 📖 Description

**Panda Extract** est une version améliorée et complète de l'extension Chrome **Ultimate Web Scraper** (ex-PandaExtract). Elle embarque **toutes les fonctionnalités premium** de l'extension originale, sans aucune restriction, directement utilisable en local.

Cette extension permet d'extraire des données structurées depuis n'importe quel site web — listes, tableaux, emails, images, texte — sans écrire une seule ligne de code.

---

## 🚀 Fonctionnalités

### 📋 Extraction de listes (List Extractor)
Outil de sélection intelligent pour extraire des données structurées à partir de listes, tableaux et contenus paginés.
- **Hover** → Survolez n'importe quelle liste ou tableau pour mettre en surbrillance les éléments extractibles
- **Click** → Cliquez sur la zone sélectionnée pour lancer l'extraction
- **Export** → Téléchargez vos données en CSV, Excel ou autres formats

### 📄 Extraction de pages (Web Page Extractor)
Extraction en masse de données spécifiques à partir d'une collection de pages.
- Ajoutez les URLs de pages similaires
- Sélectionnez les éléments à extraire (texte, image, lien)
- Extraction automatique sur toutes les pages fournies

### 📧 Extraction d'emails (Email Extractor)
Scan automatique de sites web pour détecter et collecter les adresses email.
- Upload d'un CSV avec des URLs à scanner
- **Deep Scanning** — Analyse automatique des pages et sous-pages
- Export en masse depuis des centaines de sites

### 🖼️ Téléchargement d'images (Image Downloader)
Détection intelligente et téléchargement en masse des images d'un site.
- Détection automatique et tri par taille/type
- Sélection individuelle ou par catégorie
- Téléchargement groupé en un clic

### 📝 Extraction de texte (Page Text Extractor)
Extraction de texte propre et de métadonnées depuis des pages web.
- Upload d'un CSV de pages à analyser
- Extraction automatique du contenu textuel et des métadonnées
- Export structuré avec métadonnées associées

### 📊 Data Table (Tableur intégré)
Interface tableur puissante pour gérer et organiser toutes vos données extraites.
- Filtrage avancé et recherche
- Édition de cellules, fusion de colonnes, réorganisation
- Export vers CSV, Excel, Google Sheets ou presse-papier

---

## 🎯 Cas d'utilisation populaires

| Plateforme | Données extractibles |
|---|---|
| **Google Maps** | Leads, adresses, téléphones, avis |
| **Amazon** | Produits, prix, images, descriptions |
| **Trustpilot** | Avis, notes, noms, pays |
| **Twitter/X** | Tweets, followers, likes, retweets |
| **Airbnb** | Annonces, prix, localisations, notes |
| **Shopify** | Produits, prix, images, descriptions |
| **Zillow** | Annonces immobilières, prix, localisations |
| **Etsy** | Produits, prix, images, descriptions |
| **Yelp** | Avis, commerces, coordonnées |
| **Instagram** | Images, profils |

---

## 🛠️ Installation

### Méthode — Chargement en mode développeur

1. Ouvrez votre navigateur (Chrome, Edge ou Brave)
2. Accédez à la page des extensions :
   - **Chrome** : `chrome://extensions/`
   - **Edge** : `edge://extensions/`
   - **Brave** : `brave://extensions/`
3. Activez le **Mode développeur** (toggle en haut à droite)
4. Cliquez sur **« Charger l'extension non empaquetée »**
5. Sélectionnez le dossier `Panda Extract - Ultimate Web Scrapper`
6. L'extension est prête à l'emploi ✅

---

## 📂 Structure du projet

```
Panda Extract - Ultimate Web Scrapper/
├── manifest.json                        # Configuration Manifest V3
├── background.bundle.js                 # Service Worker (logique en arrière-plan)
├── content.bundle.js                    # Script de contenu (injection dans les pages)
├── sidepanel.html                       # Interface du panneau latéral
├── sidepanel.bundle.js                  # Logique du panneau latéral (React)
├── pageElementPicker.bundle.js          # Sélecteur d'éléments sur la page
├── 281.bundle.js                        # Module complémentaire (chunk)
├── _locales/                            # Traductions (47 langues)
│   └── en/messages.json                 # Messages anglais
└── public/                              # Assets (icônes, logos, SVG navigateurs)
    ├── icon.png
    ├── logo-*.png
    ├── chrome.svg / edge.svg / brave.svg
    └── ...
```

---

## 🌍 Langues supportées

L'extension est disponible en **47 langues** grâce au système de localisation intégré (`_locales/`).

---

## ⚙️ Stack technique

| Composant | Technologie |
|---|---|
| **Manifest** | Chrome Extensions Manifest V3 |
| **UI** | React (panneau latéral) |
| **Background** | Service Worker (module ES) |
| **Permissions** | `activeTab`, `scripting`, `storage`, `sidePanel` |
| **Permissions optionnelles** | `downloads`, `clipboardWrite`, `<all_urls>` |

---

## ⚠️ Avertissement

Ce projet est fourni **à des fins éducatives et de recherche uniquement**. L'utilisation de web scraping doit respecter les conditions d'utilisation des sites web ciblés ainsi que les lois en vigueur (RGPD, CCPA, etc.). L'auteur décline toute responsabilité en cas d'utilisation abusive.

---

<div align="center">

**Panda Extract — Ultimate Web Scraper** 🐼

*Extrayez tout, de n'importe où, sans limite.*

</div>
