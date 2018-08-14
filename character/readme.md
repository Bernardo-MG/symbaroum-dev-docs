# Character

## Attributes

These are the main stats, which all characters have.

* Accurate
* Cunning
* Discreet
* Persuasive
* Quick
* Resolute
* Strong
* Vigilant

## Secondary Attributes

Always present too. Generated from attributes.

* Corruption Threshold
* Defense
* Pain Threshold
* Toughness

Note that defense is dependent on the armor, so there will be a value for each armor set.

### Formulas

The secondary attributes are calculated like this:

* Corruption Threshold: Resolute / 2 (rounded up)
* Defense: Quick - armor malus
* Pain Threshold: Strong / 2 (rounded up)
* Toughness: Strong (minimum 10)

Defense may be modified by more things than the armor, for example the robust trait. For this it is better using this formula:

* Defense = Quick - Defense Reduction

## Additional Stats

Some additional statistics:

* Resolute for powers: resolute - armor malus

Note that resolute for powers is dependent on the armor, so there will be a value for each armor set.

### Attribute modifiers

These are the modifiers calculated from attributes.

### Spent Stat

The following stats can be "spent", meaning they can have a maximum and a current value:

* Corruption
* Toughness

### Corruption

* Temporal corruption
* Permanent corruption

### Armor

The armor value depends on the armor used. But there are several sources for armor, such as traits, which can stack.

Some of these sources are not real armor. For example robust ignores damage. 

### Damage Bonus

The character may have several damage bonus:

* Base damage
* Single attack
* For a type of weapon
* Advantage attacks

### Attack Attributes

By default accuracy is used for the attacks.

The following attacks may have an additional attribute:

* Advantage
* Normal attack

In these cases the additional attribute should be noted.

### Defense Value

By default quick is used for defense. Some aspects may add additional attributes.

Defense should be noted for all the possible attributes.

Defense is modified by aspects, for example armors with the cumbersome quality or the berserker ability.

### Initiative

By default quick is used for initiative. Some aspects may add additional attributes.

### Mystical Power Ability

By default mystical powers are used with resolute modified by the armor encumbrance. Some aspects may change this formula. Some aspects may add additional attributes.

