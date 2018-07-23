# Character Properties

These have effects on the character.

Having an aspect or equipment with any of these properties will have the indicated effect.

|Property|Effect|Notes|
|---|---|---|
|Additional attack attribute|Allows attacking with an alternative attribute|Name of attribute + type of attack|
|Additional defense attribute|Allows defending with an alternative attribute|Name of attribute + type of defense|
|Additional initiative attribute|Allows calculating initiative with an alternative attribute|Name of attribute|
|Damage die bonus|Adds additional damage to advantage attacks|Type of attack + die level progression + single attack flag|
|Damage level bonus|Increases the damage of ranged attacks|Type of attack + level increase, Integer|
|Defense bonus|Increases defense protection|Type of defense|
|Dual wielding damage bonus|Increases damage when dual wielding|This is a more complex formula|
|Multiple attacks|Several attacks with a single action|Type of attack + number of attacks|
|Armor level bonus|Increases the protection given by armors|Level increase, Integer|
|Attack causes condition|Attacks cause a condition|Name of condition|
|Attack ignores armor|Attacks ignore armor|Type of attack|
|Craft alchemy|Create alchemical elixirs|Level indicates the range of objects to create|
|Creature specialisation|Linked to a creature type|Type name|
|Creature specialisation damage|Additional damage to the creature specialisations|Die level progression|
|Defense modifier|Changes defense by a negative or positive value|Integer value|
|Extra movement action|Extra movement action each turn||
|Grants rituals|Allows acquiring rituals|The levels affects the number of rituals|
|Ignore damage|Adds additional protection, not affected by armor penetration|Die level progression|
|Ignore impending armor - Quick|Ignores the impending modifier for Quick||
|Increase armor|Adds additional armor|Die level progression|
|Increase healing power|Increases the effect of healing powers|Die level progression|
|Modify attribute|Changes the value of an attribute|Attribute, integer|
|Reduce learning corruption|Reduces the corruption caused by learning powers or rituals|Affected school, integer (level)|
|Reduce power corruption|Reduces the corruption caused by magical powers to the minimum|Affected school|
|Reduce power corruption - Roll|Reduces the corruption caused by magical powers to the minimum through a roll|Affected school|
|Requires custom armor|Can only wear customised armors||
|Shield bash|Allows doing a shield bash|Die level progression (damage)|
|Set base defense|The attribute used for calculating defense is considered to be at the defined value|Natural number|
|Swap movement action for attack|Swaps a movement for an attack||

## Stacking Properties

Some properties may stack, for example multiple instances of increase armor. Check this.

If the single attack flag is used, then the values stack for a single attack.
