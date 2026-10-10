# Rapport d'investigation

**Statut : modèle à remplir. Aucune conclusion n'est encore établie.**

## 1. Résumé

À rédiger à la fin : contexte, hôte concerné, comportement observé, conclusion et limite principale. Quelques phrases suffisent.

## 2. Périmètre et qualité de la capture

- Source, nom du fichier et SHA-256 : à compléter.
- Période, fuseau horaire et point de capture : à compléter ou indiquer « inconnu ».
- Informations fournies par l'exercice : à compléter.
- Paquets tronqués, flux incomplets ou autres limites : à vérifier.

## 3. Vue d'ensemble du trafic

| Hôte | Rôle supposé | Protocoles | Preuve et justification |
| --- | --- | --- | --- |
| À compléter | À compléter | À compléter | À compléter |

Décrire les conversations principales et le fonctionnement normal attendu avant d'expliquer les anomalies.

## 4. Observations et investigation

Dupliquer cette section pour chaque observation utile.

### Observation OBS-001 — titre à compléter

- **Fait observé :** décrire uniquement ce que montrent les données.
- **Pourquoi l'examiner :** expliquer l'écart ou la question.
- **Preuve :** numéro de paquet, flux TCP, horodatage, UID Zeek et/ou fichier dans `preuves/`.
- **Méthode :** filtre Wireshark ou requête sur les journaux, avec paramètres.
- **Hypothèse :** comportement que l'observation pourrait expliquer.
- **Autre explication possible :** activité légitime ou limite de capture à considérer.
- **Vérification :** données consultées pour confirmer ou écarter l'hypothèse.
- **Conclusion locale :** confirmé, probable, non établi ou écarté ; préciser pourquoi.

## 5. Chronologie

Résumer la séquence observée et renvoyer à [chronologie.csv](chronologie.csv). Ne pas ajouter une étape de l'attaque qui n'est pas visible ou corroborée.

## 6. Indicateurs

Voir [indicateurs.csv](indicateurs.csv). Pour chaque valeur, préciser son rôle, les preuves et sa qualification. Une adresse extraite du PCAP n'est pas automatiquement un IOC.

## 7. MITRE ATT&CK

Voir [mitre-attack.csv](mitre-attack.csv). Associer une technique à un comportement justifié, pas seulement à un protocole. Indiquer « aucune correspondance établie » si les preuves ne suffisent pas.

## 8. Conclusion et limites

- Ce qui est établi : à compléter.
- Ce qui reste une hypothèse : à compléter.
- Données manquantes : à compléter.
- Vérification suivante utile : à compléter.

## 9. Reproduction

Indiquer les versions, les commandes exactes et les filtres utilisés. Lier les preuves pour permettre de vérifier les conclusions.
