# abstract-nonsense
Random Ideas for Haskell Things that Should Exist

- Library of plain attoparsec parsers for all parts of the XML spec.
    - Fast enough.
    - No FFI.
    - Not opinionated about streaming framework.
    - No dependencies
    - Useful for XML-ish things.
- [Objective-C runtime interface](https://github.com/traviswhitaker/objc-runtime)
    - With [Cocoa bindings](https://github.com/traviswhitaker/cocoa)
        - How to automatically generate these?
- Nice interface for [PortAudio](http://portaudio.com/docs/v19-doxydocs/api_overview.html)
    - Existing ones are unmaintianed.
- Complete, nice interface for [ffmpeg](https://ffmpeg.org/doxygen/trunk/index.html)
    - [ffmpeg-light](https://hackage.haskell.org/package/ffmpeg-light) is nice
      but is missing loads of features.
    - Should be possible to implement most of something like mplayer.
- [Shadertoy](https://www.shadertoy.com/), but native.
- A package like [gl](https://hackage.haskell.org/package/gl) but for EGL.
- A full [GLFW](https://github.com/glfw/glfw) clone in pure Haskell.
    - The Rust community is good about making a good thing from scratch instead
      of compromising by calling out to C. Haskell should be more like this.
- Something like [Vega](https://vega.github.io/vega/), but rendered outside the
browser and nice to use from GHCi.
