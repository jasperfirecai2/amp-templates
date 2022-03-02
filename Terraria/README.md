
# NOTICE REGARDING TMODLOADER64

tModLoader64 is a third-party wrapper for tmodloader that lets it use more RAM than 4GB.
The server implementation is less stable than the client, and depends on monodevelop for linux machines.
*DO NOT INSTALL MONODEVELOP ON YOUR MACHINE RUNNING AMP*
This can break AMP entirely and is hard to clean.

You will likely NOT NEED this for the server, because most of the RAM usage comes from TEXTURES that the server doesn't load.
If you know you need this, and know how to install monodevelop in a container, you can use tmodloader64.

## Setting up independent generics

To set up your generic template, you will need to download the .kvp, config, configtemplate and metaconfig that are meant for the version you want (e.g. tModLoader.kvp, tModLoaderconfig.json, tModLoadermetaconfig.json and tModLoaderconfigtemplate.txt).
updatesources.json is purly for readability.
tmodloader64 uses the tmodloader files for everything except the kvp.
