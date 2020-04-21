# Minecraft Updated

This is a copy of Home Assistant's built-in Minecraft server sensor, with some bugs and limitations fixed.

Current operation should be relatively similar to the built-in integration, though the IDs generated will be different.

Minecraft servers allow players to play the sandbox video game Minecraft by Mojang AB online or via a local area network with other players.
The Minecraft Server integration lets you retrieve information from a Minecraft server (Java edition) within Home Assistant.

##### The server must be version 1.7 or higher, since older versions don't expose any information.

## Configuration via the frontend

In the settings go to Integrations, click on the + sign to add an integration and click on "Minecraft Server (Updated)".
After completing the configuration flow, the Minecraft Server integration will be available.
Entity IDs will be generated based on the name you enter for the server.

## Binary sensors
This integration provides a binary sensor for the following information from a Minecraft server:
- Connection status
 
## Sensors
This integration provides sensors for the following information from a Minecraft server:
- Latency time
- Version
- Protocol version
- Number of online players (player names are available in state attributes)
- Number of maximum players
