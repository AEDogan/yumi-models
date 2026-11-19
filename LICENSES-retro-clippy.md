# Original Clippit / Clippy animation data

Source: https://github.com/clippyjs/clippy.js/tree/master/agents/Clippy

Downloaded 2026-10-22. `agent.json` is the unchanged JSON data enclosed by
`clippy.ready('Clippy', ...)` in the upstream `agent.js`; `map.png` is unchanged.
43 animations, original frame sizes, durations, weighted branches and exit branches.

Clippit artwork and animation data belong to Microsoft. This integration does not
claim ownership or grant a new license to those assets. See the upstream project
for its code license. The Python player is a separate implementation.

Yumi plays these sprites locally without a speech balloon, JavaScript runtime,
sound effects, or external network requests. AI speech uses Yumi's existing voice
transport. There is no synthesized lip sync or VRM motion applied to Clippit.

## License notes (checked 2026-11-19)

- Code: clippy.js and OpenClippy (https://github.com/lennystepn-hue/openclippy) are MIT-licensed. OpenClippy
  takes its sprites from clippyjs, the same source as these files. Our `agent.json`/`map.png` come from clippy.js (above).
- Artwork: the MIT license covers the code, not the Clippit drawings. OpenClippy's FAQ says "Microsoft open-sourced"
  the Office Assistant; the repository it links (github.com/thebeebs/OfficeAssistant) is a personal account, has no
  LICENSE file and says the code is "available to anyone for one day only". So no Microsoft license for the artwork
  was found; the artwork copyright is still Microsoft's.
- Yumi distributes the retro package free of charge, with this notice, as clippy.js and OpenClippy do.
