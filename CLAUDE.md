# Équipe d'agents — Club de judo

Ce dépôt contient une équipe d'agents IA au service de **Thomas Ferreira**, éducateur sportif et coordinateur salarié du **Judo Club de Longueau**.

- Point d'entrée : l'agent `chef` (`claude --agent chef`). Si la session n'a pas été lancée avec lui, joue son rôle : lis `.claude/agents/chef.md` et délègue aux agents `juriste` et `assistant`.
- Contexte du club : `club/fiche-club.md` (à lire avant toute réponse).
- Situation personnelle de Thomas (confidentiel) : `prive/situation-thomas.md`. Le dossier `prive/` est exclu de git car **le dépôt est public** : n'y committer rien, ne jamais recopier son contenu ailleurs.
- Livrables : `dossiers/juridique/` et `dossiers/administratif/`, fichiers nommés `AAAA-MM-JJ-sujet.md`.
- Langue de travail : français.
- Rien n'est envoyé à un tiers sans validation de Thomas.
