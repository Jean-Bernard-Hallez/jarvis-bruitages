<!---
IMPORTANT
=========
This README.md is displayed in the WebStore as well as within Jarvis app
Please do not change the structure of this file
Fill-in Description, Usage & Author sections
Make sure to rename the [en] folder into the language code your plugin is written in (ex: fr, es, de, it...)
For multi-language plugin:
- clone the language directory and translate commands/functions.sh
- optionally write the Description / Usage sections in several languages
-->

## Description
Fait des bruitages avec des sonorisations différentes pour la même demande prononcé.
Dans cette installation il y a déja:  la vache, tarzan, siffle, R2D2, chien, chèvre... et à vous de l'enrichir

Voici comment le configurer avec ses propres bruitages:
La commande doit être "Fais" + "quelque chose", et le format des fichiers doivent obligatoirement:

- être au format " . wav "
- ils doivent être placés dans le répertoire:         ~/jarvis/plugins/jarvis-bruitage/             et là 2 cas de figures:

	* Vous n'avez qu'un son, on dit "Fais le bruit d'un claxon", le son est placé dans:              ~/jarvis/plugins/jarvis-bruitage/claxon.wav

	* Il y a plusieurs fichier wav, les sons du répertoire seront tirés au sort ! 
	peut-importe les noms mais ils doivent être dans le répertoire:                                ~/jarvis/plugins/jarvis-bruitage/bruitages/NOM DU BRUITAGE/FICHIERS X.WAV
								"NOM DU BRUITAGE"= dernier mot prononcé pour l'obtenir c'est le nom du répertoire ou sont stockées les sons .wav
	exemple pour différent claxon, si on dit "Fais le bruit d'un claxon", ca  doit être dans       ~/jarvis/plugins/jarvis-bruitage/claxon/son1.wav
               															      /peutimporte.wav
																      /bruit2.wav  
								     								       etc...

	

Voilà amusez-vous bien !

## Languages

* Français


## Usage
```
You: fais comme la chèvre
Jarvis (le bruit de la chèvre) (ici, il y a 11 sons différents à chaque fois tiré au sort)

You: fait le son de la guèpe
Jarvis: Aïe, je ne trouve pas le bruitage que tu me demandes, désolé.
```

## Author
[Jean-Bernard Hallez](https://github.com/Jean-Bernard-Hallez/jarvis-bruitages)

