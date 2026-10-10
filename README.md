# MAN

A big red button that says MAN. Click it (or press Space / Enter / M) and it plays the song.

- `web/index.html` is the whole app. `web/song.m4a` is the audio from IMG_0451.MOV (12.1 s).
- `mac/build.sh` builds `MAN.app`, which plays offline over the `man://` scheme.
- Test flags: `MAN.app/Contents/MacOS/MAN --windowed --query "auto=1&dbg=1" --shot out.png --delay 4`
