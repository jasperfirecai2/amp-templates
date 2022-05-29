
# NOTICE REGARDING TMODLOADER64

tModLoader64 is a third-party wrapper for tmodloader that lets it use more RAM than 4GB.
The server implementation is less stable than the client, and depends on monodevelop for linux machines.
*DO NOT INSTALL MONODEVELOP ON YOUR MACHINE RUNNING AMP*
This can break AMP entirely and is hard to clean.

You will likely NOT NEED this for the server, because most of the RAM usage comes from TEXTURES that the server doesn't load.
If you know you need this, and know how to install monodevelop in a container, you can use tmodloader64.

## Notice regarding tModLoader

It might occur that you get the message 'Your Steam account does not have access to this server' when updating the game through steam. This is because tModLoader exists as a 'game' on the store is a special way.  This can by fixed by:

1. Aquiring [tModLoader](https://store.steampowered.com/app/1281930/tModLoader/) in your Steam library (it's free!)
2. Starting a download of tModLoader from your library
3. Accepting their Terms of Service

## Setting up independent generics

To set up your generic template, you will need to download the .kvp, config and metaconfig that are meant for the version you want (e.g. tModLoader.kvp, tModLoaderconfig.json and tModLoadermetaconfig.json).
updatesources.json is purly for readability.
tmodloader64 uses the tmodloader files for everything except the kvp.
tshock uses terraria config files

Put these files in your /generictemplates folder of ADS. File manager -> ADS01/Plugins/ADSModule/GenericTemplates
