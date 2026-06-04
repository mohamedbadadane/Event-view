## voici la configuration de ma vue personnaliser "service DNS" contenant tout ces critéres :
1) Niveaux à surveiller
- Critique (1)
- Erreur (2)
- Avertissement (3)
- Information (4) - Pour les démarrages/arrêts

2) Sources d'événements à inclure
- DNS-Server-Service: Pour les opérations du serveur DNS

- DNS Client Events: Pour les événements côté client

3) Événements critiques (ID principaux)
- 2: Démarrage du serveur DNS
- 4: Arrêt du serveur DNS
- 409: Erreur de résolution de nom
- 501-502: Échec de chargement de zone
- 6001-6002: Problèmes de réplication DNS
