# 💊 Munitions

{% hint style="info" %}
Liste complète des types de munitions disponibles sur Tanoa RP.
{% endhint %}

---

## 📦 Types de munitions (AMMO)

| Type | Description |
|------|-------------|
| `AMMO_PISTOL` | Pistolets standard |
| `AMMO_STUNGUN` | Pistolet à impulsions |
| `AMMO_FLARE` | Fusée éclairante |
| `AMMO_SMG` | Pistolets mitrailleurs |
| `AMMO_SHOTGUN` | Fusils à pompe |
| `AMMO_RIFLE` | Fusils d'assaut |
| `AMMO_POLICE_RIFLE` | Fusils police |
| `AMMO_MG` | Mitrailleuses |
| `AMMO_SNIPER` | Fusils de précision |
| `AMMO_SNIPER_REMOTE` | Sniper télécommandé |
| `AMMO_RPG` | Lance-roquettes |
| `AMMO_GRENADELAUNCHER` | Lance-grenades |
| `AMMO_MINIGUN` | Minigun |
| `AMMO_STINGER` | Hérisson / Stinger |
| `AMMO_EMPLAUNCHER` | Lance EMP |
| `AMMO_BALL` | Balles spéciales |
| `AMMO_PETROLCAN` | Jerrycan |
| `AMMO_FERTILIZERCAN` | Engrais |
| `AMMO_POISON` | Munition spéciale Assasingun |

---

## 🗺️ Config Items — Munitions

```lua
Config.AmmoItems = {
    { item = 'pistol_ammo',           type = 'AMMO_PISTOL' },
    { item = 'rifle_ammo',            type = 'AMMO_RIFLE' },
    { item = 'smg_ammo',              type = 'AMMO_SMG' },
    { item = 'shotgun_ammo',          type = 'AMMO_SHOTGUN' },
    { item = 'mg_ammo',               type = 'AMMO_MG' },
    { item = 'emp_ammo',              type = 'AMMO_EMPLAUNCHER' },
    { item = 'rpg_ammo',              type = 'AMMO_RPG' },
    { item = 'grenadelauncher_ammo',  type = 'AMMO_GRENADELAUNCHER' },
    { item = 'snp_ammo',              type = 'AMMO_SNIPER' },
    { item = 'police_rifle_ammo',     type = 'AMMO_POLICE_RIFLE' },
    { item = 'police_shotgun_ammo',   type = 'AMMO_POLICE_SHOTGUN' },
    { item = 'police_smg_ammo',       type = 'AMMO_POLICE_SMG' },
    { item = 'police_pistol_ammo',    type = 'AMMO_POLICE_PISTOL' },
    { item = 'master_ammo',           isForEveryWeapon = true },
}
```
