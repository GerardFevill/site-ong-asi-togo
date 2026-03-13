# site-ong-asi-togo — Contexte Projet

## Description
Site vitrine statique pour l'ONG Afrique Solidarite Internationale au Togo.
Un seul fichier `index.html` avec Tailwind CSS via CDN.

## Domaine
- Production : https://ongasitogo.org

## Stack
- HTML statique + Tailwind CSS (CDN)
- Nginx Alpine (image Docker)
- CI/CD : GitHub Actions -> Docker Hub (amesika2/site-ong-asi-togo)

## Deploiement
- Image Docker : amesika2/site-ong-asi-togo:latest
- Reverse proxy : nginx de MediFlow (Stellarix)
- VPS : 135.125.203.238
- Config Stellarix : stellarix/apps/site-ong-asi-togo/
