<p align="center">
<img src="./assets/logo.png" width='80' alt='Click for larger image'/>
 <h1 align="center">Steam Game Idler</h1>
 <p align="center">Idle any game in your Steam library. All you need is your Steam username or ID64. No password, token, or any other login information needed.</p>
 <p align="center">Built with NextJS + Tauri.</p>
</p>
  <p align="center">
    <a href="https://github.com/probablyraging/steam-game-idler/graphs/contributors">
      <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/probablyraging/steam-game-idler" />
    </a>
    <a href="https://github.com/probablyraging/steam-game-idler/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/probablyraging/steam-game-idler?color=0088ff" />
    </a>
    <a href="https://github.com/probablyraging/steam-game-idler/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/probablyraging/steam-game-idler?color=0088ff" />
    </a>
  </p>

<div align="center">
  <img src="./assets/example.png" width='700' alt='Click for larger image'/>
</div>

# Portable[¹](https://github.com/ProbablyRaging/steam-game-idler#notes)
Download the latest `portable` release from [Releases](https://github.com/ProbablyRaging/steam-game-idler/releases)

# Installer
Download the latest `installer` release from [Releases](https://github.com/ProbablyRaging/steam-game-idler/releases)

*Bundled with dependencies + automatic updates*

# Build It Yourself
1. Clone the repoistory
```
git clone https://github.com/ProbablyRaging/steam-game-idler.git
```
2. Install dependencies
```
npm install
```
3. Build the app
```
npm run tauri build
```
4. Check the console output for build directory *(usually `/src-tauri/target/release/bundle`)* 

# Usage
1. Enter your Steam username or [SteamID64](https://steamid.io/)
2. Make sure Steam is running
3. Click one or more games that you want to idle
4. That's it, it's that simple

## Notes
¹ *[WebView2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/?form=MA13LH#download-section) required. On Windows 10 (Version 1803 and later with all updates applied) and Windows 11, the WebView2 runtime is distributed as part of the operating system. Use the MSI Installer if you're unsure, as it comes bundled with all dependencies.*