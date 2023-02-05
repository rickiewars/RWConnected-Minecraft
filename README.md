# RWConnected Minecraft server
Deze repositorie is puur bedoeld voor de spelers in mijn Minecraft server.

# Aangeraden launcher
AtLauncher wordt als beste launcher beoordeeld over het algemeen maar maakt vooral mod-management makkelijk.
Atlauncher is optioneel maar maakt het mogelijk om een release van deze repository direct te importeren.
Als alternatief kan je ook zelf de benodigde mods downloaden.

# Installatie:
- Download en installeer [ATLauncher](https://atlauncher.com/downloads).
- Start ATLauncher, ga naar accounts, klik op `Login with Microsoft` en login met je Minecraft account.
- Op de [releases](https://github.com/rickiewars/RWConnected-Minecraft/releases) pagina, download het `RWConnected.<version>.quilt.mrpack` bestand.
- In ATLauncher, ga naar `Instances` en links bovenin, klik op `Import`.
- Klik op `Browse`, navigeer naar de map waar je het `.mrpack` bestand hebt gedownload en importeer het bestand.
- Geef de instance een naam en klik op Install.
- Na de installatie voltooid is, kan je het spel starten door op `play` te klikken.

## Updates
ATLauncher maakt het zeer gemakkelijk om mods te updaten.
- In ATLauncher, open het `Instances` tab.
- Onder de instance die je wilt updaten, klik op `edit mods`.
- In het nieuwe scherm, selecteer alle mods met het bovenste vinkje en klik op `Check for updates`.
- ATLauncher zal nu elke mod checken en als nieuwe updates beschikbaar zijn, jou de optie geven een nieuwe update te selecteren en installeren.
  - Zorg voordat je echt de mod updated, dat de versie compatible is met je huidige minecraft versie.

# Mod list
In principe kan je in de Minecraft server zonder mods maar voor de beste ervaringen raad ik een aantal mods aan.
De gehele lijst met mods kan je downloaden vanuit de releases.
Mocht je de mods handmatig willen installeren, zijn alle mods opgenoemd in drie verschillende categorieën.

## Modding API
Als modloader gebuik ik [Quilt](https://quiltmc.org/en/).
Quilt is de opvolger van Fabric en ondersteund (bijna) alle Fabric mods.
Steeds meer mods stoppen support voor Fabric en gaan over naar Quilt als basis API.
Dat is de reden dat ik Quilt heb gekozen als modloader.

Houd er mee rekening dat in Quilt, de Fabric API niet wordt ondersteund!
Wanneer een mod afhankelijk is van de Fabric API, kan de [Quilted Fabric API (QFAPI) and Quilt Standard Libraries (QSL)](https://modrinth.com/mod/qsl) worden gebruikt in de plaats daarvan.

## Additive mod pack
Als basis heb ik de Additive Mod pack gebruikt.
Het doel van de mod pack is om betere performance uit minecraft te halen zonder vanilla functionaliteit te veranderen.
Daarnaast zorgt de pack voor betere compatibilliteit met Optifine shaders en texture-packs

De volgende mods zijn meegeleverd in de Additive mod pack:
- animatica -> Animated textures
- c2me-fabric -> Parrallell chunk generation (experimental)
- capes -> optifine capes
- cem -> Custom entity models
- cit-resewn -> Custom item textures
- entityculling -> Skips rendering entities that are not visible
- entitytexturefeatures -> Add biome-dependant textures to entities
- exordium -> Lower framerate for GUI elements.
- fabric-language-kotlin -> Dependancy of some mods
- fabricskyboxes-interop -> Compatibillity for optifine skies
- fabricskyboxes -> Dependancy of fabricskyboxes-interop
- fastload -> Faster world loading
- ferrite-core -> Reduce memory usage
- immediatelyfast -> Speed up rendering
- indium -> Compatibillity mod for Sodium
- iris -> Shaders
- krypton -> Optimize the network stack
- lambdynamiclights -> Eluminates items in your hand
- lazydfu -> Optimalization mod which delays unneccesary work untill needed.
- lithium -> General purpose optimallization mod
- memoryleakfix -> Fixes multiple memory leaks in Minecraft both on server and client
- modmenu -> Add mod menu for various mods.
- moreculling -> Same as entityculling but for multiple things
- puzzle -> Compatibillity mod for optifine
- qsl -> Quilt API (replaces fabric-api if quilt is used)
- reeses-sodium-options -> Better UI for Sodium
- smoothboot-fabric -> Optimizes loading by setting thread options
- sodium-extra -> Add optimalization and optifine-Compatibillity features which are not yet included to sodium
- sodium -> Optimizes rendering engine on client-side of minecraft for more fps
- starlight -> Rewrites lightning engine
- vmp-fabric -> Optimalization for higher player counts without sacrifficing vanilla behaviour
- yacl -> Successor to cloth config api and is a configuration screen generator. 
- zoomify -> Add zoom key

## Functionele mods
De volgende lijst met mods voegd functionaliteit toe zonder vanilla functionaliteit te veranderen.
De belangrijkste mod is de "Simple Voice Chat" mod, welke voice-chat ingame mogelijk maakt.
De overige mods zijn optioneel en kunnen uitgeschakeld worden wanneer nodig.

- Simple Voice Chat -> Mod that enables voice chat on a server.
- shulkerboxtooltip -> Add tooltip to show what is inside a shulkerbox
- ItemSwapper -> Better inventory management based on the concept of Xisumavoid
  - See full explaination video from Xisumavoid on [Youtube](https://www.youtube.com/watch?v=hTuWMqj5RFE)
  - Shulkerbox functionality requires mod to be installed on the server (which needs to be discussed first)
  - Custom collections are supported
- mousewheelie -> Add various mouse wheel actions like inventory sorting, item refilling, etc.
  - Changes in the settings may be required.

## Visuele mods
De volgende mods zijn alleen visueel en veranderen niks aan de controls.
Presence foodsteps en Resounding zijn geluidsmods.
Schakel gerust de mods die je niet wilt gebruiken uit.

- Falling Leaves -> Add leaves falling effect under trees
- Presence Footsteps -> Dynamic sounds when walking on various materials
- BetterF3 -> Sorts the F3 menu in a more clear way
- Illuminations -> Add beautiful illuminations to Minecraft 
  - (waiting for 1.19.3 release)
- Resounding -> Successor to sound physics fabric. Adds ambiant sound physics to the game like an echo in caves.
  - (waiting for 1.19.3 release)
- Blur (Fabric) -> Add a blur to background when inventory is open.

# TODO:
- Wachten op update voor Illuminations
- Wachten op update voor Resounding
- Configuratie guide
- Links naar individuele mods
