# BuildGraph-SteamDeploy
## Description
A very basic buildgraph script for deploying Unreal Engine games to Steam via Horde.

If there are any features you'd like to see added, feel free to open an issue or send in a PR.

## Usage
To use this script with Horde, you must:
* Put your Steamworks install in your engine depot. This includes the upload token.
  * If you have a larger team which you don't want to have upload permissions, it shouldn't be too hard to copy "config.vdf" from a network share or local folder (that is only on your build machines), to the engine at publish-time.
* You should have three VDF files for your app, one pointing to each depot for upload. (E.g., app_0000000_Windows.vdf, app_0000000_Mac.vdf)
* I recommend putting your app's steam ID as the default value, so that you're not typing it out every time.
