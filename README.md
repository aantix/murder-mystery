# Murder Mystery

A simple mobile web app for playing the playground game "Murder Mystery" — no referee needed.

## How the Game Works

This is a tag-based game played by kids on a playground.

1. Each player taps their name on the app to secretly find out if they are the **murderer** or not.
2. Players go out onto the playground. The murderer's job is to **tag** other participants one by one — without anyone figuring out who they are.
3. When someone is tagged by the murderer, they **sit down** where they were tagged to "play dead."
4. If a participant thinks they know who the murderer is, they call a **meeting**. If they guess wrong, the incorrect guesser is out. If they guess correctly, the murderer is caught and a new round starts.
5. If the murderer is the last one standing, the **murderer wins**.

## Why This App Exists

Normally, someone has to volunteer to pick the murderer — which means that person can't play. With this app, the computer picks randomly, so **everyone gets to play**.

## Using the App

- **Settings** — Enter player names, one per line. Names are saved so you don't have to re-enter them each time.
- **Reveal** — Each player taps their name to privately see whether they are the murderer. Once revealed, the card is locked so it can't be peeked at again.
- **New Round** — Resets all cards and randomly picks a new murderer.

## Hosting

The app is a single HTML file with no dependencies. Open `index.html` directly in a browser, or host it on GitHub Pages for easy access from any phone.
