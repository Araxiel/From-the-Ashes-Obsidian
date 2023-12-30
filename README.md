# From the Ashes Obsidian Vault
The Obsidian Vault associated with [From the Ashes](https://github.com/Araxiel/From-the-Ashes/), the steampunk, post-apocalpyse Victoria 3 mod.

# What is Obsidian?
[Obsidian](https://obsidian.md/) is a open-source note taking tool.

# What Plugins are used?
For core plugins easiest is to put the `core-plugins.json` file in the directory.  
For that purpose, in this gist are both the current `core-plugins.json` and `community-plugins.json`:  
https://gist.github.com/Araxiel/1fde2ab2ee53f7718176d1a81c2486ac

| Community Plugins |   	|
|------------------	|---	|
| dataview         	| Necessary 	|
| dbfolder         	| Necessary  	|
| obsidian-git      | Recommended  	|
| obsidian-redirect | Optional  	|
| metaedit        	| Optional  	|
| badges        	| Not Yet Used 	|

Settings for everything is essentially default.

## Why not simply have the `.obsidian` folder included in the repo?
Because on how obsidian-git works. It can only keep track of files within a folder within the vault, but not the `.obsidian` folder itself. While one could just ignore obsidian-git and instead source control the entire vault, this does mean one needs to constantly manually push backups of the design doc (and setting up auto-backups yourself is way above my skill level).