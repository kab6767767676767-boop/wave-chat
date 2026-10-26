# Wave — Chat with Friends

A pure client-side chat + rooms + mini-games app.

## Live Demo

After enabling GitHub Pages (Settings → Pages → Source: Deploy from branch `main` / root):

**https://kab6767767676767-boop.github.io/wave-chat/**

## Features
- Local accounts (username + password stored in browser localStorage)
- Contacts, people discovery, group rooms with shareable codes
- Real-time-ish messaging (polls + storage events across tabs)
- Local video call demo (your camera only)
- Mini-games with shared leaderboards: Tic-Tac-Toe, Memory, Word Scramble, Quick Math

## Offline
The entire app is a single HTML file. Once loaded (or saved offline), it works without a network connection. All data lives in the browser's `localStorage`.

Google Fonts will fall back to system fonts if offline.

## How multi-user works
Because everything is client-side, true multi-device sync requires everyone to use the **same browser origin** (same device/tabs work great via storage events). For real multi-user across devices you would need a backend (Firebase, Supabase, etc.).

## License
MIT – free to use and modify.
