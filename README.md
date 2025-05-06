# 🛡️ android-threat-detector

**Détection de menaces Android (root, RASP, debug) avec Intelligence Artificielle**  
Outil d’analyse statique et dynamique pour repérer les mécanismes de sécurité dans les APKs Android.

---

## 🚀 Objectifs

- Détecter les protections comme :
  - Root detection
  - Debug detection
  - SSL Pinning
  - RASP (Runtime Application Self Protection)
- Appliquer l'IA (ML/DL) pour identifier des comportements suspects dans :
  - Le code décompilé
  - Le trafic réseau
  - Les permissions et manifestes
- Contourner certaines protections en environnement contrôlé (recherche uniquement)

---

## 📂 Structure du projet

```bash
.
├── analysis/             # Scripts d'analyse statique/dynamique
├── core/                 # Modules IA de détection
├── model/                # Modèles IA entraînés (ex: threat_model.pkl)
├── rasp/                 # Scripts de contournement (RASP, root checks, etc.)
├── data/                 # Jeux de données & APKs de test
├── screenshots/          # Captures d'écran de l'outil
├── requirements.txt
└── README.md
