# Who am I?
I work for a large tech company in Infosec, specifically Incident Response.  I also have a lot of highly nerdy hobbies like retro gaming and 3d printing.

# Useful tools
- [SSH Autoproxy](https://github.com/rmonk/ssh-autoproxy): Automatically connect over SSH JumpHosts when needed and provide SOCKS endpoints for browsers.  It's like FoxyProxy for everything!
- [Hey Whisper](https://github.com/rmonk/hey-whisper): A Whisper voice-to-text powered tool to take daily notes.
- [Antigravity Appimage](https://github.com/rmonk/antigravity-appimage): Autobuild of the latest Google Antigravity release as an Appimage with updates enabled.
- [Birdbuddy Downloader](https://github.com/rmonk/birdbuddy-downloader): Downloads and indexes photos and videos from all the Birdbuddy cameras in your account.
- [Klipper Notifier](https://github.com/rmonk/klipper-notifier): Uses getotifyapp to provide live updates of a 3d printer's print status on iOS devices.
- [HubitatSyslogDriver](https://github.com/rmonk/hubitatSyslogDriver): Advanced Hubitat driver to stream hub logs to a syslog-compatible endpoint.
- [Romm Retroarch Sync](https://github.com/rmonk/romm-retroarch-sync): Sync your local flatpak Retroarch games/saves/savestates with your Romm server.
- [AVML](https://github.com/rmonk/avml): Fork of MS's AVML Linux memory image tool with ability to stream the image over an SSH session
- [Site-Monitor](https://github.com/rmonk/site-monitor): A simple tool to monitor and alert on sites that are down, like Uptime Kuma

## Hardened images
I have a number of *-hardened repos here.  These are automatically rebuilt container images for several common projects which are behind on their security updates, mostly when it comes to dependencies.  With the massive uptick in CVEs over the past few months (As of writing in Nov 2026, several critical vulnerabilities in major packages THIS WEEK) the biggest flaw in containerized workloads is coming to fruition.

Since I don't have the money for Aikido's auto-patching toolkit, I have claude rebuild from upstream with updated container images with as many patched versions as I can.  These rebuild usually weekly.
