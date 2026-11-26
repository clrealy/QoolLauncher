<p align="center">
  <img src="docs/qool_icon.png" width="160" alt="Qool icon"/>
</p>

# Qool

**The Quest menu, but Qool again.**

Qool is a launcher for Meta Quest that brings back the clean, simple feel of the old Oculus Quest menu, without the clutter of the new Navigator UI.

Qool is a fork of [Lightning Launcher](https://github.com/threethan/LightningLauncher) by **threethan**. All credit for the original launcher goes to them.

## Status

🚧 Early work in progress. Right now Qool is Lightning Launcher with a new name, icon and app ID. The classic Quest 1 style restyle is coming next.

## Install

1. Download `QoolLauncher.apk` from [Releases](https://github.com/clrealy/QoolLauncher/releases).
2. Install it on your Quest (SideQuest, or open the APK with the Quest's Package Installer).
3. Open **Qool** from your app library.

Qool uses its own app ID (`com.clrealy.qool`), so it can be installed alongside Lightning Launcher.

## Build

Open the `Launcher` folder in Android Studio and build the **sideload** variant, or run:

```sh
cd Launcher
./gradlew assembleSideloadRelease
```

## Roadmap

- [x] Rename to Qool, new icon, new app ID
- [ ] Classic Oculus Quest 1 style layout (floating panel, rounded tiles, bottom bar with clock and battery)
- [ ] Classic-style themes and wallpapers
- [ ] First release on GitHub and SideQuest

## License

Qool is licensed under the **GNU GPL v3**, the same license as Lightning Launcher. See [LICENSE](LICENSE).

The original Lightning Launcher README is kept in [README.upstream.md](README.upstream.md).

Qool is not affiliated with or endorsed by Meta or Oculus.
