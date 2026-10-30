# WaveSurfer.js system tool

A window-owning app can call `await host.tools.createWaveSurfer(options)` to
create a WaveSurfer instance in its own DOM. The instance is destroyed when the
app view closes; apps may destroy it sooner. Use `loadBlob()` with data obtained
through the account file mirror. The installed library is lazy-loaded and has
no standalone window. Run `npm ci --prefix apps/system/wavesurfer --ignore-scripts`
before building.
