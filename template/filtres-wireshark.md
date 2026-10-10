# Filtres Wireshark

**Modèle.** Les filtres ci-dessous sont des points de départ, pas des détections d'attaque. Ajouter les filtres réellement utilisés et leurs résultats dans le tableau.

| Filtre de départ | Question |
| --- | --- |
| `dns` | Quelles résolutions DNS sont visibles ? |
| `http.request` | Quelles requêtes HTTP en clair sont présentes ? |
| `tls` | Quels échanges TLS sont reconnus ? |
| `tcp.flags.syn == 1 && tcp.flags.ack == 0` | Quelles tentatives d'ouverture TCP sont visibles ? |

Après avoir identifié une adresse ou un flux, utiliser un filtre ciblé comme `ip.addr == 192.0.2.10` ou `tcp.stream == 0`. Ces valeurs sont des exemples à remplacer.

| Question étudiée | Filtre exact utilisé | Résultat observé | Référence de preuve |
| --- | --- | --- | --- |
| À compléter | À compléter | À compléter | À compléter |
