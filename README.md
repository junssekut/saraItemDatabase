### saraItemDatabase

---

ItemDatabase v4.18

Growtopia decoded item database via items.dat, created with modified version of GrowtopiaNoobs' items.dat decoder.
Only available to use it on LUA programming language. If you need help implementing this, feels free to dm me at discord junssekut#4964 or join my [discord server](https://dsc.gg/machseeman).

## How To Use

> Add this code inside your script (online fetch):
```lua
    --- Fetch the item database.
    local ItemDatabase = assert(load(request('GET', 'https://raw.githubusercontent.com/junssekut/saraItemDatabase/main/ItemDatabase.lua'))())

    --- Get item name from item id.
    ItemDatabase[4584] --- Pepper Tree
    ItemDatabase[4585] --- Pepper Tree Seed
```

> Add this code inside your script if you want it offline or locally:
```lua
    --- Replace 'ItemDatabase' with the name of your database file, of course you need 
    --- to download the file first and place it in the same folder as Pandora located.
    local ItemDatabase = require('ItemDatabase')

    --- Get item name from item id.
    ItemDatabase[4584] --- Pepper Tree
    ItemDatabase[4585] --- Pepper Tree Seed
```
