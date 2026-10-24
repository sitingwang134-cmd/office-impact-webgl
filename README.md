# Office Impact - Unity WebGL

Play: https://sitingwang134-cmd.github.io/office-impact-webgl/

Complete HTML, WebAssembly engine, models, textures and audio are included in the numbered release archive parts. GitHub Pages automatically verifies and extracts the archive before publishing. No Unity installation or API key is needed to play.

To run locally:

```sh
cat game.tar.gz.part* > game.tar.gz
tar -xzf game.tar.gz
python3 -m http.server 8088
```

Then open http://localhost:8088/ in a desktop browser. Drag the head back and release to launch. Five levels, expression changes, collision pop effects, randomized voices and background music are included.
