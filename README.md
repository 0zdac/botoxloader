# botox loader

Minimalist AMOLED CS:GO manual map loader built with ImGui and Direct3D 11.

## Features

- Pure AMOLED `#000000` borderless square interface (260x160)
- Manual mapping engine with TLS initialization, CRT init, and WoW64 thread hijacking
- Automatic game launch (`-allow_third_party_software`) and injection fallback
- Dynamic SHA-256 validation and caching in `%APPDATA%\botox\bin`

## Build

Requirements: Visual Studio 2022 (MSVC C++20), Windows SDK.

```cmd
cd botox
build.bat
```

Output: `botox/build/botox.exe`
