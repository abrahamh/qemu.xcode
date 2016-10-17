# What is it
Xcode project to build qemu on macOS. 

# Features
- [x] makefile based project for easy integrate other build steps
- [x] one makefile to define used versions (Makefile.def)
- [x] download required source (i.e. qemu, glib ...)
- [x] pack results as *.tar.gz
- [ ] simple UI (planed for future)

# Usage
0. Select scheme `download` and build to download required source.
1. Adapt PREFIX (Makefile.def) if you want to change the target directory.
2. Select scheme `qemu` and build to build qemu and all required libaries an pack result as tar.gz.

# Tests
- Tested with macOS 10.11 and Xcode 8.0


