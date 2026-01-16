# Zork: Mobile

A modern, mobile-first web adaptation of the classic interactive fiction game **ZORK I: The Great Underground Empire**.

## About
This project reimagines the classic text adventure interface as a modern messaging app. It runs entirely in the browser using the **JSZM** interpreter to execute the original Z-machine story file.

Developed with a focus on responsiveness, accessibility, and a premium mobile experience.

## Features
- **Modern UI**: Chat-bubble interface with responsive design.
- **Mobile Optimized**: Full-screen experience, safe-area handling, and virtual keyboard support.
- **Text-to-Speech**: Integrated Web Speech API to read game output aloud with a retro "beep" indicator.
- **Auto-Save**: Seamless save/load functionality using LocalStorage.
- **Real-time Clock**: Status bar synced to your device time.

## Technology
- **Engine**: [JSZM](https://www.ifwiki.org/JSZM) (JavaScript Z-Machine Interpreter)
- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **Audio**: Web Audio API (procedural sound generation) & Web Speech API

## Credits & License
**Developer**: Lewis Dryburgh

**Disclaimer**:
This is an **unofficial fan project**. It is not affiliated with, endorsed by, or connected to Infocom, Activision, or any other trademark holders of the Zork franchise.

**Source Code**:
The Z-Machine interpreter source code is provided under the **MIT License (Microsoft, 2025)** (see `LICENSE-ZORK`).
The frontend web wrapper and UI code is provided under the **MIT License (Lewis Dryburgh, 2026)** (see `LICENSE-FRONTEND`).

*ZORK is a registered trademark of Infocom, Inc.*
*Original Game © 1981-1986 Infocom, Inc.*
