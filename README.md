# download-sdl2

This is an action for downloading SDL2 sources and runtime binaries on Windows using MSVC.

The downloaded headers will be stored under `sources_destination`, in a separate `SDL2-X.Y.Z` folder, where `X.Y.Z` corresponds to the `version` parameter, e.g. `2.0.14`. The `binaries_destination` is the folder where all the runtime binaries (`.dll` files) will be stored.

Note, you will have to make sure that the destination folders exist before invoking the action.

## Usage

```yml
- name: Download SDL2
  uses: albin-johansson/download-sdl2@latest
  with:
    sources_destination: .
    binaries_destination: bin
```
