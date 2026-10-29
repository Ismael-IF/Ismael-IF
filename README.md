## Ismael Foudjo - Data Scientist & Machine Learning Engineer

Je conçois des chaînes de bout en bout : de la donnée brute au modèle servi,
puis du modèle à la décision que quelqu'un prend réellement.

Une métrique statistique ne vaut rien tant qu'elle n'est pas traduite en
règle chiffrée. C'est le fil conducteur de mes projets : je mesure d'abord
ce que vaut l'absence de modèle, puis ce que le modèle change à la décision.

### Projets

**[rakuten-mlops-project](https://github.com/Ismael-IF/rakuten-mlops-project)** - *industrialisation*
Deux pipelines Airflow : entraînement tracé dans MLflow et promotion en
Model Registry, puis build et déploiement automatisés de l'API FastAPI qui
sert le modèle. Docker Compose, MinIO S3, JWT, MongoDB. 

**[gel-temperature-humide](https://github.com/Ismael-IF/gel-temperature-humide)** - *donnée réelle et analyse de décision*
11,8 M de mesures horaires, 1 739 capteurs agro-météo. Trois approches que
je démontre non départagées, et la conclusion que le vrai levier n'est pas
le modèle mais le seuil d'alerte : à coûts asymétriques, il tombe à +2,5 °C
et non 0 °C, le coût des erreurs baisse de 79 %. Je recommande la formule
physique recalibrée plutôt que le gradient boosting.

**[silica-impurity-prediction](https://github.com/Ismael-IF/silica-impurity-prediction)** - *reproductibilité*
Pipeline DVC en six étapes, piloté par configuration, testé contre les
fuites de données, rejoué intégralement en CI. Le seuil d'alerte calibré
fait passer la détection des lots hors spécification de 21 à 54 sur 76.

### Outils

Python · scikit-learn · TensorFlow · Airflow · MLflow · DVC · FastAPI
Docker · PostgreSQL · MongoDB · MinIO/S3 · GitHub Actions · pytest · Git
