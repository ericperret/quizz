[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Pure HTML/JS](https://img.shields.io/badge/Pure-HTML%2FJS-blue.svg)](#)
[![Educational](https://img.shields.io/badge/Purpose-Educational-orange.svg)](#)

**Tutoriel interactif sur la chaîne de transmission DVB-S** — De l'image JPEG à la modulation QPSK.

![Screenshot](screenshot.png)

## 🚀 Fonctionnalités

Visualisation étape par étape de la chaîne de transmission DVB-S complète :

1. **Capture Caméra** — Acquisition de l'image source
2. **Macroblocs** — Découpage en blocs 8x8
3. **DCT** — Transformée en Cosinus Discrète
4. **Quantification** — Compression avec pertes
5. **Scan Zigzag** — Réordonnancement des coefficients
6. **RLE + Huffman** — Codage entropique
7. **Elementary Stream** — Empaquetage ES vidéo
8. **PES** — Packetized Elementary Stream
9. **Transport Stream** — Multiplexage MPEG-TS
10. **PRBS** — Dispersion d'énergie
11. **Reed-Solomon** — Codage externe FEC (204,188)
12. **Entrelacement** — Protection contre les erreurs en rafale
13. **Code Convolutif** — Codage interne FEC
14. **QPSK** — Modulation en quadrature
15. **Filtre SRRC** — Mise en forme des impulsions

## 🛠️ Technologies

- HTML/CSS/JavaScript pur
- Aucune dépendance externe
- Chaque étape est une page HTML autonome
- Calculs réels, pas juste des schémas

## 📖 Utilisation

Ouvrir n'importe quel fichier \`pageXX-*.html\` dans un navigateur pour explorer cette étape.

## 🎓 But pédagogique

Comprendre comment fonctionne la TV satellite numérique, de la compression vidéo à la modulation RF. Chaque page inclut :
- Explication théorique
- Visualisation interactive
- Calculs temps réel

## 📄 Licence

CC BY-NC 4.0

## 👤 Auteur

**Eric PERRET** — [GitHub](https://github.com/ericperret)