<div align="center">
  <img src="./assets/logo.png" width='80' alt='Click for larger image' />
  <h1 align="center">Steam Game Idler - Lite</h1>
  <p align="center">Idle any game in your Steam library. All you need is a game ID. No password, token, or any other login information needed.</p>
<p align="center">
  <img src="https://img.shields.io/github/downloads/probablyraging/steam-game-idler/total?style=for-the-badge&logo=github&color=137eb5" alt="Downloads" />
  <img src="https://img.shields.io/github/issues/probablyraging/steam-game-idler?style=for-the-badge&logo=github&color=137eb5" alt="Issues" />
  <img src="https://img.shields.io/github/issues-pr/probablyraging/steam-game-idler?style=for-the-badge&logo=github&color=137eb5" alt="Issues" />
  <img src="https://img.shields.io/github/contributors/probablyraging/steam-game-idler?style=for-the-badge&logo=github&color=137eb5" alt="GitHub Contributors" />
</p>
</div>
<div align="center" style="margin-top: 10px;">
  <img src="./assets/example.png" width='700' alt='Click for larger image' />
</div>

# Download
All the latest windows supported versions of SGI can be downloaded from the [releases page](https://github.com/probablyraging/steam-game-idler/releases)<br/>
Looking for a linux/macos supported version? Take a look at the [CLI + Web UI](https://github.com/probablyraging/steam-game-idler/tree/cli-webui) branch

### Options
* **[Portable](https://github.com/probablyraging/steam-game-idler)**: `.exe` file, works on most win10/win11 systems *(check the note below)*
* **[Installer](https://github.com/probablyraging/steam-game-idler)**: `.msi` file, includes all dependencies and automatic updates, **recommended** for all windows versions
* **[Lite](https://github.com/probablyraging/steam-game-idler/tree/lite)**: simplified version with minimal UI, only requires a game ID, no Steam profile name or ID64 needed
* **[CLI + Web UI](https://github.com/probablyraging/steam-game-idler/tree/cli-webui)**: windows, linux, and macos supported version with a command-line interface and/or web interface

> [!Note]
> ***PORTABLE** requires the [WebView2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/?form=MA13LH#download-section) runtime which is distributed as part of the OS on Win10 (version 1803 and later with all updates applied) and Win11. Use the MSI installer if you're unsure, as it comes bundled with all dependencies.*

# Build It Yourself
1. **Clone**: `git clone -b lite https://github.com/probablyraging/steam-game-idler.git`
2. **Install deps**: `cd ./steam-game-idler` & `npm install`
3. **Build idler**: `msbuild ./idler-csharp/idler.csproj`
	* Creates `/libs` dir with packaged libraries in `/src-tauri`
4. **Build app**: `npm run tauri build`
5. **Check console output** for build dir *(usually `/src-tauri/target/release/bundle`)*

# Usage
*The Steam desktop app needs to be running*
1. Enter one or more game IDs
    * Enter multiple game IDs seperated by a comma to idle multiple games at once *(e.g. 460, 22100, 5677)*
2. That's it!

# License
All versions of SGI are licensed under the **[GPL-3.0 License](./LICENSE)**