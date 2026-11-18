BotanyTrees – Port no oficial a Minecraft 26.3 (Fabric) + español

⚠️ Port no oficial. No está hecho ni respaldado por el autor original (Darkhax). No reportes errores de esta versión en las páginas oficiales del mod. ⚠️ Sin probar en el juego. Se verificó que los archivos JSON son válidos y que las versiones coinciden con lo publicado por Fabric y Mojang, pero no se cargó en Minecraft 26.3.

🇬🇧 English version below

🇪🇸 Español
Qué es

Complemento de Botany Pots que permite cultivar árboles y brotes dentro de las macetas, tanto para decorar como para montar una mini granja de madera. Incluye árboles de vanilla y de muchos otros mods.

Qué cambia respecto al original (1.21.1)
Actualizado para Minecraft 26.3 y Fabric.
Añadido el roble pálido (no existía en 1.21.1).
Traducción al español de la descripción del mod para Mod Menu (es_es, es_mx, es_ar, es_cl, es_uy, es_ve).
Se eliminaron las clases compiladas y los mixins vacíos del original, que eran para 1.21.1 y no funcionan en 26.x. El mod solo contiene datos (recetas y tablas de botín).
El resto de recetas y tablas de botín no se modificó.
Requisitos
Requisito	Versión
Minecraft	26.3
Java	25 o superior
Fabric Loader	0.20.1 o superior
Fabric API	0.165.0 o superior
Botany Pots	una versión compatible con 26.3
Bookshelf	una versión compatible con 26.3
Prickle	una versión compatible con 26.3

Importante: Botany Pots oficial (Darkhax) solo existe para 1.21.1. Hay un port no oficial para 26.1 y otro llamado "Botany Pots Renewed" para 26.2, pero no se confirmó ninguno para 26.3. Sin un Botany Pots compatible, este mod no hará nada.

Instalación
Instala Fabric Loader y Fabric API para 26.3.
Instala Botany Pots, Bookshelf y Prickle en versiones compatibles.
Copia botanytrees-fabric-26_3-26.3.0-es.jar en la carpeta mods.
Abre un mundo y planta un brote de árbol en una maceta con tierra.
Estructura del proyecto
fabric.mod.json                  Dependencias y metadatos (sin clases ni mixins)
pack.mcmeta                      Formato de datapack 121 (26.3)
assets/botanytrees/lang/         Traducciones (Mod Menu)
data/botanytrees/recipe/         Cultivos de cada árbol (por mod)
data/botanytrees/loot_table/     Drops de cada árbol
Generar el .jar

Comprime el contenido de la carpeta (no la carpeta) y renómbralo a .jar:

zip -r botanytrees-fabric-26_3-26.3.0-es.jar .
Problemas conocidos
Los ids de algunos mods compatibles (Aether, Biomes O' Plenty, etc.) pudieron cambiar en sus versiones para 26.x. Las recetas de mods que no estén instalados se ignoran.
No se añadieron los árboles nuevos de 26.3 (como el álamo del bosque moteado) porque no se conocen sus ids.
Si hay errores al cargar un mundo, revisa el log del juego.
Créditos y licencia
Mod original: Darkhax — https://github.com/Darkhax-Minecraft/BotanyTrees
Port a 26.3 y traducción al español: no oficiales.
Licencia: LGPL v2.1 (ver license_botanytrees.txt). Si redistribuyes una versión modificada, mantén la licencia y el crédito al autor original.
🇬🇧 English
What it is

An addon for Botany Pots that lets you grow trees and saplings inside pots, for decoration or as a mini wood farm. Includes vanilla trees and trees from many other mods.

Changes from the original (1.21.1)
Updated for Minecraft 26.3 on Fabric.
Added the pale oak tree (it didn't exist in 1.21.1).
Spanish translation of the mod description for Mod Menu (es_es, es_mx, es_ar, es_cl, es_uy, es_ve).
Removed the original's compiled classes and empty mixins, which targeted 1.21.1 and don't work on 26.x. The mod is data-only (recipes and loot tables).
All other recipes and loot tables are unchanged.
Requirements
Requirement	Version
Minecraft	26.3
Java	25 or higher
Fabric Loader	0.20.1 or higher
Fabric API	0.165.0 or higher
Botany Pots	a version compatible with 26.3
Bookshelf	a version compatible with 26.3
Prickle	a version compatible with 26.3

Important: the official Botany Pots (Darkhax) only exists for 1.21.1. There is an unofficial 26.1 port and a "Botany Pots Renewed" for 26.2, but neither was confirmed for 26.3. Without a compatible Botany Pots, this mod does nothing.

Installation
Install Fabric Loader and Fabric API for 26.3.
Install compatible versions of Botany Pots, Bookshelf and Prickle.
Drop botanytrees-fabric-26_3-26.3.0-es.jar into your mods folder.
Open a world and plant a tree sapling in a pot with soil.
Project layout
fabric.mod.json                  Dependencies and metadata (no classes or mixins)
pack.mcmeta                      Data pack format 121 (26.3)
assets/botanytrees/lang/         Translations (Mod Menu)
data/botanytrees/recipe/         Crop definition for each tree (per mod)
data/botanytrees/loot_table/     Drops for each tree
Building the .jar

Zip the contents of the folder (not the folder itself) and rename it to .jar:

zip -r botanytrees-fabric-26_3-26.3.0-es.jar .
Known issues
Block/item ids from some supported mods (Aether, Biomes O' Plenty, etc.) may have changed in their 26.x versions. Recipes for mods that aren't installed are skipped.
New 26.3 trees (such as the poplar from the dappled forest) were not added because their ids are unknown.
If a world fails to load, check the game log.
Credits and license
Original mod: Darkhax — https://github.com/Darkhax-Minecraft/BotanyTrees
26.3 port and Spanish translation: unofficial.
License: LGPL v2.1 (see license_botanytrees.txt). If you redistribute a modified version, keep the license and credit the original author.
