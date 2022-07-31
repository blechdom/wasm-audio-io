# WASM AUDIO APP

1. `npm i`
1. `cd wasm-audio`
1. `wasm-pack build --target web`
   (builds wasm pack in `./pkg`)
1. `cp -R ./wasm-audio/pkg ./public/wasm-audio` (without pkg directory)
1. `cd ..`
1. `yarn start`
