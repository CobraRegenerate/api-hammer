# Assets to create for api-hammer

## logo.png вЂ” 256x256, transparent, dark theme
🔨 Neon shield/gear motif matching $api-hammer$ brand color. See master prompt in _shared docs.

## banner.png вЂ” 1280x640, background #0d1117
Large bold title $api-hammer$, subtitle gray #8b949e, thin gradient line #00ff9dв†’#bc8cff.

## screenshots/main.png вЂ” 1280x800
Request builder — method, URL, headers, JSON body with linting

## screenshots/settings.png вЂ” 1280x800
Collections sidebar — nested folders with env switcher

## screenshots/results.png вЂ” 1280x800
Response viewer — pretty JSON with search and timing

## gifs/demo.gif вЂ” 800x500, 8s, 12fps, <8MB
1. Open app, 2. click main action, 3. status turns green, 4. toggle a feature, 5. return.
ffmpeg: -vf "fps=12,scale=800:-1:flags=lanczos,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse"