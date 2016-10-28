# Neutralism
An MCPE behavior pack which makes hostile mobs always spawn in neutral.
Unless you aggravate them,
* Blazes don't shoot fireballs at you.
* Creepers don't explode.
* Spiders or Cave Spiders don't attack you regardless of the light level.

In addition to that,
* Adult cows become hostile once you attack them. You can't leash angry cows of course.
* The same goes for donkeys. Also you can't tame them when they're angered.


## Tested on
* MCPE v0.16.0


## Known problems
* Guardians cannot be made neutral. They act strangely when `minecraft:behavior.hurt_by_target` is applied.


## How to build
1. Install the following tools:
 * GNU Autoconf
 * GNU Automake
 * GNU Make
 * [yamljs](https://www.npmjs.com/package/yamljs)
 * Info-Zip [Zip](http://www.info-zip.org/Zip.html)
2. Run `./Build`.
3. Now there should be `mcpe-neutralism-addon-*.mcpack` under `_build/src/`.

## Author
PHO &lt;pho [...] cielonegro.org&gt;


## License
[CC0](https://creativecommons.org/share-your-work/public-domain/cc0/) “No Rights Reserved”
