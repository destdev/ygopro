## ygopro
A script engine for "yu-gi-oh!" and sample gui

###Keys:
* ESC: Minimize the window.
* A: Holding down this buton will let the system stop at every timing.
* S: Holding down this butoon will let the system skip every timing.
* R: Fix the font error.
* F1~F3: Show the cards in your grave, banished zone, extra deck.
* F5~F7: Show the cards in your opponent's grave, banished zone, extra deck.

###Sequence:
* Monster Zone: 1~5, starting from the left hand side.
* Spell & Trap Zone: 1~5, starting from the left hand side.
* Spell Zone: 6
* Pendulum Zone: 7~8, starting from the left hand side.
* The others: 1~n, starting from the bottom.

###Deck edit page:
* All numeric textboxs: They suuport >, =, <, >=, <= signs.
* Card name: Search card names and texts by default, and $foo will only search foo in card names.

### Command-line options:
* -j: Join the host in system.conf file.
* -d: Enter the deck edit page.
* -r: Enter the replay mode page.
* -s: Enter the single mode page.
* -efoo: Load foo as the extra database.

### Directories:
* pics: .jpg card images(177*254).
* pics\thumbnail: .jpg thumbnail images(44*64).
* script: .lua script files.
* textures: Other image files.
* deck: .ydk deck files.
* replay: .yrp replay files.
* expansions: *.cdb will be loaded as extra databaes.
