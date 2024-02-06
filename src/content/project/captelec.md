---
title: CaptElec
description: Application d'affichage de données de capteurs présent au sein de l'IUT de Blaganc
img: "/portfolio/captelec.png"
badge: ""
url: https://github.com/rboulle/SAE-ALT-S3-Dev-22-23-CaptElec-3A-Equipe-2
year: 2022
tags: ["javascript", "docker", "mqtt", "backend"]
---
Dans le cadre du troisième semestre de ma formation à l'IUT de Blagnac, j'ai participé, en groupe de 5 personnes, à la réalisation d'une application d'affichage de données de capteurs présent au sein de l'IUT de Blagnac.

## Contexte

CaptElec est une application web permettant de visualiser les données de capteurs présents au sein de l'IUT de Blagnac. Ces capteurs sont utilisés pour mesurer la température, l'humidité, la concentration en CO2 dans les salles de l'IUT. Les données sont envoyées par les capteurs à un serveur MQTT. L'application CaptElec se connecte à ce serveur pour récupérer les données et les afficher sous forme de graphiques.

## Ma contribution

Sur ce projet, j'ai principalement travaillé sur la partie backend de l'application. J'ai utilisé le framework Node.js pour développer une API REST. Cette API permet de récupérer les données des capteurs depuis le serveur MQTT et de les envoyer à l'application web.

J'ai également mis en place une base de données PostgreSQL pour stocker les données de l'application.

Enfin, j'ai utilisé Docker pour déployer l'application sur un serveur afin de rendre l'application accessible à tous les étudiants et enseignants de l'IUT.
