# Alexander Leiar — five-act production V3

This revision follows the five-act script supplied by Alexander. It retains his water polo, South African wildlife and identifiable personal moments. Generic phone travel/airport/city coverage and photographed slides are assigned stock-replacement slots.

This is an **offline edit assembly with marked missing material**, not a completed film. No stock clips have been downloaded or licensed yet, and no synthetic voice or stock actor stands in for Alexander.

## Review assets

- `Personal_Footage_Review.mp4` — about 20 seconds demonstrating retained real wildlife and both water polo sources in the approved motion style. It is an excerpt, not the full narrative.
- `Travel_Map_Preview.mp4` — Africa / Europe / Asia map motion study.
- `Route_Motion_Preview.mp4` — South Africa → Ireland → St. Louis professional-experience transition.
- `Contact_Card_Preview.mp4` — the actual supplied name, email and LinkedIn profile.
- `Alexander_Leiar_V3_Sequence_Review.mp4` — retained-footage excerpt, professional route and contact card in one review reel; the later graphic studies are intentionally silent.

## Editable project

`Alexander_Leiar_V3.otio` is an OpenTimelineIO edit assembly with linked 1080p personal-media renders, a reference-audio track, motion assets, six explicitly named recording pickups and visible stock placeholders. `Media/Original_Draft.mp4` retains the supplied source. `Timeline_Validation.json` records the project checks.

Use an editor/importer supporting OTIO; relink the included `Media` folder if the editor requires absolute paths. Keep the project file next to `Media`. The OTIO file was serialized, reopened and checked for valid file references and source ranges; import in a specific desktop NLE has not been tested in this cloud environment.

The primary picture track includes visible `RECORDING REQUIRED` and `STOCK SHOT REQUIRED` slates. They are intentional review markers, never final-film graphics. The reference audio is not an audio-verified final script performance. Missing new recordings are explicitly represented as missing audio references. Retiming after the actual takes arrive is expected.

The Act 4 overlay track contains the requested **Adaptability**, **Relationships** and **Global Perspective** phrase animations. Their planning positions need to follow the new performance in the final conform.

## Script and recordings

- `SCRIPT.md` — the complete approved script, with Greek/LinkedIn spelling normalized.
- `TELEPROMPTER.txt` — a reading copy.
- `RECORDING_GUIDE.md` — six clip/pickup names, exact line references and practical capture instructions.
- `RECORDING_COVERAGE.md` — available old audio versus new wording and missing camera takes.
- `assembly.json` and `timing_markers.json` — line IDs, planning timing and slot assignments. Timing estimates are not final performance timing.

Record R01A/R01B, R04 and R05 to camera. R03A/R03B are wording pickups for the exact new script. A complete fresh voice read of Acts 2 and 3 is also useful if Alexander wants a consistent performance throughout.

## Picture selection

`PICTURE_PLAN.md`, `retained_media.json` and `stock_manifest.json` record the keep/replace decisions. Stock entries currently contain search subjects and source-search URLs, not cleared clip selections. Each final clip still needs its creator, exact clip URL and actual license recorded.

Pexels and Mixkit continue to return proxy HTTP 403 from this running environment. The necessary domains are saved in the environment configuration draft: `pexels.com`, `www.pexels.com`, `videos.pexels.com`, `images.pexels.com`, `mixkit.co`, `assets.mixkit.co`. Applying/saving the relevant settings and publishing the environment is a user-facing operation; saving a draft did not activate access. Alternatively, supplied stock files with their source/license links can be conformed locally.

## Closing card

Alexander Leiar  
alexleiar@gmail.com  
https://www.linkedin.com/in/alex-leiar-395b1a415/

## Map source and rebuild

Maps use public-domain Natural Earth data. See `MAP_CREDITS.md`, `countries.geojson` and the upstream `natural-earth-readme.md`.

The project uses Python/Pillow and FFmpeg. OTIO generation uses `opentimelineio==0.18.1`. Motion scripts reference the cloud machine’s installed sans-serif fonts; change `FONT`/`REG` to your locally available fonts when rebuilding elsewhere. Rendered media and placeholder graphics are included, so ordinary editing does not require those fonts.

`graphics_v3.py` creates map/contact/recording-slot assets. `build_script.py` and `build_plan.py` retain the supplied script and slot structure. `build_timeline.py` assembles and validates the OTIO project. Source scripts also refer to earlier cloud intermediates when rebuilding linked personal renders; the included `Media/Own` renders and original draft are sufficient for editorial relinking without rebuilding them.
