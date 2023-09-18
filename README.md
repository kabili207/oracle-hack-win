# ZoraGen WPF ![Build status](https://github.com/kabili207/zoragen-wpf/actions/workflows/dotnet-desktop.yml/badge.svg)

A generator and decoder for the password system used in the Legend of Zelda Oracle of Ages and Oracle of Seasons games.
Built using the [ZoraSharp](https://github.com/kabili207/zora-sharp) library.

### Features
 * Decodes game and ring secrets
 * Generates game, ring, and memory secrets
 * Allows the user to save the game information for later use
 
### Download
 * [Stable Release](https://github.com/kabili207/zoragen-wpf/releases/latest)

### TODO
 * Include a debugging screen to get raw information about secrets

### Special Thanks
 * Paulygon - Created the [original secret generator](http://home.earthlink.net/~paul3/zeldagbc.html) way back in 2001
 * 39ster - Rediscovered [how to decode game secrets](http://www.gamefaqs.com/boards/472313-the-legend-of-zelda-oracle-of-ages/66934363) using paulygon's program
 * [LunarCookies](https://github.com/LunarCookies) - Discovered the correct cipher and checksum logic used to generate secrets

### License
ZoraGen WPF is licensed under the GNU General Public License version 3.

ZoraGen WPF makes use of the following libraries:
 * [ZoraSharp](https://github.com/kabili207/zora-sharp), licensed under the GNU Lesser General Public License version 3
 * [SemVer](https://github.com/maxhauser/semver), licensed under the MIT License


