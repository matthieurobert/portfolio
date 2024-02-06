---
title: Flop Bot
description: Intégration d'un bot discord à l'application FlopEdt afin de notifier les étudiant des changements d'emploi du temps
img: "/portfolio/flopbot.png"
badge: ""
url: https://framagit.org/Eric-Philippe/flop-edt-flop-scheduler-flop-bot
year: 2023
tags: ["python", "django", "backend"]
---
Dans le cadre du quatrième semestre de ma formation à l'IUT de Blagnac, j'ai participé, en groupe de 2 personnes, à l'amélioration de l'application FlopEdt.

## Contexte

FlopEdt est une application web permettant aux étudiants de l'IUT de Blagnac de consulter leur emploi du temps. Lorque l'emploi du temps est modifié, les étudiants ne sont pas notifiés. Pour remédier à cela, nous avons décidé d'intégrer un bot discord à l'application. Ce bot est capable de notifier les étudiants des changements d'emploi du temps.

## Ma contribution

Sur ce projet, j'ai principalement travaillé sur la partie backend de l'application. J'ai utilisé le framework Django pour compléter l'API REST existante, en ajoutant la connection de à discord afin de pouvoir envoyer des messages aux étudiants lorsqu'un changement d'emploi du temps est détecté.