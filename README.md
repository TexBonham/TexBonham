## Tex Bonham
 
CS senior at CSUN (B.S. May 2027), with associate degrees in Mathematics and Physics. I build systems-heavy projects — game engines, compilers, OS internals — mostly in C#. Currently teaching CS at Great Minds Robotics alongside my degree.
 
### Current: MSG — Multiplayer Strategy Game
 
A 2D turn-based strategy game in the Advance Wars tradition, solo-developed under **TATB Studio** and targeting a Steam release. Unity 6 / C# on top of a Unity-free deterministic .NET rules engine — now 23 playtest builds in, with 16 commanders, 13 authored maps, an in-game map editor, and match replays.
 
- Online multiplayer over direct TCP and Steam P2P, with server-authoritative sessions, per-seat fog filtering, and per-action state hashing for desync detection
- Successive generations of data-driven AI (a 197-term scoring vocabulary, then fog-honest belief maps with sighting memory), tuned through seeded 800-game overnight self-play batches
- Byte-identical match replays re-simulated through the live rules
- ~18,000 automated tests (NUnit + Unity EditMode) running in CI on every push
*Source private pending release.*
 
### Public projects
 
- **[CSharpOS](https://github.com/TexBonham/CSharpOS)** — an OS emulator on a custom ISA: demand paging with LRU eviction and swap, fork/exec/wait, signals, a filesystem, a self-hosted assembler — and Snake running on top of it all
- **[CishCompiler](https://github.com/TexBonham/CishCompiler)** — a compiler for a custom C-family language, from lexer to .NET CIL code generation
- **[Custom-Computer-Architecture](https://github.com/TexBonham/Custom-Computer-Architecture)** — the 2022 ISA emulator that grew into CSharpOS
bonhamtex@gmail.com · [LinkedIn](https://www.linkedin.com/in/tex-bonham/)
