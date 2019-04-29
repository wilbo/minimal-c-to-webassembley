# Minimal C to WebAssembly boilerplate

A C file, a shell HTML file and a build script that compiles a C function into a callable WebAssembly function from JavaScript.

## install

Follow the emscripten installation instructions until you are able to use the `emcc` command (up to the `source ./emsdk_env.sh` part). Clone this project and use the following commands to compile and execute some WebAssembly:

```bash
# Compiles the C code to Webassembley and moves it into the dist folder.
./build.sh
# Serve the compiled output with serve (must have Node.js installed).
npx serve dist
```
