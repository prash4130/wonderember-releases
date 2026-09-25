# Wonderember

A handwriting app for learning. Write and draw on your iPad with Apple Pencil. Claude reads the page and answers in red handwriting. The Mac runs the app. The iPad opens it in Safari.

This is the first public build. It's a beta.

**[Download the latest release](https://github.com/prash4130/wonderember-releases/releases/latest)**

## Requirements

- Apple-silicon Mac, macOS 13 or newer
- iPad with Apple Pencil and Safari
- Both devices on the same Wi-Fi
- Claude Code installed and signed in with a paid Claude plan (Pro, Max, Team, or Enterprise)

## Install

1. Open the DMG and drag Wonderember into your Applications folder.
2. Open Terminal and run `claude` to make sure Claude Code is installed and you're signed in. If you don't have it yet, see [Anthropic's install instructions](https://code.claude.com/docs/en/setup).
3. Open Wonderember. It checks for Claude Code and tells you if something is missing.
4. Scan the QR code on your Mac with your iPad camera. The page opens in Safari.

## Verify the download

```
shasum -a 256 Wonderember-0.1.0.dmg
```

The checksum for v0.1.0 is `1e9a7626f5c59cc0969ecf4e46b612f92fce9a03f84d3524c5271cbe20bfad03`. A matching SHA-256 file is attached to each release.

## Help

Questions or bugs? Email support@wonderember.com.

Website: [wonderember.com](https://wonderember.com)

## About this repo

This repo holds releases only. The app source code is not here.
