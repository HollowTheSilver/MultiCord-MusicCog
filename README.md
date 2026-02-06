# MultiCord Music Cog

Music playback for Discord with queue management, YouTube support, and voice controls.

## Features

- **Voice Control**: Join/leave voice channels
- **Playback**: Play, pause, resume, stop, skip
- **Queue Management**: Queue display, now playing
- **Volume Control**: Adjustable 0-100%

## Quick Start

```bash
# Install FFmpeg first (required)
# Windows: Download from https://ffmpeg.org/download.html
# Linux: sudo apt install ffmpeg
# macOS: brew install ffmpeg

# Install into a bot
multicord bot cog add music my-bot

# Restart the bot to load
multicord bot run my-bot
```

## Commands

### Voice
- `!join` - Join your voice channel
- `!leave` - Leave voice channel

### Playback
- `!play <song>` - Play or add to queue
- `!pause` - Pause playback
- `!resume` - Resume playback
- `!stop` - Stop and clear queue
- `!skip` - Skip current song

### Queue
- `!queue` - Show queue
- `!nowplaying` - Show current song

### Controls
- `!volume <0-100>` - Set volume

## Configuration

Configure in your bot's `config.toml`:

```toml
[music]
default_volume = 50
max_queue_size = 100
max_song_duration_seconds = 600
```

## Requirements

- **FFmpeg** - Audio processing (system install)
- **yt-dlp** - YouTube extraction (in requirements.txt)
- **PyNaCl** - Voice support (in requirements.txt)

## Required Permissions

- Connect, Speak (voice)
- Send Messages, Embed Links

## License

MIT License - see [LICENSE](LICENSE)
