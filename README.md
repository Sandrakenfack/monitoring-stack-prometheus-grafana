# 📊 Monitoring d'Infrastructure Linux (Prometheus & Grafana)

## 🌟 Aperçu du Projet
Ce projet démontre la mise en place d'une solution d'observabilité complète pour un serveur Ubuntu. Il permet de surveiller les ressources système en temps réel et d'automatiser les alertes de performance.

---

## 🖼️ Dashboard en Action
![Capture du Dashboard](dashboard-preview.png)

## 🎥 Démonstration du Stress Test
*Cette vidéo montre la réaction du dashboard lors d'une simulation de charge CPU/RAM via l'outil `stress`.*

![Vidéo Démo](monitoring-demo-live.mp4)

---

## 🛠️ Stack Technique & Métriques
* **Outils** : Prometheus (Collecte), Grafana (Visualisation), Node Exporter (Agent).
* **Métriques surveillées** : 
  * 📈 Utilisation CPU (Global & par cœur)
  * 🧠 Consommation RAM
  * 💽 Espace disque et I/O
  * 🌐 Trafic réseau entrant/sortant
* **Alerting** : Notifications configurées pour les seuils critiques (> 90%).

## 📂 Comment utiliser ce projet
1. Téléchargez le fichier `dashboard.json` présent dans ce dépôt.
2. Importez-le dans votre instance **Grafana** (Dashboards > Import).
3. Assurez-vous d'avoir une source de données **Prometheus** configurée avec **Node Exporter**.
