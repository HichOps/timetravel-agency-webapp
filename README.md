# TimeTravel Agency - Webapp Interactive ⏳✨

Webapp immersive pour une agence de voyage temporel de luxe, réalisée dans le cadre du projet supervisé "IA Créatives".

🔗 **Démo en ligne** : [(https://time-tracer-hub.lovable.app/)]

## 📝 Description

Cette application "One Page" permet aux utilisateurs de découvrir des destinations historiques, d'interagir avec **Chronos** (un agent temporel intelligent) et d'obtenir des recommandations personnalisées via un quiz interactif.

L'objectif était de créer un MVP (Minimum Viable Product) fonctionnel, responsive et esthétique en utilisant exclusivement des outils d'IA générative (Vibe Coding).

## 🛠 Stack & Outils Utilisés

Ce projet repose sur une collaboration entre plusieurs IAs et outils modernes :

### 🤖 Génération & Code
* **Lovable.dev** : Plateforme de "Vibe Coding" utilisée pour générer l'intégralité du code (Frontend React + Tailwind) à partir de prompts en langage naturel.
* **Gemini (Google)** : Assistant IA utilisé pour la structuration du projet, l'élaboration des prompts complexes, la rédaction de la documentation et la vérification technique.
* **GitHub** : Gestion du code source (Version Control) et partage du projet.

### 🎨 Assets & Visuels
* **Nano Banana** : IA génératrice d'images utilisée pour créer les visuels exclusifs des destinations (Paris 1889, Crétacé, Florence 1504) et donner une identité "cinématographique" unique au site.
* **Imgur** : Hébergement cloud des assets graphiques pour l'intégration web.
* **Lucide React** : Librairie d'icônes pour l'interface utilisateur.

### ⚡ Architecture Technique
* **Framework** : React (via Vite)
* **Styling** : Tailwind CSS (pour le design responsive et le mode sombre).
* **Animations** : CSS natif et logique React pour les interactions fluides.

## ✨ Fonctionnalités Clés

1.  **Hero Section Immersive** : Design "Dark Mode" premium avec mise en avant des visuels Nano Banana.
2.  **Galerie Temporelle** : Cartes interactives présentant les époques avec effets de survol.
3.  **🤖 Agent Chronos** : Chatbot intégré (simulé) capable de renseigner sur la sécurité, les prix et l'expérience voyageur.
4.  **🧭 Chrono-Quiz** : Algorithme de recommandation qui suggère la destination idéale selon les préférences de l'utilisateur.
5.  **Responsive Design** : Interface "Mobile-First" parfaitement adaptée aux smartphones.

## ⚖️ Transparence & Processus

Conformément à la charte d'utilisation des IA :
* **Code** : Généré à 100% via Lovable sous supervision humaine.
* **Stratégie** : Élaborée avec l'aide de Gemini.
* **Images** : Synthétisées via Nano Banana.

## 🧠 Retour d'expérience & Processus (Vibe Coding)

Ce projet a été réalisé en 2 heures en adoptant une approche "Vibe Coding" pure.

### Ce qui a bien fonctionné :
* **Rapidité d'exécution** : Passer de l'idée au MVP déployé en moins de 2h grâce à Lovable.
* **Prompt Engineering** : L'utilisation de descriptions visuelles précises (inspirées des images générées) a permis d'obtenir un design "Dark Mode" cohérent du premier coup.
* **Intégration des Assets** : L'hébergement externe sur Imgur a contourné la complexité de la gestion de fichiers locaux.

### Défis rencontrés & Solutions :
* **Hallucinations du Chatbot** : Au début, l'agent inventait des réponses. Solution : Injection d'un contexte strict ("Tu es Chronos...") et de règles métier (Prix, Sécurité) directement dans le prompt système.
* **Contraintes de Crédits** : La gestion des tokens a nécessité d'être stratégique sur les prompts (regrouper les demandes de modifications en un seul message).

### Conclusion
L'IA a agi comme un développeur senior, me permettant de me concentrer sur l'UX, la direction artistique et la logique métier plutôt que sur la syntaxe React.

## 📄 Licence
MIT License - Projet pédagogique M1/M2.
