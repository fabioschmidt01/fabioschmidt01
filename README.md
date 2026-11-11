<div align="center">

# 👋 Hi there, I'm Fábio Schmidt

### **Game Developer • Low-Level Systems & Graphics • Static Recompilation**

[![GitHub followers](https://img.shields.io/github/followers/fabioschmidt01?label=Followers&style=social)](https://github.com/fabioschmidt01)
[![GitHub stars](https://img.shields.io/github/stars/fabioschmidt01?label=Stars&style=social)](https://github.com/fabioschmidt01)

<br/>

> *"Exploring the frontiers of reverse engineering, ahead-of-time (AOT) static recompilation, Vulkan graphics, and custom game engine architecture."*

</div>

---

### 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚡ <a href="https://github.com/fabioschmidt01/PokeL-ARecomp">PokeL-ARecomp (PLA Recomp)</a></h4>
      <p>Native PC port and static recompiler for <i>Pokémon Legends: Arceus</i> (Nintendo Switch). Custom Vulkan 1.3 backend, dynamic delta-time 60 FPS pacing, hardware optical flow Frame Generation (90–120 FPS), HUD Decoupling via <code>hdr_snapshot</code>, and multi-threaded Xeon / Intel Arc Battlemage optimizations.</p>
      <p><code>C</code> <code>Vulkan 1.3</code> <code>C# .NET 9</code> <code>LibHac</code> <code>SDL3</code> <code>XeSS</code></p>
    </td>
    <td width="50%" valign="top">
      <h4>⚡ <a href="https://github.com/fabioschmidt01/PokeV-Recomp">PokeV-Recomp (SV Recomp)</a></h4>
      <p>Native PC port and ahead-of-time recompiler for <i>Pokémon Violet & Scarlet</i>. Translates ARM64 machine code directly into native 64-bit C with reimplemented Switch OS services and Maxwell NVN graphics running over Vulkan without emulation.</p>
      <p><code>C</code> <code>Vulkan</code> <code>AOT Recompilation</code> <code>Multi-Threading</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🛡️ <a href="https://github.com/fabioschmidt01/aurora-engine">Aurora Engine & SDK</a></h4>
      <p>Proprietary 2D game engine and reusable SDK built from scratch in C++20. Features a custom Vulkan 1.4 renderer, SDL3 windowing, EnTT ECS, Box2D physics, miniaudio, LDtk tilemaps, and hot-reloadable Lua 5.4 scripting.</p>
      <p><code>C++20</code> <code>Vulkan 1.4</code> <code>SDL3</code> <code>EnTT ECS</code> <code>Box2D</code> <code>Lua</code></p>
    </td>
    <td width="50%" valign="top">
      <h4>🥊 <a href="https://github.com/fabioschmidt01/godhand-recomp">God Hand Recomp</a></h4>
      <p>Static recompilation of the PlayStation 2 classic <i>God Hand</i> into native x86-64 C++ utilizing PS2Recomp, executing the original game logic directly on PC hardware.</p>
      <p><code>C++</code> <code>PS2 Recompilation</code> <code>Reverse Engineering</code></p>
    </td>
  </tr>
</table>

---

### 🛠️ Tech Stack & Skills

<div align="center">

| Category | Technologies |
|---|---|
| **Languages** | ![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![GLSL](https://img.shields.io/badge/GLSL-555555?style=for-the-badge&logo=opengl&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) |
| **Graphics & Low-Level** | ![Vulkan](https://img.shields.io/badge/Vulkan-AC162C?style=for-the-badge&logo=vulkan&logoColor=white) ![DirectX 12](https://img.shields.io/badge/DirectX_12-0078D7?style=for-the-badge&logo=windows&logoColor=white) ![SDL3](https://img.shields.io/badge/SDL3-1774A5?style=for-the-badge&logoColor=white) ![Intel XeSS](https://img.shields.io/badge/Intel_XeSS-0071C5?style=for-the-badge&logo=intel&logoColor=white) ![SPIR-V](https://img.shields.io/badge/SPIR--V-7D1538?style=for-the-badge&logoColor=white) |
| **Game Engines & SDKs** | ![Aurora SDK](https://img.shields.io/badge/Aurora_Engine_%26_SDK-6C5CE7?style=for-the-badge&logo=cplusplus&logoColor=white) ![Unreal Engine](https://img.shields.io/badge/Unreal_Engine-313131?style=for-the-badge&logo=unrealengine&logoColor=white) ![Godot](https://img.shields.io/badge/Godot_Engine-478CBF?style=for-the-badge&logo=godotengine&logoColor=white) |
| **Systems & DevOps** | ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Clang/LLVM](https://img.shields.io/badge/LLVM_Clang-262C39?style=for-the-badge&logo=llvm&logoColor=white) |

</div>

---

### 🎮 Arcade Quest (Interactive Mini-Game)

Click below to play a quick turn-based encounter:

<details>
<summary><b>⚔️ A wild Bug appeared! Click to choose your move:</b></summary>
<br/>

> **Wild Bug:** *"Segmentation fault (core dumped) at `0xDEADBEEF`!"*  
> **Your HP:** `100/100` | **Bug HP:** `80/80`

<table>
  <tr>
    <td align="center">
      <details>
        <summary><b>🗡️ Action 1: Disassemble & Recompile</b></summary>
        <p>💥 <i>Critical Hit! You translated the guest ARM64 opcodes into optimized native C!</i></p>
        <p><b>Result:</b> Bug took <b>95 damage</b>! Bug fainted!</p>
        <p>🏆 <i>+500 EXP. Framerate boosted to 60 FPS!</i></p>
      </details>
    </td>
    <td align="center">
      <details>
        <summary><b>🛡️ Action 2: Vulkan Pipeline Barrier</b></summary>
        <p>🛡️ <i>You deployed <code>vkCmdPipelineBarrier</code> with <code>VK_ACCESS_MEMORY_READ_BIT</code>!</i></p>
        <p><b>Result:</b> Zero memory races. The bug's attack was completely absorbed!</p>
        <p>✨ <i>Swapchain remains pristine!</i></p>
      </details>
    </td>
  </tr>
  <tr>
    <td align="center">
      <details>
        <summary><b>⚡ Action 3: Optical Flow Frame Gen</b></summary>
        <p>🚀 <i>Motion vectors interpolated to 120 FPS!</i></p>
        <p><b>Result:</b> The bug couldn't keep up with your refresh rate and fell into a swapchain vblank stall!</p>
        <p>⚡ <i>Smooth victory!</i></p>
      </details>
    </td>
    <td align="center">
      <details>
        <summary><b>🔴 Action 4: Throw Arceus Pokéball</b></summary>
        <p>⭐ <i>Wobble... Wobble... Click!</i></p>
        <p><b>Result:</b> You caught the wild Bug and refactored it into a clean pull request!</p>
        <p>🎉 <i>Merged into <code>main</code>!</i></p>
      </details>
    </td>
  </tr>
</table>

</details>

---

### 📊 GitHub Stats & Activity

<div align="center">

  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=fabioschmidt01&show_icons=true&theme=radical&include_all_commits=true&count_private=true&hide_border=true&border_radius=8" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=fabioschmidt01&layout=compact&langs_count=6&theme=radical&hide_border=true&border_radius=8" />

  <br/><br/>

  <img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=fabioschmidt01&theme=radical&hide_border=true&border_radius=8" />

</div>

---

### 🐍 Contribution Snake

<div align="center">

  <img src="https://raw.githubusercontent.com/fabioschmidt01/fabioschmidt01/output/github-contribution-grid-snake.svg" alt="Snake animation" />

</div>

---

<div align="center">
  <sub>Engineered with passion for native graphics, low-level systems, and static recompilation.</sub>
</div>
