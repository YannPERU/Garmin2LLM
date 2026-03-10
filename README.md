# 🏃 Garmin2LLM

Extrais tes données Garmin Connect (santé, sommeil, HRV, activités) et génère
un prompt clé-en-main à coller dans ChatGPT, Claude ou n'importe quel coach IA.

**Aucune installation locale** — tourne entièrement dans Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YannPERU/Garmin2LLM/blob/main/ColabGarmin2LLM.ipynb)

---

## ✨ Ce que ça fait

- 🏥 **Santé** — Training Status, bien-être, Body Battery, stress, pas
- 😴 **Sommeil** — Score, phases, HRV, agitation
- 🏃 **Activités** — Détail complet de chaque séance (splits, métriques)
- 📋 **Export** — CSV + texte fusionné prêt à coller dans un prompt IA

---

## 🚀 Démarrage rapide

1. Clique sur le badge **Open in Colab** ci-dessus
2. `Fichier → Enregistrer une copie dans Drive`
3. Configure tes identifiants dans le panneau 🔑 Secrets :
   - `GARMIN_EMAIL` → ton adresse email Garmin
   - `GARMIN_PASSWORD` → ton mot de passe Garmin
4. Lance les cellules dans l'ordre ▶️

---

## 🔐 Sécurité

Les identifiants sont stockés dans les **Secrets Colab** (chiffrés par Google,
invisibles dans le code). Ils ne transitent jamais en clair dans le notebook.
Le token de session Garmin est réutilisé automatiquement pour éviter
les re-connexions répétées.

---

## 📦 Dépendances

Installées automatiquement par le notebook :

- [`garminconnect`](https://github.com/cyberjunky/python-garminconnect)
- `python-dotenv`

---

## 📄 Licence

MIT — libre d'utilisation, de modification et de partage.

---

## 🙏 Crédits

Basé sur la bibliothèque open-source
[python-garminconnect](https://github.com/cyberjunky/python-garminconnect)
par [@cyberjunky](https://github.com/cyberjunky).
