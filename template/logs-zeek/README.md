# Journaux Zeek

Ce dossier recevra les journaux générés à partir du PCAP. Aucun journal n'a encore été produit.

Depuis le dossier du nouveau cas, dans un shell Linux ou WSL avec Zeek installé :

```bash
cd logs-zeek
zeek -r ../capture.pcap LogAscii::use_json=T
```

Adapter le nom si la capture est au format PCAPNG. Noter la commande exacte et la version de Zeek dans le rapport. Les journaux dépendent du trafic visible : tous les protocoles ne produiront pas nécessairement un fichier.
