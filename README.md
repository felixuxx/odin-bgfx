# odin-bgfx
Odin bindings for the BGFX library

An example is included in the examples directory

## Platform support

- Windows: links against the bundled `.lib` files.
- Linux: links against the bundled `.so` files in `bgfx/bindings/lib`.
  - X11 is supported.
  - Wayland is supported when GLFW provides Wayland native functions (GLFW 3.4+).

Darwin support is still TODO.

## Run example

```bash
odin run examples
```
