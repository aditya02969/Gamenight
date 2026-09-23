# Game Night

Nine games in one installable web app: chess, carrom, ludo and more. No build step, no backend, no accounts.

- **Chess** with the full rules and a computer opponent
- **Ludo** for 2 to 4 players
- **Carrom** with physics, a computer opponent and a solo challenge
- **Target Rush**, a fast aiming game with difficulty levels and a scoreboard
- **Tic-Tac-Toe**, a quick classic with a computer opponent
- **Heart Match**, a memory pairs game for two with a fun prize on the line
- Three games for two: **Love Game** (guess each other, truths, dares and a love meter), **Love Dice** (roll for a sweet little action), and the **Date Night Wheel** (spin for a date idea)

You can play on one device, online with a friend using a room code, against a bot, or solo for a high score.

## Play it

Open the hosted page in a browser. To install it like an app:

- **Android (Chrome):** menu (three dots), then **Install app**.
- **iPhone (Safari):** Share, then **Add to Home Screen**.

After the first load it also works offline for on-device play. Online rooms need an internet connection.

## The games

### Chess
- Two players: on one device (with an optional computer opponent) or online with a friend.
- Legal move checking, check, checkmate, stalemate, castling, en passant and promotion.
- Draws by insufficient material, the fifty-move rule and threefold repetition.
- Move list, captured pieces, resign, and a flip-board button.
- The computer opponent searches a few moves ahead (more on Hard) and weighs material and piece placement — Easy also throws in the occasional beginner mistake.

### Ludo
- 2 to 4 players. Any seat can be a bot.
- Roll a 6 to bring a token out. A 6, a capture, or getting a token home gives another roll. Three sixes in a row lose the turn.
- Landing on a lone opponent on a plain square sends it back. Start squares and starred squares are safe.
- You need an exact roll to finish. The first player with all four tokens home wins.

### Carrom
- Slide the striker along your baseline to any spot from one red circle to the other. Then put your finger **anywhere on the board**, drag, and release. You shoot in the opposite direction of your drag, so the striker can be right at the edge and you still have room to aim.
- While you aim, a dotted guide shows where the striker will first hit a coin and which way that coin will go. If the shot hits the cushion first, it also shows the bounce (bank shot).
- Shallow angles along the edges work too. Only shots backward or dead sideways are refused, as in real carrom.
- **Versus:** white plays white coins, black plays black coins. Each coin potted scores 1 point for its owner, and the queen scores 3 for whoever pots it. Potting your own coin or the queen earns another shot. If your striker falls in, you lose a point and your turn. The game ends when the board is empty, or when 20 shots in a row pot nothing (the higher score wins).
- **Bot:** Easy, Medium or Hard. The bot tries many shots in a simulation and picks the best one.
- **Solo challenge:** a limited number of shots (fewer on harder levels). Coins are worth 100, the queen 300, all multiplied by the difficulty. Clearing the board gives a bonus for unused shots. Scores go on the scoreboard.
- Choose 3, 6 or 9 coins per side.

### Target Rush
- Hit as many targets as you can in 30 seconds. Centred, quick hits and long combos score more. A miss breaks your combo and costs points.
- **Easy:** one big target. **Medium:** two smaller targets. **Hard:** three small moving targets. Points are multiplied by 1, 2 or 3.
- **Solo:** saves your best scores to the scoreboard.
- **Multiplayer:** everyone plays the same set of targets (generated from a shared seed) and the highest score wins. On one device players take turns. Online, each player starts their own run and scores are compared at the end.

### Couple games
Three games made for two people, on one phone or on two phones online.

#### Love Game
Ten rounds:

- **Know me:** one of you answers a question about yourself in secret, and the other guesses. A match earns 3 hearts.
- **Would you rather:** you both pick, then compare. The same pick earns 3 hearts, different picks earn 1.
- **Truth:** answer a sweet question out loud, and your partner gives it 1 to 3 hearts.
- **Dare:** do a small, wholesome dare, and your partner gives it 1 to 3 hearts. You can skip a dare.

At the end you get a **love meter** percentage and a short message. On one phone the game asks you to pass the phone before every secret question. Online, each of you answers on your own phone. Answers are hidden on screen until the reveal, but the game state is shared between the phones, so it relies on trust and is just for fun.


#### Love Dice
Roll two dice for a sweet little action (like "give a shoulder rub") and a way to do it (like "while looking into their eyes"). Your partner rates it 1 to 3 hearts. Ten rounds, then see your sweetness score.

#### Date Night Wheel
Pick a mood (cozy at home, out and about, adventurous, or extra sweet) and spin a wheel of date ideas. Keep spinning, and save the ones you like to a shared list you can come back to. This one is local only, played together on one device.

### Tic-Tac-Toe
A classic, best of as many rounds as you like. Scores carry across rounds, and who goes first alternates. Play against a friend on one device, online with a room code, or against a computer opponent on Easy, Medium or Hard — Hard never loses.

### Heart Match
A memory pairs game for two. Take turns flipping two cards; a match keeps your turn, a miss passes it. Whoever finds more pairs at the end picks a small prize, drawn randomly each game (movie night, a massage, who makes the tea, and so on). Choose Easy, Medium or Hard for how many cards are on the board.

## Look and feel

Boards have a bit of texture instead of flat color: the Carrom table has a faint wood grain, the chess squares, Tic-Tac-Toe cells and Heart Match cards have a subtle fine-grain surface, the Ludo board and Target Rush arena floor have a soft mottled texture, and panels and cards throughout have a light grain overlay — all aiming for a more tactile, less flat feel without slowing anything down.

The whole app uses one combined colour theme: the **Deep Space** navy, indigo, cyan and violet, lit by the **On Fire** orange, red and pale yellow. Panels are frosted glass over a slowly drifting gradient. The same palette is used on the menus, the chess board (cream and indigo squares), the Ludo board, the Carrom board (fire-coloured wood in a navy frame with a cyan striker), the Target Rush arena, and the Tic-Tac-Toe and Heart Match boards.

Small animations include cards rising in, buttons that press and glow, a pop on the chess piece you just moved, a pulsing dot on whose turn it is, score numbers that pop, confetti on a win, and hearts in the Love Game. The background stops drifting while a fast game animation is running, to keep it smooth, and all animation turns off if the device is set to reduce motion.

## Names

Every mode lets you set names:

- **This device:** type a name for each player before starting.
- **Solo and online:** a "Your name" box on the setup screen. Guests can type their name on the home screen before joining, and anyone can change their name in the lobby with **Save name**.

## Online play

1. One player opens a game, picks **Online room**, and taps **Create room**. They get a 5-letter code.
2. Friends open the app, type the code under **Join a friend's room**, and tap **Join room**. An invite link (`?room=CODE`) also works.
3. The host taps **Start game**.

Notes:

- Ludo, Carrom, Tic-Tac-Toe and Chess (in local pass-and-play only) can fill a seat with a bot. Chess online, Love Game and Love Dice need the other player to join first. Target Rush drops empty seats. Heart Match and the Date Night Wheel do not use bots.
- If a player disconnects, they can rejoin with the same code in the same browser tab. In Ludo a bot plays for them until they return.
- Online rooms use peer-to-peer connections (WebRTC through [PeerJS](https://peerjs.com)). The free public PeerJS signalling server helps the phones find each other, and the game data then goes directly between them.
- Some networks block direct connections (certain school or office Wi-Fi). Mobile data or home Wi-Fi usually works.
- This is built for playing with friends. A determined player could tamper with their own copy of the page.

## Sound

All sounds are generated by the browser, so there are no audio files to host and they work offline: piece taps and check chimes in chess, a dice rattle and token pops in Ludo, shot thwacks, coin clacks and pocket thunks in Carrom, and hit pings, countdown beeps and misses in Target Rush. There are short win, lose and draw jingles, and online games play a soft chime when it becomes your turn.

- Use the speaker button in the top right corner to mute or unmute. The choice is remembered on that device.
- Phones only allow sound after the first tap on the page, so the first tap turns it on.
- On iPhone, the silent-mode switch can mute web sound.

## Scoreboard

The scoreboard keeps the top 10 solo scores for **Target Rush** and **Carrom Solo** on each difficulty. Scores are saved in your browser on that device only. Set your name on the home screen first, since it is saved with each score.

## Host it yourself (GitHub Pages)

1. Create a repo and upload these files to the top level (not inside a folder): `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `apple-touch-icon.png`, and this `README.md`.
2. Go to **Settings**, then **Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and `/ (root)`, then **Save**.
3. After a minute or two your site is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

Any static host works too (Netlify, Cloudflare Pages, and so on). It must be served over **https** for installing and offline mode to work.

To update a live copy, upload the new files over the old ones and reload the page twice, since the service worker keeps a cached copy.

## Files

| File | What it does |
| --- | --- |
| `index.html` | The whole app: rules, screens, styling and networking in one file |
| `manifest.webmanifest` | App name, colours and icons for installing |
| `sw.js` | Service worker for offline play (bump `CACHE` when you change files) |
| `icon-*.png`, `apple-touch-icon.png` | App icons |

## How it works

- **Single file, no dependencies** except PeerJS (loaded from a CDN) and two Google Fonts. Sound uses the browser's built-in Web Audio. Everything else is plain HTML, CSS and JavaScript.
- **Rules are separate from the screens.** The first `<script>` block holds pure game logic with no page code. Each game has a function that takes the current state, an action and the player's seat, and returns the new state or an error.
- **Online:** the host runs the rules and sends the full game state to every guest after each move. Guests only send their actions. This keeps everyone in sync.
- **Colours:** the page colours come from CSS variables, and the game boards read one small palette table in the script, so the look can be changed in two places.
- **Chess:** the move generator matches the standard reference move counts (perft) for the start position and four well-known tricky positions; the bot was run in hundreds of bot-vs-bot games at each difficulty to check it never crashes, stalls, or returns an illegal move, and that Hard reliably beats Easy.
- **Carrom drawing:** the board and the coins are painted once and then stamped each frame, motion is interpolated between physics steps, and the canvas size follows the screen, so it stays smooth on phones.
- **Carrom:** the physics is deterministic, so every device replays a shot the same way. The host's result is the source of truth and every board snaps to it when the animation ends. Bots test many candidate shots in the same simulation and choose the best.
- **Target Rush races:** targets come from a seeded random generator, so the same seed gives every player the same sequence.

## Limits

- No accounts and no shared online scoreboard. Solo scores live on each device.
- Rooms only last while the host keeps the page open.
- No computer opponent for chess, and no draw offers.
- Sounds are simple synthesized effects, not recordings of real wood and plastic.
- Tested in a simulated browser. Please try the online modes on real devices and report anything odd.

## Credits

Built with plain JavaScript and [PeerJS](https://peerjs.com). Fonts: DM Sans and Fraunces from Google Fonts.
