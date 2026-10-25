
# DreamcastDroid Build

Experimental build configuration for Android 4.0
targeting the Sega Dreamcast's SH-4 architecture.

## Status
Planning only. No successful SH-4 Android build yet.

## Planned files
- AndroidProducts.mk
- dreamcastdroid.mk
- BoardConfig.mk
- device.mk
- build-notes.md

## Architecture
The standard ICS build system does not provide a ready-made
SH-4 Dreamcast target. Architecture support must be investigated
before attempting a complete build.

## Build milestones
- [ ] Verify the historical ICS source tree
- [ ] Establish an SH-4 Linux cross-toolchain
- [ ] Investigate build-system architecture assumptions
- [ ] Define the Dreamcast product and board configuration
- [ ] Build and test a minimal native userspace
- [ ] Attempt Android framework integration

## Important
Do not treat a successful makefile parse as proof that
the target can compile or boot.
