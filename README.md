![emscripten logo](media/switch_logo.png)

Internal [Numfum](//numfum.com/) fork of Emscripten containing fixes not merged into the main Emscripten branch:

- Audio Worklets have an [optimised copy](//github.com/cwoffenden/emscripten/tree/cw-audio-spinlock-fix) from the wasm heap (details in [PR 22753](//github.com/emscripten-core/emscripten/pull/22753) yielding a 7-12x perfomance increase).
- Audio Worklets have [support for spinlocks](//github.com/cwoffenden/emscripten/tree/cw-audio-spinlock-fix) (details in [PR 23393](//github.com/emscripten-core/emscripten/pull/23393)).
