# 🎮 G*BOY Audio Analyzer

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://opensource.org/)
[![Made for NeukoAI](https://img.shields.io/badge/Made%20for-NeukoAI%20Community-orange.svg)](https://github.com)

> **Outil d'analyse audio et de détection de stéganographie pour les puzzles ARG Web3 de G*BOY par NeukoAI**

![G*BOY Audio Analyzer](https://img.shields.io/badge/Status-Active-success)
![Version](https://img.shields.io/badge/Version-1.0-blue)

## 🔍 Description

G*BOY Audio Analyzer est un outil open-source conçu spécifiquement pour la communauté **NeukoAI** et leurs puzzles **ARG (Alternate Reality Game)** Web3. Cet analyseur permet de détecter des messages, images et données cachées dans les fichiers audio et vidéo.

### ✨ Pourquoi cet outil ?

Les créateurs d'ARG comme NeukoAI dissimulent souvent des indices dans les spectrogrammes audio, utilisent la stéganographie LSB, ou encodent des messages via SSTV/Morse. Cet outil centralise toutes les techniques d'analyse nécessaires dans une interface rétro inspirée des années 80.

## 🚀 Démo en ligne

**👉 [Essayez l'outil ici](https://eNudimmud.github.io/gboy-audio-analyzer/)**

## 🎯 Fonctionnalités

### 📊 Modules d'analyse

| Module | Description |
|--------|-------------|
| **🌈 SPECTROGRAM** | Visualise les images et textes cachés dans le spectre de fréquences |
| **〰️ WAVEFORM** | Analyse détaillée de la forme d'onde pour détecter des patterns anormaux |
| **📈 FREQUENCY** | Analyse spectrale avec détection des pics de fréquence suspects |
| **🔐 STEGANOGRAPHY** | Détection LSB, analyse du bruit de fond, patterns SSTV/Morse |
| **📝 METADATA** | Extraction des métadonnées cachées dans les fichiers |
| **🎵 AUDIO EFFECTS** | Inversion, ralenti/accéléré pour révéler des messages cachés |

### 🎨 Interface

- **Design rétro années 80/Atari** avec effet CRT authentique
- **Phosphore vert** style terminal classique
- **Scanlines animées** pour une immersion totale
- **Police VT323 et Press Start 2P** pour l'authenticité
- **Effets de scintillement** CRT réalistes

## 📦 Installation

### Option 1 : Utilisation en ligne (recommandé)
Accédez simplement à l'URL de démo ci-dessus. Aucune installation nécessaire !

### Option 2 : Utilisation locale
1. Téléchargez le fichier `index.html`
2. Double-cliquez dessus pour l'ouvrir dans votre navigateur
3. C'est tout ! L'outil fonctionne 100% en local

### Option 3 : Clone du dépôt
```bash
git clone https://github.com/eNudimmud/gboy-audio-analyzer.git
cd gboy-audio-analyzer
# Ouvrez index.html dans votre navigateur
```

## 🎮 Guide d'utilisation

### Étape 1 : Charger un fichier
- Glissez-déposez un fichier audio/vidéo dans la zone de drop
- Ou cliquez sur "SELECT FILE" pour parcourir vos fichiers
- Formats supportés : MP3, WAV, OGG, MP4, WEBM, AVI

### Étape 2 : Choisir un module d'analyse
- Naviguez entre les onglets (SPECTROGRAM, WAVEFORM, etc.)
- Cliquez sur les boutons d'analyse selon vos besoins

### Étape 3 : Interpréter les résultats
- **Spectrogram** : Cherchez des patterns visuels, du texte ou des images
- **LSB Analysis** : Un ratio de bits anormal peut indiquer des données cachées
- **Frequency** : Des pics de fréquence inhabituels peuvent être des signaux encodés
- **Reverse** : Les messages peuvent être cachés à l'envers

## 🔧 Techniques de détection

### Stéganographie LSB (Least Significant Bit)
L'outil analyse les bits de poids faible des échantillons audio pour détecter des patterns non aléatoires indiquant des données cachées.

### Analyse spectrogramme
Convertit l'audio en représentation visuelle fréquence/temps. Les créateurs d'ARG cachent souvent des images ou du texte visible uniquement en vue spectrale.

### Détection SSTV (Slow Scan Television)
Recherche les patterns de fréquence caractéristiques des transmissions SSTV (images encodées en audio).

### Analyse du bruit de fond
Un niveau de bruit inhabituellement élevé peut indiquer la présence de données stéganographiques.

### Audio inversé
Certains messages sont simplement enregistrés à l'envers. L'outil permet de les révéler instantanément.

## 🛠️ Technologies utilisées

- **HTML5** - Structure
- **CSS3** - Design rétro avec effets CRT
- **JavaScript Vanilla** - Logique d'analyse
- **Web Audio API** - Traitement audio en temps réel
- **Canvas API** - Visualisations graphiques

**Aucune dépendance externe !** Tout fonctionne nativement dans le navigateur.

## 🔒 Confidentialité

- ✅ **100% client-side** - Tout le traitement se fait dans votre navigateur
- ✅ **Aucune donnée envoyée** - Vos fichiers ne quittent jamais votre ordinateur
- ✅ **Pas de tracking** - Aucun analytics ou cookie
- ✅ **Open source** - Code entièrement auditable

## 🤝 Contribution

Les contributions sont les bienvenues ! Ce projet est fait pour la communauté.

### Comment contribuer ?

1. **Fork** le projet
2. Créez une branche pour votre feature (`git checkout -b feature/AmazingFeature`)
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une **Pull Request**

### Idées de contributions

- [ ] Ajout de décodeurs SSTV automatiques
- [ ] Détection de codes Morse automatisée
- [ ] Export des résultats en JSON
- [ ] Support de formats audio exotiques
- [ ] Thèmes alternatifs (Phosphore ambre, vert, etc.)
- [ ] Analyse par IA des patterns suspects
- [ ] Mode batch pour analyser plusieurs fichiers

## 📜 Licence

Ce projet est sous licence **MIT** - voir le fichier [LICENSE](LICENSE) pour plus de détails.

Vous êtes libre de :
- ✅ Utiliser commercialement
- ✅ Modifier
- ✅ Distribuer
- ✅ Utiliser en privé

## 🎖️ Crédits

### Créé pour la communauté
- **NeukoAI** - Créateurs du projet G*BOY
- **Communauté ARG Web3** - Pour qui cet outil a été conçu

### Polices utilisées
- [VT323](https://fonts.google.com/specimen/VT323) - Fonte terminal par Peter Hull
- [Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P) - Police rétro gaming

## 🌟 Remerciements

Un grand merci à :
- La communauté **NeukoAI** pour l'inspiration
- Tous les puzzle solvers et chasseurs d'ARG
- Les contributeurs open-source

## 📞 Support & Contact

- **Issues** : [GitHub Issues](https://github.com/eNudimmud/gboy-audio-analyzer/issues)
- **Discussions** : [GitHub Discussions](https://github.com/eNudimmud/gboy-audio-analyzer/discussions)
- **Community** : Rejoignez la communauté NeukoAI/G*BOY

## 🔮 Roadmap

### Version 1.1 (À venir)
- [ ] Décodeur SSTV intégré
- [ ] Détection automatique de Morse
- [ ] Export des spectrogrammes en haute résolution
- [ ] Mode sombre/clair (en plus du mode CRT)

### Version 2.0 (Futur)
- [ ] Analyse par IA des patterns
- [ ] Support de l'analyse en temps réel (streaming)
- [ ] Mode collaboratif multi-utilisateurs
- [ ] Base de données de signatures connues

## 📊 Statistiques

![GitHub stars](https://img.shields.io/github/stars/eNudimmud/gboy-audio-analyzer?style=social)
![GitHub forks](https://img.shields.io/github/forks/eNudimmud/gboy-audio-analyzer?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/eNudimmud/gboy-audio-analyzer?style=social)

---

<div align="center">

**Fait avec ❤️ pour la communauté NeukoAI/G*BOY**

[⭐ Star ce projet](https://github.com/eNudimmud/gboy-audio-analyzer) | [🐛 Reporter un bug](https://github.com/eNudimmud/gboy-audio-analyzer/issues) | [💡 Suggérer une feature](https://github.com/eNudimmud/gboy-audio-analyzer/issues)

</div>

---

## 🎯 Quick Start

```bash
# Clone
git clone https://github.com/eNudimmud/gboy-audio-analyzer.git

# Navigate
cd gboy-audio-analyzer

# Open
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

**C'est parti pour la chasse aux secrets ! 🕵️‍♂️🔍**
