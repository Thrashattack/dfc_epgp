This addon is a fork of the EPGP addon from http://epgp.googlecode.com/
Find the origin discuss forum [here](http://groups.google.com/group/epgp-discuss)


# Improvements

- Fixed the decay functionality: 
    - Now decay is performed with a 1s tick in between operations to avoid server rate limit when setting the guild notes
    - Decay will not reduce the players amount of epgp below the `@min_ep` and `@base_gp` configs
    - Decay skips completely players that have exactly `@min_ep` of EP and `@base_gp` of GP reducing the number of operations and optimizing time
    
- Fixed min EP/GP values 
    - The guild note values now reflect exactly the values of EPGP that a player has. This means that the initial EP/GP value will always be considered for the priority. E.g: if `@min_ep: 1000` and `@base_gp: 1000` then Player Notes: `1000,1000`
    
- Added a filter in the EPGP dialog to show only players that have EP or GP different than the minimum 
    - In order to reduce noise of the EPGP list when clicking to "show all" this extra filter will come in hand, only showing players with relevant data

- Can link external toons to in guild toons 
    - Lootmaster ML UI now shows the prio of the main in-guild toon for the external toons and allow distribution of loot by giving GP to the linked in-guild toon
    - Externals shows in the roaster (/epgp) with their main in-guild toons
    - Externals are included in the Mass EP awards and the EP goes to their in-guild linked toons
    - Externals can be GPed and EPed with commands and dialog actions, and the values goes to their in-guild linked toons
    - Commands to link externals, unlink, and show all externals linked
    - Commands to sync externals across officers


# Instalation 

- Downlad the zip [here](https://github.com/Thrashattack/dfc_epgp/archive/refs/heads/main.zip). Extract all contents into the Addons Folder.

