## Trappist Weather
- Trappist weather app which will show weather using a weather api.
- No weather api logic yet, just ui for demo purposes

## Error in Linux Systems:

#### Fix for Error: node:internal/fs/watchers:252 throw error;^ | Error: ENOSPC: System limit for number of file watchers reached,

`echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p`