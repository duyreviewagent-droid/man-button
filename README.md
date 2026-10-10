# MAN

A big red button that says MAN. Click it (or press Space / Enter / M) and it plays the song.

- `web/index.html` is the whole app. `web/song.m4a` is the audio from IMG_0451.MOV (12.1 s).
- `mac/build.sh` builds `MAN.app`, which plays offline over the `man://` scheme.
- Test flags: `MAN.app/Contents/MacOS/MAN --windowed --query "auto=1&dbg=1" --shot out.png --delay 4`

## Online
Static site on Render from `render.yaml` (repo github.com/duyreviewagent-droid/man-button).
First deploy: open https://render.com/deploy?repo=https://github.com/duyreviewagent-droid/man-button and click Apply.
After that, every push to main redeploys.
