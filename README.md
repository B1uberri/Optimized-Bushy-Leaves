# Optimized Bushy Leaves
<p align="center">
  <a href="https://modrinth.com/resourcepack/fancyfast-bushy-leaves"><img src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/available/modrinth_64h.png" alt="Modrinth" height="64"></a>
  <a href="https://www.curseforge.com/minecraft/texture-packs/fancyfast-bushy-leaves"><img src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/available/curseforge_64h.png" alt="CurseForge" height="64"></a>
</p>

<center>
<h2>Description</h2>
</center>

Bushy leaves resource packs often require more GPU processing power because they generate additional leaf layers not only on the outer parts of tree canopies, but also inside them, where they are barely visible to the player. These hidden internal layers can have a significant impact on performance, especially on mid-range and low-end GPUs when shaders are enabled.

Mods such as <a href="https://modrinth.com/mod/moreculling">More Culling</a> can improve performance by removing internal leaf faces. However, when a resource pack adds its own additional geometry or layers inside the leaf block, these elements usually cannot be culled by the mod and may still cause noticeable performance drops.

This resource pack does not add any internal geometry inside leaf blocks and also disables leaf transparency. As a result, GPU load is significantly reduced and performance is noticeably improved. Additionally, it helps hide the unusual visual artifacts that can appear on tree canopies when using fast leaves culling.

**Important!**

- **Fancy Leaves** setting is required for the resource pack to function correctly.
- <a href="https://modrinth.com/mod/moreculling">**More Culling**</a> (or other similar mod) is required, otherwise performance may not increase.
