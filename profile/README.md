# Atmoscheme

[atmoscheme.com](https://atmoscheme.com) is an interactive 3D globe, weather atlas, and ambient geoplaylist player built with Vue 3, CesiumJS, Web Audio API, and NestJS.

The app itself and its geoplaylist catalog live in private repositories. Standalone pieces from the graphics, GIS, and audio codebases are published here under MIT:

- [cesium-scheme-preloader](https://github.com/atmoscheme/cesium-scheme-preloader): ENU grid and topographic contour shader overlay while Cesium tiles load
- [cesium-tour-kit](https://github.com/atmoscheme/cesium-tour-kit): three-phase geodesic camera flights, Slippy-tile preloader, route slicing, and water-surface styling
- [osm-ring-sampler](https://github.com/atmoscheme/osm-ring-sampler): concentric ring POI sampling (5 to 200 km) and raceway polyline stitching over Overpass and Nominatim
- [web-audio-sidechain](https://github.com/atmoscheme/web-audio-sidechain): Web Audio RMS sidechain ducking and narration queue with SpeechSynthesis fallback
- [piper-tts-nest-starter](https://github.com/atmoscheme/piper-tts-nest-starter): self-hosted Piper TTS + NestJS 11 API with SHA-256 WAV cache and RIFF duration headers
- [vue-14seg](https://github.com/atmoscheme/vue-14seg): Vue 3 14-segment SVG display with diacritic folding

Maintained by [@rromanoff-gh](https://github.com/rromanoff-gh). Contact: [atmoscheme@gmail.com](mailto:atmoscheme@gmail.com) | [t.me/atmoscheme](https://t.me/atmoscheme).