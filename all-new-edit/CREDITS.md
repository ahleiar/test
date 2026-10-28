# All-new full edit — sources and production notes

The film is 2:55, 1920×1080 at 24 fps, with the complete five-act narration and supplied contact details. No original user photos, video clips or original audio were used in this version.

## Visuals

Thirteen new scene plates were generated with OpenAI image generation: Cape Town, Lisbon, South African wildlife, a training pool, a commercial office, Dublin, St. Louis, wine logistics, Arizona, a meeting, financial work, rugby and a commercial building. They are illustrative reconstructions, not documentary recordings of Alexander, his workplaces or his actual trips. Anonymous people in illustrations are not presented as Alexander.

The plates were animated using MiDaS depth estimation and a Three.js virtual camera. They are animated image-based scenes, not newly captured live-action footage. Some moves were rendered at 12 fps and temporally blended to 24 fps for smooth, subtle camera motion. The globe was rendered in Three.js at 24 fps, with public-domain Natural Earth country data.

## Stock inserts

Two legacy Coverr-source samples were obtained from publicly hosted demonstration projects and used as short illustrative inserts:

- Handyman: https://raw.githubusercontent.com/JettTech/homepageVid/master/assets/images/MP4/Handyman.mp4 — the source HTML and README credit Coverr.
- Love Coding: https://raw.githubusercontent.com/jvining/Video-Hero-Image-Coverr-Demo/master/mov/Love-Coding.mp4 — the source HTML credits Coverr.

Legacy CC0 reference: https://github.com/neutraltone/awesome-stock-resources#videos. Download hashes and provenance are in `stock_sources.json`. Current provider terms can differ from historical distributions; no ownership of the underlying stock is claimed. These inserts illustrate general work/problem-solving, not a claim that the depicted work was performed by Alexander.

## Narration and sound

The complete supplied script was read using Kokoro v1.0, voice `am_michael`, through kokoro-onnx. This is a generic synthetic narrator, not Alexander’s voice and not a clone of his voice. St. Louis and the dollar amount were expanded for spoken pronunciation; the full script content was retained.

- Kokoro model: Apache 2.0, official model release at https://github.com/thewh1teagle/kokoro-onnx/releases/tag/model-files-v1.1
- kokoro-onnx: MIT, https://github.com/thewh1teagle/kokoro-onnx
- MiDaS: MIT, https://github.com/isl-org/MiDaS
- Three.js: MIT, https://github.com/mrdoob/three.js
- Natural Earth: public-domain country data, https://github.com/nvkelso/natural-earth-vector

The piano/pad/percussion score and transition effects were synthesized specifically for this edit. No third-party song or music sample was used. The score was ducked under the voice and the final audio loudness measured after export.

Typography uses the cloud machine’s installed OpenAI Sans. Font files are not redistributed.

## Captions and verification

Optional English captions are embedded in the MP4 and available separately. Sentence boundaries come from the actual synthesis clips; short caption-group timings are estimated within each sentence. Captions are not burned over the film.

All 61 picture segments matched their intended frame counts. The final export has 4,200 frames and passed a complete audio/video decode with `-xerror`. `Validation.json` reports final dimensions, duration, loudness and file hash.
