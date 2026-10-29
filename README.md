# Salut, moi c'est Nicolas

Lead dev chez [Ubikap](https://www.ubikap.com), à Lyon. Avant ça j'étais CTO de [Legal Pilot](https://legal-pilot.com), sur lequel je bosse toujours aujourd'hui.

Ce qui me plaît, c'est de partir d'un besoin un peu flou et d'arriver à un truc qui tourne en prod. Je cadre, je dessine les écrans, j'écris le front et le back, puis je m'occupe du serveur derrière. Quand c'est la même personne qui imagine et qui construit, on perd beaucoup moins de temps en traductions.

## Au boulot

Du SaaS B2B pour les juristes. Concrètement : beaucoup de TypeScript, de l'Angular et du React côté interface, NestJS et PostgreSQL derrière, et pas mal d'intégrations avec les outils que les cabinets utilisent déjà (signature électronique, logiciels métier, bases documentaires). Je passe aussi du temps à brancher des LLM dans le produit de façon propre, sans s'enfermer chez un seul fournisseur.

## À côté

Je fais de la musique, et forcément ça finit dans le code.

**LiveSet** est probablement le projet dont je suis le plus fier. C'est un lecteur de backing tracks pour la scène, écrit entièrement en Rust, piloté au pied. Le callback audio ne fait aucune allocation ni aucun lock, et un test le vérifie. Les machines du groupe se trouvent toutes seules sur le réseau et restent calées entre elles sans machine maître. Dans le même esprit j'ai fait une télécommande pour la table de mixage XR18 en OSC brut, et un petit convertisseur de notes MIDI en program changes.

J'ai aussi monté **Drive for Artists**, une plateforme pour gérer un groupe de A à Z, et le site d'[August Is Gone](https://augustisgone.com), sans framework, juste du HTML et du CSS qui chargent vite.

Côté Android, j'aime bien remplacer les applis qui m'agacent par les miennes :

* [echappee](https://github.com/Nico7an/echappee) : GPS vélo en Kotlin, navigation temps réel, fonctionne hors-ligne, se connecte au capteur cardio
* [Spotlight](https://github.com/Nico7an/Spotlight) : la recherche d'apps de macOS, sur tablette, au clavier uniquement
* [Terminal](https://github.com/Nico7an/Terminal) : un client SSH minimaliste pour Android
* [btop](https://github.com/Nico7an/btop) : un moniteur système façon btop au look One UI, pensé pour les Galaxy S et DeX, sans root
* [regles](https://github.com/Nico7an/regles) : suivi de cycle menstruel où les données ne quittent jamais le téléphone

J'ai même fait de la rétro-ingénierie sur le Bluetooth d'une balance connectée pour me passer de l'appli du constructeur.

Et quelques outils nés d'une frustration précise :

* [actions](https://github.com/Nico7an/actions) : l'onglet Actions de GitHub, mais pour ton propre serveur. En Go, zéro dépendance.
* [FrameworkPowerManagement](https://github.com/Nico7an/FrameworkPowerManagement) : basculer la limite de charge d'un Framework Laptop 13 entre 80 et 100 % depuis la barre des tâches, sans redémarrer
* [MacUnzipForWindows](https://github.com/Nico7an/MacUnzipForWindows) : ouvrir proprement sous Windows un zip fait sur Mac, sans les dossiers `__MACOSX` qui traînent
* [kapsule](https://github.com/Nico7an/kapsule) : apprendre le fonctionnement d'une entreprise par petites capsules de 3 minutes

Il y a aussi [Boussole Législative](https://krateos.fr), pour suivre les lois et les votes des députés à partir de l'open data de Légifrance et de l'Assemblée.

## Ce que j'utilise

| | |
|---|---|
| Langages | TypeScript, JavaScript, Rust, Kotlin, Go, PHP, SQL |
| Front | React, Angular, Vite, Tailwind |
| Back | NestJS, Node / Express, API Platform, PostgreSQL, Redis, Supabase |
| Mobile | React Native / Expo, Capacitor, Android natif, Android TV |
| Infra | Cloudflare Workers et Pages, Docker, Traefik, Helm, GitHub Actions, S3 / MinIO, un serveur perso à la maison |
| IA | APIs LLM multi-fournisseurs, agents et MCP, RAG, embeddings, OCR |

La plupart de mes projets sont en privé. Si l'un d'eux t'intéresse, demande.

## Me trouver

[nico7an.fr](https://nico7an.fr) · [LinkedIn](https://fr.linkedin.com/in/nicoseven) · contact@nico7an.fr
