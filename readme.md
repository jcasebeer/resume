# James Casebeer

**Richmond, VA** | **Remote Available** | **Open to relocation for the right opportunity**  
(703) 638-2390 | [james.casebeer@gmail.com](mailto:james.casebeer@gmail.com)  
[LinkedIn](https://www.linkedin.com/in/james-casebeer-b64b4813b/) | [GitHub](https://github.com/jcasebeer)

---

## Professional Summary

C/C++ systems developer with 8 years of professional experience building and maintaining high-throughput, mission-critical software for enterprise document delivery platforms. Led a small development team and drove technical direction for on-premises software deployed across large enterprise ERP environments. Independently designed and built a 3D game engine from scratch in C++, featuring a physically based rendering pipeline, shadow mapping, an entity-component system, custom memory allocators, and multithreaded procedural mesh generation. Equally comfortable at the systems and graphics layers — seeking a role where low-level performance and code quality matter.

---

## Professional Experience

### Lead Product Developer
**STR Software — Richmond, VA**
*2021 – Present*

- Led development and long-term technical direction of core C/C++ software for an on-premises enterprise document delivery platform, deployed at customer sites processing **10,000+ documents per day**.
- Managed and mentored junior developers, conducting code reviews and providing technical guidance across the team.
- Drove architectural decisions to improve integration stability and throughput across ERP environments including Oracle and SAP.
- Sole developer on a port of the Linux build from 32-bit to 64-bit, requiring significant rework of platform assumptions baked into the original design while maintaining compatibility across Solaris, AIX, and HPUX.
- Owned feature development end-to-end, from design through deployment, for mission-critical print, fax, and email delivery systems.

### Junior Software Developer
**STR Software — Richmond, VA**
*2017 – 2021*

- Developed and maintained C/C++ components for ERP-to-hardware integration, focusing on high-throughput data handling and device communication across print, fax, and email delivery systems.
- Worked extensively with Unix system APIs including fork, select, and FIFO-based IPC for inter-process communication across the document delivery pipeline.
- Contributed to performance tuning, debugging, and feature work on a production codebase serving enterprise customers.

---

## Selected Projects

### Gunswinger — 3D Game Engine & Game
*Personal Project — C++ | ~20,000 lines | Private repository, available on request*

- Designed and built a complete 3D game engine and game from scratch in C++.
- Implemented a physically based rendering (PBR) pipeline in OpenGL with custom GLSL shaders, including shadow mapping, normal mapping, and material workflows.
- Built an entity-component system (ECS) for decoupled, composable scene management.
- Wrote custom memory allocators to minimize heap fragmentation and improve cache performance in hot paths.
- Implemented multithreaded procedural mesh generation with optimizations targeting high-refresh-rate displays (120Hz+).
- Integrated GLFW for window/input management and miniaudio for audio playback.

### CGOL — Cellular Automata Simulator
*Personal Project — C | [github.com/jcasebeer/cgol](https://github.com/jcasebeer/cgol)*

- Built a terminal-based Conway's Game of Life simulator supporting arbitrary rulesets in Golly notation.
- Implemented a fixed 2D grid, real-time simulation, and a flexible command-line interface for custom cellular automata rules.

### Low-Level C Utilities
*Personal Projects — C | [github.com/jcasebeer](https://github.com/jcasebeer)*

- **packer** — Packs separate PBR textures (albedo, roughness, metallic) into combined textures, reducing memory usage and binding overhead in rendering systems.
- **radix_sort** — LSD radix sort implementation.
- **hash** — Custom hash table implementations.
- **marray** — Dynamic array macros for efficient memory management in C.


---

## Education

**Bachelor of Science in Computer Science**  
George Mason University — Graduated 2017

---

## Skills

| | |
|---|---|
| **Languages** | C, C++ (C++17/20), Java, Python |
| **Graphics & Audio** | OpenGL, GLSL, GLFW, miniaudio, ImGui |
| **Rendering** | Physically Based Rendering, Shadow Mapping, Texture/Channel Packing |
| **Systems** | Multithreading, Custom Memory Allocators, Performance Optimization, Data Structures & Algorithms, Unix IPC (fork, select, FIFO) |
| **Platforms** | Linux (RHEL, Alpine), Solaris, AIX, HPUX |
| **Tools** | CMake, GCC/Clang, GDB, Make, Visual Studio, Git, SQLite, stb_image |
| **Other** | ECS Architecture, Procedural Generation, ERP Integration (Oracle, SAP) |
