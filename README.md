# 📊 Monitoring d'Infrastructure Linux (Prometheus & Grafana)
Stack d'observabilité complète (Prometheus/Grafana) pour serveur Linux avec alerting Discord.

## 🏗️ Architecture Technique
L'écosystème repose sur trois composants majeurs :
* **Node Exporter** : Collecte les métriques matérielles (CPU, RAM, Disque) sur le port 9100.
* **Prometheus** : Serveur de stockage des données qui récupère les métriques toutes les 15 secondes.
* **Grafana** : Interface de visualisation pour transformer les données en graphiques décisionnels.

## 📊 Métriques Surveillées
* **Calcul (CPU)** : Utilisation en temps réel pour identifier les pics de charge.
* **Mémoire (RAM)** : Suivi de la consommation pour prévenir les saturations.
* **Stockage (Disk)** : Surveillance de l'espace disque disponible.
* **Réseau (I/O)** : Analyse du débit entrant et sortant.

## ⚠️ Gestion des Alertes
Le projet inclut une configuration d'alerting proactif :
* **Seuils** : Warning à 80% et Critical à 90%.
* **Canal** : Notifications envoyées automatiquement via **Webhook vers Discord**.

## 📂 Contenu du Dépôt
* `dashboard.json` : Modèle de tableau de bord prêt à l'emploi.
* `prometheus.yml` : Configuration du serveur de collecte.
![Capture](dashboard-preview.png)

![Video](monitoring-demo-live.mp4)
