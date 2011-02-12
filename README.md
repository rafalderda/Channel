# Synopsis <a name="Synopsis"></a>

This is a plugin for [PS3 Media Server](http://code.google.com/p/ps3mediaserver/) (PMS) that allows you to browse
various online wb tv channels.

# Installation <a name="Install"></a>

* download the [Channels jar file](https://github.com/downloads/SharkHunter/Channel/tv_plug.jar) and place it in the PMS `plugins` directory
* download the [Channels files](https://github.com/SharkHunter/Channel/tree/master/channels) you need and place them in a new directory.
* you must also download [PMSEncoder scripts](https://github.com/SharkHunter/Channel/tree/master/scripts). 
* shut down PMS; open `PMS.conf` in a text editor; and add Channel specific configuration see below. 
* restart PMS

## Upgrading <a name="Upgrade"></a>

To upgrade to a new version of the plugin, simply replace the old jar file in the `plugins` directory with the [new version](https://github.com/downloads/SharkHunter/GSPMS/gs_plugin.jar) and restart PMS.

## Uninstalling <a name="Uninstall"></a>

To uninstall Channels, remove the jar file from the `plugins` directory and restart PMS. Also remove any 
.ch files.

## Configuration <a name="Configuration"></a>

The Channel plugin has the following configuration options all should be entered in the PMS.conf file:

* channels.path - The path to were the plugin will look for the channel files (.ch). (For example c:\\gs_data)
  This should normally be set to something.

* channeld.poll - The number of milliseconds tbetween the plugin checks for new .ch files. 

## Writing .ch files <a name="Write .ch files"></a>
For instructions on how to write [.ch files](https://github.com/SharkHunter/Channel/blob/master/README)