# Neutralism
An MCPE behavior pack which makes hostile mobs always spawn in
neutral. Unless you aggravate them,
* Blazes don't shoot fireballs at you.
* Creepers don't explode.
* Silver fish, Wither Skeletons, Zombies, Husks, or Zombie Villagers
  don't attack you.
* Strays don't shoot arrows at you.
* Spiders or Cave Spiders don't attack you regardless of the light
  level.

In addition to that,
* Adult cows become hostile once you attack them. You can't leash
  angry cows of course.
* Adult pigs, rabbits, skeleton horses, and bats become hostile too.
* The same goes for untamed donkeys, horses, and mules. Also you can't
  tame them when they are angered.

There are a few exceptions:
* Wolves still attack sheep and rabbits. They will starve otherwise...


## Tested on
* MCPE v0.16.0


## Known issues
* **Mobs spawned before applying the behavior pack do not behave
  correctly,** which can not be fixed.
* Guardians or Elder Guardians cannot be made neutral. They act
  strangely when `minecraft:behavior.hurt_by_target` is applied.
* Angry pigs are still rideable. This is weird but there seems not to
  be a way around.


## How to build
1. Install the following tools:
 * GNU Autoconf
 * GNU Automake
 * GNU Make
 * [yamljs](https://www.npmjs.com/package/yamljs)
 * Info-Zip [Zip](http://www.info-zip.org/Zip.html)
2. Run `./Build`.
3. Now there should be `mcpe-neutralism-addon-*.mcpack` under
   `_build/src/`.

## Author
PHO &lt;pho [...] cielonegro.org&gt;


## License
[CC0](https://creativecommons.org/share-your-work/public-domain/cc0/)
“No Rights Reserved”
