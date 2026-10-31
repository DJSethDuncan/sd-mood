# SD MOOD

MOOD-inspired ambient delay/texture effect. Original implementation; not affiliated with Chase Bliss.

Independent open-source DSP prototype built with JUCE. Controls are informed by publicly documented hardware controls; this is not affiliated with the manufacturers and is not a bit-accurate recreation. UI is JUCE's generic parameter editor.

## Build
Requires CMake 3.22+, Git, Xcode Command Line Tools, and network access to fetch JUCE 8.0.6.
```sh
cmake -S . -B build -DCMAKE_BUILD_TYPE=Release
cmake --build build --config Release
```
VST3: `build/SDMood_artefacts/Release/VST3/SD MOOD.vst3`.
