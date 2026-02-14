# SOC-Home-Lab-Detection-Intrusions-et-Analyse-de-Logs
Ce projet présente la mise en place d'une architecture de surveillance réseau complète utilisant la Stack ELK et Suricata.


Architecture

-Sonde IDS : Suricata configuré sur un routeur Linux (Debian) pour l'inspection du trafic.

-Collecte de données : Elastic Agent & Fleet pour la centralisation des logs (Système, Apache, IDS).

-Visualisation : Dashboards Kibana personnalisés pour la détection de menaces.


Scénarios de détection implémentés

-Brute Force SSH : Identification des tentatives de mouvements latéraux via les logs auth.log

-Surveillance Web : Détection d'accès externes non autorisés via des signatures Suricata personnalisées.

-Analyse de trafic Web : Filtrage des méthodes HTTP (POST) pour surveiller l'intégrité du serveur web.
