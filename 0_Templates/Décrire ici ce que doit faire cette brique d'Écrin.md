---
title: Décrire ici ce que doit faire cette brique d'Écrin.
status: none
priority: normal
scheduled: 2026-11-10
dateCreated: 2026-11-03T15:52:53.863+01:00
dateModified: 2026-11-10T11:48:26.189+01:00
tags:
  - task
---

Développer, tester et valider une brique fonctionnelle de l'écosystème **Écrin**, qui s'articule autour de deux parcours clés et de quatre catégories cœurs :  
- Périmètre Fonctionnel et Parcours Double (Expéditeur - Destinataire)  
	- Côté Expéditeur (Application Mobile) :  Permettre à l'utilisateur d'orchestrer une attention personnalisée en choisissant parmi les 4 catégories : **RDV & Invitations**, **Mots doux**, **Surprises**, ou **Réconciliation ("Drapeau Blanc")**. 
	- Offrir la possibilité d'ajouter du contenu enrichi et multimédia : Questions interactives et QCM (ex: "Es-tu libre ce soir ?", "Quel restaurant préfères-tu ?").
	- Galerie de photos souvenirs et visuels du lieu.
	- Enregistrement vocal audio personnalisé.
	- Localisation GPS et adresse exacte de l'événement/RDV.
	- Valider et déclencher l'envoi instantané au destinataire via le numéro de téléphone portable.

	- Côté Destinataire (WebApp Web Responsive) : 
		- Expérience Zéro-Friction : Permettre au destinataire de consulter la surprise ou l'invitation sur son navigateur mobile via un lien unique et sécurisé reçu par SMS, **sans aucun téléchargement d'application**.  
		- Mettre en scène la surprise avec une interface fluide et émotionnelle (lecture audio, galerie photo, carte interactive, formulaire de réponse).
		
		- Capture et Sauvegarde :  
		Proposer un écran de conversion demandant à l'utilisateur de saisir son adresse email pour sauvegarder son cadeau , souvenir dans son espace personnel.  
		
	- Boucle de Rétroaction (Feedback Loop) :  
		- Envoyer une notification Push en temps réel sur l'application mobile de l'expéditeur dès que le destinataire a consulté le lien et répondu aux questions.  
		
		- Centraliser la liste des réponses et le statut dans l'historique de l'expéditeur.
