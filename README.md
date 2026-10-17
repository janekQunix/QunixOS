# QunixOS

A lightweight Linux distribution based on Artix, built for gamers who want control.

## What is QunixOS?

QunixOS is Artix with:

- **BORE + NTSync kernel** — ready, optimized for gaming
- **Steam + Proton-GE** — preconfigured, ready to play
- **doas** instead of sudo
- **runit/OpenRC** instead of systemd
- **Nix in a container** (Distrobox) for isolated environments
- **Pacman + AUR (yay)** — Arch/Artix package system

## Who is it for?

For gamers who want:

- **Gaming performance** — BORE, NTSync, low latency, stable 1% low
- **System control** — runit/OpenRC, doas, custom kernel
- **Difficulty in use** — like Gentoo, but without emerge (no compiling everything)

## Principles

1. **No systemd** — runit/OpenRC
2. **No sudo** — doas
3. **No emerge** — binaries + AUR
4. **No bloat** — only what's needed
5. **Gaming performance** — priority
6. **Three package worlds** — Pacman, AUR, Nix — consciously separated

## Status

🚧 **Early development** — project in planning and prototype phase.

## Roadmap

- [ ] Install Artix in VirtualBox
- [ ] Configure yay, doas
- [ ] Compile BORE + NTSync kernel
- [ ] Install Steam + Proton-GE
- [ ] Build ISO with Calamares
- [ ] Publish documentation
- [ ] Release first version

## Getting started

(Coming soon — installation documentation)

## License

GPLv3
