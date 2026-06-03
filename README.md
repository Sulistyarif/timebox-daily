# timebox-daily

A simple daily project rotation timer. Stay focused, move on time.

## Features

- Rotate through up to 6 projects with a countdown timer per slot
- Visual ring timer with warning indicator at 5 minutes remaining
- Audio beep notification when time is up
- Mark projects as done manually or automatically
- Jump to any project by tapping the queue list
- Editable project names directly in the app
- Configurable slot duration (5–120 minutes)
- Persistent state via localStorage — safe to refresh
- Screen wake lock support (iPad / mobile)

## Deploy

### Vercel (recommended)

1. Fork or clone this repo
2. Connect to [Vercel](https://vercel.com)
3. Deploy — no build step needed, it's a single HTML file
4. Open the URL from any browser, including iPad Safari

### Manual

Just open `index.html` in any modern browser — no dependencies, no build tools.

## Usage

1. Tap **Edit** to set your project names
2. Tap **Start** to begin the timer
3. Tap **Next →** to mark current project done and move to the next
4. Tap the ⚙ stat chip at the bottom to change slot duration
5. Tap any row in the queue to jump to that project

## Stack

Plain HTML + CSS + JavaScript. No frameworks, no dependencies.

## License

MIT
