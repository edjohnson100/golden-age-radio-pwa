# Golden Age Radio

A retro 1950s Old Time Radio listening room and Progressive Web App (PWA) streaming public-domain broadcasts from the [Internet Archive](https://archive.org/details/oldtimeradio).

## Two Machines, One Archive

- **The Living Room Dial (`mantel.html`)** — A 1950s walnut mantel clock-radio with a live Roman-numeral analog clock, glowing 6E5 magic-eye tuning tube, and AM frequency dial (`600–1580 KC`).
- **The Diner Selector (`jukebox.html`)** — A chrome & backlit 1950s booth jukebox with a spinning vinyl record, tonearm, and red-and-cream title strips (`A1–I4`).

Both players share the exact same 41 starter episodes and stream hundreds more live from **22 Internet Archive collections** across 9 stations:

| Letter | Station | Frequency | Highlights |
| :---: | :--- | :---: | :--- |
| **A** | Comedy | 600 KC | *Fibber McGee and Molly*, *The Jack Benny Program*, *The Mel Blanc Show* |
| **B** | Detective | 720 KC | *Dragnet*, *Yours Truly, Johnny Dollar* |
| **C** | Horror & Supernatural | 840 KC | *The Sealed Book*, *Inner Sanctum Mysteries*, *The Weird Circle*, *Creeps by Night* |
| **D** | Westerns & Adventure | 960 KC | *Frontier Gentleman*, *Escape* |
| **E** | Drama | 1080 KC | *Suspense*, *Gunsmoke* |
| **F** | Holiday | 1225 KC | *An Old Fashioned Christmas*, *500 OTR Christmas Shows* |
| **G** | Big Band & Swing | 1340 KC | *Big Band Remotes* (Benny Goodman, Count Basie, Duke Ellington, Ella Fitzgerald) |
| **H** | Sci-Fi | 1460 KC | *X Minus One*, *Dimension X* |
| **I** | History | 1580 KC | *You Are There*, *American History Through The Eyes Of Radio*, *Stroke of Fate* |

## Features

- **Instant Playback & Live Catalog**: Starter episodes play immediately while the full catalog loads in the background from the Internet Archive.
- **Group-Preserving Shuffle**: Shuffles shows and episodes while keeping multi-part stories (`Part 1`, `Part 2`, etc.) together in order.
- **Browse / Full Catalog**: Search by show, episode title, or year and filter by station or series with live match counts.
- **Installable PWA**: Works offline for the app shell, with `MediaSession` lock-screen and Bluetooth controls on mobile and desktop.

## Install as an App (PWA)

- **iPhone / iPad (Safari)**: Tap **Share** → **Add to Home Screen**.
- **Android (Chrome)**: Tap **Install app** (or **⋮ → Add to Home screen**).
- **Windows / macOS (Chrome or Edge)**: Click the **Install** icon in the address bar.

## Credits, Audio Rights & License

- **Code License**: The HTML, CSS, and JavaScript in this repository are created by Ed Johnson with a Gemini AI assist and released under the [MIT License](LICENSE).
- **Audio Streams & Rights**: This app does not host or redistribute audio files. All broadcasts stream directly from the [Internet Archive](https://archive.org/details/oldtimeradio) (including collections preserved by the Old Time Radio Researchers Group) under their respective public-domain or Archive-listed terms. Each player links back to the underlying Archive item page; if you spot a broken stream or have a rights concern about a specific Archive listing, please open an issue in this repository or refer to the linked Archive item.
- **Typography & Artwork**: Fonts (`Bebas Neue`, `Inter`, `Pacifico`, `Playfair Display`) are loaded via Google Fonts under their respective open-source licenses. All cabinet/jukebox CSS artwork and app icons are original to this project, with no third-party hardware trademarks.
- **Privacy**: Runs 100% client-side with no backend, analytics, cookies, or tracking—only `localStorage` in your browser to remember volume, station, and shuffle preferences.
