<img align="left" src="logo/raudio_256x256.png" width=256>

- Forked for Windows + VS2022.

**raudio is simple and easy-to-use audio library based on miniaudio.**

`raudio` API tries to be very simple and intuitive and it represents a thin layer over the powerful [miniaudio library](https://github.com/dr-soft/miniaudio), including support for multiple audio formats: WAV, OGG, MP3, FLAC, MOD, XM.

`raudio` is used by [raylib](https://github.com/raysan5/raylib) library as the internal audio module. `raudio.h` exposes the same audio functionality exposed by `raylib.h`. 
<br>

## features

 - Simplifies `miniaudio` usage exposing only basic functionality
 - Audio formats supported: `.wav`, `.qoa`, `.ogg`, `.mp3`, `.flac`, `.xm`, `.mod`
 - Select desired input formats at compilation time
 - Load and play audio, static or streamed modes
 - Support for plugable audio effects with callbacks
 
## library

`raudio` is distributed as two main files: 
 - `raudio.h`: It contains the API declaration with all the exposed functionality
 - `raudio.c`: It contains the implementation of the library, including all the [`external`](src/external) required libraries, all of them single-file header-only libraries.
## usage
For usage example, it's recommended to check the provided [`examples`](examples). They also contain detailed documentation at the start of the examples.
