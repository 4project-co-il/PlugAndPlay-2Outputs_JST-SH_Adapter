# PlugAndPlay: Output module with JST-SH connectors as an adapter for other devices
This is the repository with the files for PlugAndPlay output module with JST-SH connectors on output lines.

That module have 2x 3pin JST-SH connectors, each allowing control of Pololu's single relay with JST-SH connector for easy connection.
The module also have 1x 4pin JST-SH connector, allowing control of Pololu's double relay with JST-SH connector.
The 2x 3pin connectors and 1x 4pin connector are connected in parallel to the same INT lines from the PnP connector, so they should not be used together.
The PnP Power Connector is used to provide the voltage needed for the Pololu's relays. Generally 5V or 12V, depending on the relay you use.
PnP INT lines are used to control the relay's EN lines.

