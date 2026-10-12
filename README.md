# Reverb downloads

Official Mac beta downloads for [Reverb](https://getreverb.app).

[Download the Mac beta DMG](https://github.com/cennixAI/reverb-downloads/releases/download/v0.1.3/Reverb-0.1.3-macos-arm64.dmg) · [Release notes and checksums](https://github.com/cennixAI/reverb-downloads/releases/tag/v0.1.3)

## Install

1. Open the DMG and drag **Reverb** into **Applications**.
2. Open Reverb from Applications, then eject the disk image.
3. Allow Microphone and Accessibility in Reverb’s setup dashboard.

Requires Apple silicon and macOS 14+. Parakeet speech recognition and Riva’s voice are included. Local dictation needs no API key or separate model download. First launch prepares the local models and can take several seconds.

Reverb has two modes: free local Dictate, and Pilot for brief answers, web search, Mac tasks and connected apps. Pilot uses your OpenAI key; computer control additionally uses your TypeSafe key. Enable Pilot in General and configure your own credentials in Connections. Google Workspace, Notion and Slack currently use advanced access-token setup stored in Keychain; Apple tools need macOS permissions and configured accounts. Public one-click OAuth sign-in is not available yet. Connected-app writes are reviewed before execution. Cloud features require internet and may incur usage fees. An optional local language model for advanced rewriting or local chat is not included.

This beta app is not Developer ID signed or notarized. macOS may require **Open Anyway** in Privacy & Security. See the release notes for setup and privacy details.

This repository distributes app downloads only. No private application source, personal credentials or user settings are included.
