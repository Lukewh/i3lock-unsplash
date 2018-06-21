# i3lock-unsplash
Load a random image every hour from upsplash when locking your screen.

## Requirements
- Python3
- Unsplash client-id: https://unsplash.com/oauth/applications
- i3lock

## How do?
Clone the repo/ copy the files and update the variables.
Add the following to your i3 config:

```
bindsym $mod+<your key combo for locking the screen> exec python3 <path to lock.py>
```

I keep everything in `~/.config`
