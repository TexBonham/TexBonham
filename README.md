# Tex Bonham
 
CS senior at CSUN (B.S. May 2027), with associate degrees in Mathematics and Physics.
I build systems-heavy projects — game engines, compilers, OS internals — mostly in C#.
Currently teaching computer science at Great Minds Robotics alongside my degree.
 
## Current project: MSG — Multiplayer Strategy Game
 
A 2D turn-based strategy game in the Advance Wars tradition, solo-developed under
**TATB Studio** and targeting a Steam release. Built in Unity 6 / C# on top of a
Unity-free, deterministic .NET rules engine:
 
- Online multiplayer over direct TCP and Steam P2P, with server-authoritative
  sessions and per-seat fog-of-war filtering
- A data-driven AI tuned through seeded self-play (800-game overnight batches)
- Byte-identical match replays re-simulated through the live rules
- ~13,000 automated tests running in CI on every push
*Source private pending release.*
 
## Public projects
 
- **[CSharpOS](https://github.com/TexBonham/CSharpOS)** — an OS emulator on a custom
  ISA: demand paging with LRU eviction and swap, fork/exec/wait, signals, a
  filesystem, a self-hosted assembler — and Snake running on top of it all
- **[CishCompiler](https://github.com/TexBonham/CishCompiler)** — a compiler for a
  custom C-family language, from lexer to .NET CIL code generation
- **[Custom-Computer-Architecture](https://github.com/TexBonham/Custom-Computer-Architecture)** —
  the 2022 ISA assembler/emulator that grew into CSharpOS
  bonhamtex@gmail.com · [LinkedIn](https://www.linkedin.com/in/tex-bonham/)
