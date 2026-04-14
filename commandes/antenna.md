# 📡 Antenna System

## Gestion des Antennes

| Commande | Description |
|----------|-------------|
| `/ant_add <name> <x> <y> <z> [radius]` | Ajoute une nouvelle antenne en base de données. Retourne l'ID unique. |
| `/ant_remove <id>` | Supprime définitivement l'antenne correspondant à l'ID. |
| `/ant_repair [id]` | Répare l'antenne ciblée. Si aucun ID, répare la plus proche. |

## Configuration & Props

| Commande | Description |
|----------|-------------|
| `/ant_setradius <id> <radius>` | Modifie en temps réel le rayon d'action (en mètres). |
| `/ant_toggle <id>` | Alterne l'état entre "Active" et "Inactive". |
| `/ant_attachprop <id> <prop_hash> <netid>` | Attache un objet à l'antenne avec offset de position et rotation. |
