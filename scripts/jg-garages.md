# 🚗 JG Advanced Garages

**Version :** jg-advancedgarages v3.2.6

{% hint style="info" %}
JG Advanced Garages est le système de garage avancé du serveur. Il gère le stockage, la récupération et l'impound des véhicules.
{% endhint %}

---

## ✨ Fonctionnalités
- Garages publics et privés
- Système d'impound (fourrière)
- Garages par métier et par gang
- Historique des véhicules
- Mileage tracking intégré

---

## 💡 Tips Staff

{% hint style="success" %}
**Tip 1** — Si un véhicule est introuvable dans le garage d'un joueur, utilise `/openinventorytarget` pour vérifier qu'il a bien ses clés, puis `/setjobvehicle` si c'est un véhicule de job.
{% endhint %}

{% hint style="success" %}
**Tip 2** — `/iv` met un véhicule en fourrière. Le joueur devra payer pour le récupérer à l'impound.
{% endhint %}

{% hint style="success" %}
**Tip 3** — `/privategarages` permet à l'immobilier de créer des garages privés liés à des propriétés.
{% endhint %}

{% hint style="warning" %}
**Attention** — `/dvdb` supprime un véhicule **définitivement** de la BDD. Utiliser avec extrême précaution.
{% endhint %}

---

## ⌨️ Commandes utiles

| Commande | Description | Accès |
|----------|-------------|-------|
| `/iv` | Mettre en fourrière | Police |
| `/privategarages` | Créer garage privé | Immobilier |
| `/setjobvehicle [job] [grade]` | Garage de métier | Admin |
| `/removejobvehicle [id]` | Retirer du garage métier | Admin |
| `/vplate` | Changer la plaque | Admin |
| `/dvdb` | Supprimer de la BDD | Admin |
| `/vreturn [plaque]` | Rentrer véhicule extérieur | Staff |
