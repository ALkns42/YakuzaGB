# YakuzaGB
Attempt at translating the Yakuza franchise's world and combat to the Game Boy via GB Studio

# "Design"
## Open-world mode
* Top-down perspective
* Several interactive spots, like restaurants (to heal) and stores (to buy items)
* Random street battles that lead into
  
## Combat mode
* Similar to Zelda II
* 2D platformer with an attack button
* Mash [B] 5 times to perform a rush combo with a finisher
  * Probably gonna want to pull some waits as a sort of combo cooldown
* 2 HUD stats: Health and Heat
  * Health: Health, obviously. Reach 0 and you're done.
  * Heat: A resource to perform **HEAT ACTION**
    * Heat Action: a "super move", so to speak
    * Press [A] and [B] at the same time to execute
    * Massive damage, high knockback
* Completing combat nets you money, usually around 5000-20000 Yen

## Items
* 3 Recovery items, with 4 tiers:
|          | Toughness (Health) | Tauriner (Heat)  | Staminan (Health/Heat)* |
|----------|--------------------|------------------|-------------------------|
| Minimum  | Toughness Z        | Tauriner         | Staminan X              |
| Moderate | Toughness ZZ       | Tauriner+        | Staminan XX             |
| Marginal | Toughness Emperor  | Tauriner++       | Staminan Royale         |
| Maximum  | Toughness Infinity | Tauriner Maximum | Staminan Spark          |
* *Staminan recovers less health and heat for the cost of doing both in one drink
