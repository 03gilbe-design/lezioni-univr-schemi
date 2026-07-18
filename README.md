# Lezioni UniVR verso Appunti e Schemi

![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat&logo=jupyter&logoColor=white)

App Google Colab che trasforma una lezione (video Panopto UniVR, dal PC, o da Google Drive) in appunti, esercizi o schemi con diagrammi e immagini delle slide.

Non serve saper programmare: apri il notebook in Colab, esegui le celle in ordine e compila i campi che compaiono.

## Apri in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/03gilbe-design/lezioni-univr-schemi/blob/master/App_Lezioni_Schemi_Colab.ipynb)

## Cosa serve

- Una chiave Groq gratuita (trascrizione): https://console.groq.com/keys
- Una chiave Gemini gratuita (generazione appunti): https://aistudio.google.com/apikey

Le chiavi le inserisci tu nel notebook, non sono incluse nel codice.

## Come funziona

1. Scegli la lezione (Panopto UniVR con ricerca, oppure carichi un video)
2. Il notebook trascrive l'audio (Whisper via Groq)
3. Genera appunti/esercizi/schemi con diagrammi (lore-engine + Gemini)
4. Te li mostra e li scarica

Basato su [lore-engine](https://github.com/Slydite/lore-engine) e [panopto-sync](https://gitlab.com/Microeinstein/panopto-sync).
