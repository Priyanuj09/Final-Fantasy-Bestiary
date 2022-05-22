# Final Fantasy
![](https://steamcdn-a.akamaihd.net/steam/apps/1173770/header.jpg)

### About the game
Final Fantasy is a fantasy role-playing video game developed and published by Square in 1987. It is the first game in Square's Final Fantasy series, created by Hironobu Sakaguchi. Originally released for the NES, Final Fantasy was remade for several video game consoles and is frequently packaged with Final Fantasy II in video game collections.\
The first Final Fantasy story follows four youths called the Light Warriors, who each carry one of their world's four elemental crystals which have been darkened by the four Elemental Fiends. Together, they quest to defeat these evil forces, restore light to the crystals, and save their world _[...read more!](https://en.wikipedia.org/wiki/Final_Fantasy_(video_game)#:~:text=The%20first%20Final%20Fantasy%20story,crystals%2C%20and%20save%20their%20world.)_

## Notes
A complete bestiary data of Final Fantasy 1 written in JSON
- Contains all monsters _(#203 in total)_
- Updated stats

### Preview
```json
{
  "game": "Final Fantasy",
  "bestiary": [
    {
      "count": 100
    },
    {
      "name": "Chaos",
      "hp": 10,
      "attack": 5,
      "accuracy": 2,
      "defense": 4,
      "agility": 3,
      "intelligence": 1,
      "evasion": 6,
      "magic_defense": 0,
      "gil": 20,
      "exp": 20,
      "treasure": "Potion",
      "weakness": [
        "Lightning",
        "Dia"
      ],
      "resistance": [
        "Darkness"
      ],
      "is_boss": false
    }
  ]
}
```
###### The above JSON preview shown is for viewing purpose only and data inputted there are fake.

### Data Type
| Name                   | Type     | Return Information|
| ---------------  | ------- |------------------ |
| game                   | String    | Game name|
| count                   | Integer  | Total no. of monsters in bestiary. |
| name                   | String    | Monster's name. |
| hp                        | Integer  | Monster's health points. |
| attack                  | Integer  | Monster's attack value. |
| accuracy            | Integer   | Monster's attack accuracy value. |
| defense              | Integer   | Monster's attacks resistance capacity value. |
| agility                  | Integer   | Monster's agility value. |
| intelligence        | Integer   | Monster's intelligence value. |
| evasion               | Integer  | Monster's attacks evading capacity value. |
| magic_defense | Integer  | Monster's magic defense value. |
| gil                         | Integer  | Amount of money received by player upon defeating the monster. |
| exp                      | Integer  | Amount of experience gained by player upon defeating the monster. |
| treasure              | String    | A specific item where a player might get upon defeating the monster. |
| weakness           | String    | List of magic spells which are vulnerable to the monster. |
| resistance           | String    | List of magic spells which are immune/has less effects to the monster. |
| is_boss               | Boolean | `true` if the monster is a boss else `false`|

## Source
Following are the various sources which were used while making this complete bestiary data -
- Final Fantasy 1 & 2 - Dawn of Souls  - GBA (USA)
    - Monsters Stats #1-#195
- Final Fantasy - 20<sup>th</sup> Anniversary Edition - PSP (JP)
   - Monsters Stats #196-203
