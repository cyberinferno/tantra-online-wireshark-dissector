# Tantra Online Wireshark Dissector

Wireshark dissector which shows tantra online packet types exchanged between server and game client.

Most Kathana 5 packet type opcodes have been defined by referring to the leaked Kathana 3 C++ source code. Unknown packet types will be added to the dissector in the future as and when it has been identified.

## Installation

* Update tantra server ports at the end of the `tantra-dissector.lua` file if needed.
* Copy `tantra-dissector.lua` to Wireshark plugin directory (To locate plugin folder refer [this link](https://www.wireshark.org/docs/wsug_html_chunked/ChPluginFolders.html) ).
* If Wireshark is already running then open `Analyze` option dropdown and click on `Reload Lua Plugins` to load the plugin.