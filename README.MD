# Chatbot Intelligent – Microservice RAG (Spring Boot)
## Description

Ce projet consiste à développer un microservice de chatbot intelligent en utilisant Spring Boot et l’architecture RAG (Retrieval-Augmented Generation).
Le système combine des techniques avancées de traitement du langage naturel (NLP) avec des mécanismes de recherche d’information, afin de fournir des réponses pertinentes, précises et contextualisées.

Le chatbot est exposé sous forme d’une API REST, facilitant son intégration avec des applications web, mobiles ou d’autres microservices.

## Architecture Générale

L’architecture repose sur les composants suivants :

- API REST Spring Boot : gestion des requêtes utilisateur

- Module Retrieval : recherche sémantique dans une base de connaissances

- Module Generation : génération de réponses via un modèle de langage

- Base de données / Vector Store : stockage des documents et embeddings

- Microservice indépendant : déployable et scalable

## Principe RAG

- L’utilisateur envoie une question via l’API REST

- Le module de recherche identifie les documents les plus pertinents

- Le contexte récupéré est injecté dans le modèle de génération

- Le chatbot retourne une réponse enrichie et contextualisée

## Fonctionnalités

- Chat interactif en temps réel

- Recherche d’informations dans des documents ou une base de données

- Génération de réponses contextuelles grâce à RAG

- API REST pour l’intégration avec d’autres services

- Architecture microservice basée sur Spring Boot

## Cas d’Utilisation

- Assistant intelligent basé sur des documents métiers

- Chatbot universitaire ou pédagogique

- Support client automatisé

- Système de questions-réponses interne

### Réalisé par: RANIA KETTANI
