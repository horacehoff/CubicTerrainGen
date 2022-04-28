# CubicTerrainGen

An Unreal Engine 5 project that generates minecraft-like terrain using sine waves and Blueprint\
**Features**:
- Multiple terrain layers, meaning a more diverse terrain (the more terrain layers, the more diverse the terrain will be)
- Fast iteration
- An experimental grass/dirt separation
- Complete control over the size of the terrain and the separation between blocks

**Drawbacks**:
- The whole system is written in Blueprint, which means terrain generation may take some time (usually ~15 seconds for a terrain with 500x500 blocks)
- Since the project is using sine waves, terrain may become repetitive over size and have less features than a noise-generated terrain.

**To-Do**:
- Rewrite the entire system in C++
- Use noise instead
- Find a way to have only one material for the grass and dirt (meaning only one instanced static mesh, thus improving the performance)

## 🏛️ License
[MIT License](https://github.com/just-a-mango/CubicTerrainGen/blob/main/LICENSE)

Copyright (c) 2022 Just_a_Mango
