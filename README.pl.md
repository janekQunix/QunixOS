# QunixOS

Lekka dystrybucja Linuksa oparta na Artix, stworzona dla graczy, którzy chcą kontroli.

## Czym jest QunixOS?

QunixOS to Artix z:

- **kernelem BORE + NTSync** — gotowy, zoptymalizowany pod gry
- **Steam + Proton-GE** — skonfigurowany, gotowy do grania
- **doas** zamiast sudo
- **runit/OpenRC** zamiast systemd
- **Nix w kontenerze** (Distrobox) dla izolowanych środowisk
- **Pacman + AUR (yay)** — system pakietów Arch/Artix

## Dla kogo?

Dla graczy, którzy chcą:

- **Wydajności w grach** — BORE, NTSync, niskie opóźnienia, stabilny 1% low
- **Kontroli nad systemem** — runit/OpenRC, doas, własne jądro
- **Trudności w obsłudze** — jak Gentoo, ale bez emerge (bez kompilacji wszystkiego)

## Zasady

1. **Bez systemd** — runit/OpenRC
2. **Bez sudo** — doas
3. **Bez emerge** — binaria + AUR
4. **Bez zbędnych rzeczy** — tylko to, co potrzebne
5. **Wydajność w grach** — priorytet
6. **Trzy światy pakietów** — Pacman, AUR, Nix — świadomie rozdzielone

## Status

🚧 **Wczesny rozwój** — projekt w fazie planowania i prototypu.

## Plan

- [ ] Zainstalować Artix w VirtualBoxie
- [ ] Skonfigurować yay, doas
- [ ] Skompilować jądro BORE + NTSync
- [ ] Zainstalować Steam + Proton-GE
- [ ] Zbudować ISO z Calamares
- [ ] Opublikować dokumentację
- [ ] Wydać pierwszą wersję

## Jak zacząć?

(Wkrótce — dokumentacja instalacji)

## Licencja

GPLv3
