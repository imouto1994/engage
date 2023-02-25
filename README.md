# engage

## Changes

Built on top of Battle Outfits Mod

#### assettable.xml

- Update assets to include new weapons

#### shop.xml

- Flea market now sells Steel Iron & Silver Iron in infinite amount after Chapter 16
- Flea market now sells all Augment Materials in infinite amount after Chapter 18
- Costume shop now sells all swimsuit outfits after Chapter 16
- Update weapon shops to include new weapons in respective chapters

#### item.xml

- Added Emblem Weapons:
    - Byleth Vajra - Arts (Normal & Glow)
    - Edelgard Failnaught - Bow (Normal & Glow)
    - Leif Killer Axe - Axe (Normal & Glow)
    - Meteor - Tome (Normal only)
    - Roy Binding Blade - Sword (Normal & Glow)
    - Lyn Mani Katti - Sword (Normal & Glow)
    - Byleth Sword of the Creator - Sword (Normal & Glow)
    - Corrin Yato - Sword (Normal & Glow)
    - Leif Master Lance - Lance (Normal & Glow)
    - Byleth Luin - Lance (Glow only)

#### god.xml

- Changed Ike:
    - Replaced `Reposition` with `Battlewise`
    - Replaced `Demolish` with `Adaptable`
    - Removed all Engage Weapons

#### person.xml

- Added `+1 range` to Ivy Default Skills

#### skill.xml

- Fixed Arts damage calculation to be `Max (STR, MAG)` instead of `(STR + MAG) / 2`
- Changed Lapis Personal Skill to `+10 Crit` instead of `-10 Crit`
- Changed Ivy Personal Skill from `+20 Hit to same previous target` to `100% Double Attack`
- Changed Lindwurm Class Skill:
    - Changed probability from `%DEX` to fixed `80%`
    - Scaled with `ENEMY RES` instead of `ENEMY MAG`
- Changed Picket Class Skill:
    - Changed probability from `%DEX` to fixed `80%`
