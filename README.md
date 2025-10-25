This addon is a fork of the EPGP addon from http://epgp.googlecode.com/
Find the origin discuss forum [here](http://groups.google.com/group/epgp-discuss)


# Improvements

- Fixed the decay functionality: 
    - Now decay is performed with a 1s tick in between operations to avoid server rate limit when setting the guild notes
- Fixed min EP/GP values
    - The guild note values now reflect exactly the values of EPGP that a player has. This means that the initial EP/GP value will always be considered for the priority. E.g: if `@min_ep: 1000` then Player Notes: `1000,1000`
- Added a filter in the EPGP dialog to show only players that have EP or GP different than the minimum
    - In order to reduce noise of the EPGP list when clicking to "show all" (sometimes to award or gp people with toons in guild but currenly playing on outsieders) this extra filter will come in hand, only showing relevant data

- Can link external toons to in guild toons
    - Lootmaster ML UI now shows prio for external toons linked and allow distribution of loot by giving GP to the linked in guild member
    - Externals shows in the roaster (/epgp) with their main toons
    - Externals are included in the Mass EP awards
    - Externals can be GPed and EPed with commands and dialog actions
    - Commands to link externals, unlink, and show all externals linked


# Instalation 

- Downlad the zip [here](https://github.com/Thrashattack/dfc_epgp/archive/refs/heads/main.zip). Extract all contents into the Addons Folder.

