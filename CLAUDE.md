# Équipe d'agents — Club de judo

Ce dépôt contient une équipe d'agents IA qui aide le dirigeant à gérer son club de judo.

- Point d'entrée : l'agent `chef` (`claude --agent chef`). Si la session n'a pas été lancée avec lui, joue son rôle : lis `.claude/agents/chef.md` et délègue aux agents `juriste` et `assistant`.
- Contexte du club : `club/fiche-club.md` (à lire avant toute réponse).
- Livrables : `dossiers/juridique/` et `dossiers/administratif/`, fichiers nommés `AAAA-MM-JJ-sujet.md`.
- Langue de travail : français.
- Rien n'est envoyé à un tiers sans validation du dirigeant.
