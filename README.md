# SOC Task: Security Alert Monitoring & Incident Response

## Description du Projet
Ce projet simule les activités d'un analyste **SOC (Security Operations Center)**. L'objectif était d'analyser des journaux système (logs) via un outil SIEM pour détecter des menaces, les classifier par priorité et rédiger un rapport d'incident complet.

## Outils Utilisés
*   **SIEM :** Elastic Stack (ELK)
*   **Analyse de données :** Kibana (KQL - Kibana Query Language)
*   **Format des données :** Logs convertis en CSV pour une ingestion structurée.
*   **Reporting :** Google Docs / PDF.

## Analyse SIEM (Elasticsearch)
Grâce à Elastic, j'ai pu identifier plusieurs menaces critiques :
*   **Ransomware Behavior** sur l'utilisateur Bob.
*   **Rootkit Signature** détecté sur le poste d'Alice.
*   **Worm Infection** et tentatives de **Brute Force**.


## Contenu du Dépôt
*   `/logs` : Données brutes utilisées pour l'analyse.
*   `/reports` : Rapport d'incident détaillé (Timeline, Impact, Remédiation).
*   `/screenshots` : Captures d'écran du tableau de bord Elastic.

## Compétences Acquises
*   Ingestion et nettoyage de logs (CSV/Txt).
*   Analyse de menaces et triage d'alertes par priorité (Critique à Faible).
*   Utilisation d'un SIEM (Elasticsearch & Kibana).
*   Rédaction de rapports de réponse aux incidents (IRR).
