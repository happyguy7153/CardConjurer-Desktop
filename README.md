Made for Heitzey

# Card Conjurer Desktop

An unofficial Windows x64 desktop packaging of Card Conjurer, based on upstream snapshot [`2fcddba8966156d484cedf54d8214996748dd5e`](https://github.com/Investigamer/cardconjurer/tree/2fcddba8966156d484cedf54d8214996748dd5e).

Card Conjurer Desktop runs in its own Electron window. It does not require a separate browser or a Card Conjurer account.

## Features

- **Card Creator:** edit card details, choose available frames and visual options, add local artwork, and preview changes as you work.
- **Printing Tool:** arrange cards on print sheets and export them as PNG files. PDF support uses the online printing library.
- **Card lookup:** retrieve card information through Scryfall and use remote image URLs when online.
- **Creative tools:** Ask Urza 2.0, Phyrexian Generator, Gallery, and Theme Editor.
- **Local saves and exports:** save cards and settings on your PC; export card and print-sheet PNG files locally.
- **Windows setup:** per-user installation, Start Menu shortcuts, an optional Desktop shortcut, and an uninstaller. Saved cards and settings remain after uninstall.

## Internet connection

Card editing, bundled frames, local artwork, saving, card PNG export, and print-sheet PNG export work locally. Scryfall lookup, remote images, and the Printing Tool's PDF library require an internet connection.

## Download and install

Release **0.0.1** has been packaged as a standalone Windows installer. Its full installer is about 2.87 GiB. The GitHub repository and release assets have not been created or uploaded yet; the split download parts and one-file online bootstrapper are also still pending. Download instructions will be added when those files are ready.

## Data locations

- Saved cards, drafts, and settings: `%APPDATA%\Card Conjurer Desktop`
- PNG and PDF exports: the Windows Downloads folder by default

Saved user data is kept when the application is uninstalled.

## Notice

This is an unsigned, unofficial build and is not affiliated with Wizards of the Coast or the upstream maintainers. The pinned upstream snapshot has no license file, and some artwork may have separate rights. Verify redistribution permissions before publishing or redistributing the application.

See [`RELEASE-DESCRIPTION.md`](RELEASE-DESCRIPTION.md) for the release feature summary and [`release-manifest.json`](release-manifest.json) for the package metadata.
