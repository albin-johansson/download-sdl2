# download-sdl2

This is an action for downloading SDL2 sources and runtime binaries on Windows using MSVC.

## Usage

```yml
- name: Download SDL2
  uses: albin-johansson/download-sdl2@v1
  with:
    version: 2.0.14
    sources_destination: ./SDL2
    binaries_destination: ./bin
```
