# Modèle d'investigation PCAP

Ce dossier est un modèle à copier pour chaque nouvelle analyse.

1. Copier le dossier `template` et renommer la copie, par exemple `01-analyse-dns`.
2. Ajouter le fichier `capture.pcap` ou `capture.pcapng` directement dans le nouveau dossier.
3. Compléter la fiche du cas ci-dessous : source, contexte, empreinte SHA-256 et versions des outils.
4. Analyser la capture avec Wireshark et Zeek, puis remplir les livrables avec des preuves précises.
5. Rédiger le résumé et la conclusion après l'investigation.

Garder le dossier `template` vierge pour les analyses suivantes. Les fichiers CSV contiennent uniquement les colonnes à remplir. Aucun PCAP n'est inclus dans le modèle.

| Livrable | Contenu |
| --- | --- |
| [rapport.md](rapport.md) | Investigation, observations, vérifications et conclusions |
| [filtres-wireshark.md](filtres-wireshark.md) | Filtres utilisés et résultats |
| [chronologie.csv](chronologie.csv) | Séquence des événements et preuves |
| [indicateurs.csv](indicateurs.csv) | Indicateurs et qualification |
| [mitre-attack.csv](mitre-attack.csv) | Techniques proposées et justification |
| [preuves/](preuves/README.md) | Captures d'écran et extraits utiles |
| [logs-zeek/](logs-zeek/README.md) | Journaux issus du PCAP |

# Fiche du cas

**Statut : à compléter — investigation non réalisée.**

| Information | Valeur |
| --- | --- |
| Nom du cas | À compléter |
| Fichier PCAP | Ajouter `capture.pcap` ou `capture.pcapng` dans ce dossier |
| Source et lien | À compléter |
| Conditions de redistribution | À vérifier |
| SHA-256 | À calculer |
| Date de l'analyse | À compléter |
| Période couverte et fuseau horaire | À compléter |
| Contexte fourni par la source | À compléter ; séparer ce contexte des observations |
| Versions de Wireshark et Zeek | À compléter |

Les CSV contiennent uniquement des en-têtes : aucune ligne ne représente un résultat réel pour le moment.

Commencer par `rapport.md`. Conserver les identifiants des preuves dans les CSV pour retrouver chaque observation.
