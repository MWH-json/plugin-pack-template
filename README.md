# Plugin Pack Template
Start making your own Plugin Pack for Mini World with this blank template!

# Steps:
1. Download the template from the [Releases](https://github.com/MWH-json/plugin-pack-template/releases) Page.
2. Extract it and move it to the Mini World main mods folder:
    * Android is ```miniplay>com.playmini.miniworld>data>mods```
    * Windows is ```C:\Users\YOUR-USERNAME\AppData\Roaming\miniworlddata410\data\mods```
3. Open Mini World, go to **Singleplayer**>Plugin Library>Plugin Pack and the pack should be there!

# Make the pack an independent Plugin Pack
When you download it you can see that we made it and it is separated from the others, this is because we use our own UUID and we fill up some properties, here is how you can make it too:

* In the ```pack_manifest.json``` there is some properties you'll need to fill up to make this happen:
    1. ```author``` and all his variants are your username.
    2. ```authoruin``` its your UID, it starts with 1000 at the beggining.
    3. ```uuid``` its the **Universal Unique Identifier**, you can get one from this sites: 
    * [UUIDGenerator](https://www.uuidgenerator.net/) 
    * [Feik's UUID Generator (using the same API as uuidgenerator)](https://feiku.gq/uuid)
    
# Adding plugins

To add your own plugins open your game go to ```Singleplayer>Plugin Library>Plugin Pack>YOUR PACK NAME>Edit```, 
#### Disclaimer: do not save the description, title and chart image inside the plugin pack editor, it will corrupt it.


# Custom Logo

If you want to add a custom logo just edit our logo with your things and then rename it again to ```logo.png_``` *the ```.png_``` there its important, do not remove it*
