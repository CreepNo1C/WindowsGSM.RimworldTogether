# WindowsGSM.RimworldTogether
WindowsGSM Plugin that provides a Rimworld Together Dedicated Server

# Dedicated server info
At the moment the Server version is hardcoded to version 25.1.2.1. If you want to install a newer version you need to edit the downloadlink
in the Rimworld.cs at line 152 or update manually after installation.

```ruby
using (var webClient = new WebClient())
            {
                await webClient.DownloadFileTaskAsync($"https://github.com/Byte-Nova/Rimworld-Together/releases/download/25.1.2.1/win-x64.zip", Functions.ServerPath.GetServersServerFiles(_serverData.ServerID, "win-x64.zip"));
            }
```


## WindowsGSM Installation: 
1. Download  WindowsGSM https://windowsgsm.com/ 
2. Create a Folder at a Location you wan't all Server to be Installed and Run.
4. Drag WindowsGSM.Exe into previoulsy created folder and execute it.

## Plugin Installation:
1. Download [latest](https://github.com/ohmcodes/WindowsGSM.Satisfactory/releases/latest) release
2. Extract then Move **Rimworld.cs** folder to **plugins** folder
  a. OR Press on the Puzzle Icon in the left bottom side and install this plugin by navigating to it and select the Zip File.
4. Click **[RELOAD PLUGINS]** button or restart WindowsGSM
5. Navigate "Servers" and Click "Install Game Server" and find "Rimworld Together Dedicated Server [Rimworld.cs]


### Official Documentation
🗃️ Rimworld Together mod [https://steamcommunity.com/sharedfiles/filedetails/?id=3005289691](https://steamcommunity.com/sharedfiles/filedetails/?id=3005289691)<br/>
🗃️ Rimworld Together Server [https://github.com/Byte-Nova/Rimworld-Together/wiki](https://github.com/Byte-Nova/Rimworld-Together/wiki)

### The Game
🕹️ Official Site [https://rimworldgame.com/](https://rimworldgame.com/)<br/>
🕹️ Steam Site [https://rimworldgame.com/](https://store.steampowered.com/app/294100/RimWorld/)
