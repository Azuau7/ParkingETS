# ParkingETS

Carte interactive des places de stationnement autour de l'École de technologie supérieure (Montréal).

## Stack
- Frontend : HTML + CSS + JavaScript + Leaflet.js
- Backend : Java Spring Boot
- Base de données : PostgreSQL

## Structure
- `frontend/` — carte interactive, panel admin
- `backend/` — API REST Spring Boot

## Fonctionnalités
- Carte Leaflet centrée sur l'ÉTS avec zoom/dézoom
- Places individuelles par rue avec type (gratuit, payant, vignette, borne élec.)
- Filtre par date et heure
- Gestion des travaux et fermetures temporaires
- Panel admin pour ajouter/modifier/supprimer des places