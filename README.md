# Awesome-Game-Engines

# Top Game Engines Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Cross-Platform Game Development, Editor Workflows & Self-Hosted Engine Alternatives*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Game Engines**. These tools provide the complete environment for building games—editor, rendering, physics, scripting, and asset pipelines—ranging from proprietary industry standards to MIT-licensed engines that guarantee zero platform risk.

**Examples** include Godot, Unity, Unreal Engine, GameMaker, Construct 3, Cocos Creator, PlayCanvas, Defold, RPG Maker, and Stencyl (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom engine modification, and transparent development workflows—ideal for indie studios, solo developers, and teams that prioritize long-term financial predictability over proprietary feature lock-in. The open-source landscape is anchored by **Godot** (the leading MIT-licensed engine with a full editor), **Defold** (the cross-platform engine from King with a permissive license), and **Cocos Creator** (the TypeScript-based 2D/3D engine), with **Stencyl** offering visual scripting for non-programmers and **PlayCanvas** providing a browser-first collaborative editor.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Unity](https://unity.com/)**  
  The dominant commercial game engine with a full editor, asset store, and massive ecosystem. **Pricing**: Unity Pro is required above $200,000 annual revenue/funding; Enterprise above $25 million. Unity 7 was announced at Unite Seoul 2026, introducing Neural Texture Compression (50%+ runtime memory reduction) and a Unity-in-Unreal rendering partnership demo . DevOps pricing changed March 2026 with unlimited seats and increased free tiers . Proprietary.

- **[Unreal Engine](https://www.unrealengine.com/)**  
  Epic's flagship engine for photorealistic AAA and high-fidelity visuals. **UE 5.8** is the last planned UE5 major release, with **Unreal Engine 6** targeting Early Access in late 2027 . UE 5.8 introduces an experimental MCP plugin allowing Claude/Gemini to actively participate in engine workflows, and **Lore**, an open-source next-gen version control system for both code and binary assets . Royalty model: 5% above $1M lifetime revenue. Proprietary source available.

- **[GameMaker](https://gamemaker.io/)**  
  Commercial 2D-focused engine with GML scripting and visual editor. **2026.0** release removed default empty asset groups from new projects and changed default product naming from "Created in GameMaker" . Offers Monthly, Beta, and LTS release channels; LTS recommended for education environments . Proprietary with free tier for non-commercial use.

- **[Construct 3](https://www.construct.net/)**  
  Browser-based 2D game engine with event-sheet logic (no traditional coding). **r477** (March 2026) added WebGPU compatibility mode for broader device support and pixel snapping for pixel-art games . Proprietary subscription.

- **[RPG Maker](https://rpgmakerofficial.com/)**  
  Series of consumer-focused RPG creation tools. The **RPG Maker U2U** (Unity-based) and **RPG MAKER WITH** (Godot-based action game maker) represent the series' expansion beyond its traditional 2D RPG niche . Proprietary, with varying feature sets per edition.

- **[PlayCanvas](https://playcanvas.com/)**  
  Browser-based collaborative game engine with WebGL/WebGPU rendering. **WebGPU support** officially landed in PlayCanvas Engine 1.62, enabling faster rendering for complex 3D scenes directly in the browser . The editor is proprietary SaaS, but the **engine runtime is open-source** (MIT). Best for web-first 3D games and real-time collaborative development.

## Open-Source GitHub Projects

- **[Godot Engine](https://github.com/godotengine/godot)**  
  The leading open-source game engine. **MIT licensed**—the most permissive license among full-featured engines, meaning zero platform risk: terms cannot be changed or "rug-pulled" like proprietary engines . Full visual editor, GDScript (Python-like) plus C# support, scene system, and 2D/3D rendering. **Production-proven**: Slay the Spire 2, Brotato, Dome Keeper, and Cassette Beasts were built with Godot . **Best for**: Indie developers prioritizing financial predictability, 2D games, stylized 3D, mobile (smaller binaries, faster builds), and game jams . **Limitations**: Less mature than Unreal for photorealistic AAA, large-scale multiplayer, or VR at production scale .

- **[Defold](https://github.com/defold/defold)**  
  Cross-platform game engine from King (Candy Crush creators) with a **permissive license** (source available, free to use and modify). **Defold 1.14.0** (October 2026) added Metal as default on macOS, cubemap render targets, and support for up to 1,048,576 game objects per collection . **Breaking changes**: 32-bit Windows support removed; shared Lua state now mandatory . Historically Vulkan became default on macOS in 2025, with OpenGL still selectable via App Manifest . Best for 2D and lightweight 3D games targeting mobile, web, and desktop with a small runtime footprint.

- **[Cocos Creator](https://github.com/cocos/cocos-engine)**  
  TypeScript-based 2D/3D game engine with a full editor. Supports TypeScript 4.1.0 with specific restrictions (no `const enums`, no `export =`, `tsconfig.json` not read at compile time) . JavaScript is supported only as plugin scripts; ES6 features and legacy decorators are available . **Cocos Dashboard** now integrates OpenPaaS, enabling one-click publishing to 3,000+ platforms . Best for developers in the TypeScript ecosystem and teams targeting Asian markets where Cocos has strong adoption.

- **[PlayCanvas Engine](https://github.com/playcanvas/engine)**  
  The **open-source runtime** powering the PlayCanvas editor. MIT licensed. WebGL/WebGPU rendering optimized for browser-based 3D games. The editor itself is proprietary SaaS, but the engine can be self-hosted and extended. Best for developers who want the PlayCanvas runtime without the hosted editor dependency, or who want to study a production-grade web game engine.

- **[Stencyl](https://github.com/Stencyl/stencyl-engine)**  
  Visual scripting game engine for creating 2D games without writing code, similar to Scratch. **Stencyl 4.2.0** (September 2026) supports Windows, macOS, and Linux; free to publish to HTML5, with paid tiers for iOS/Android/desktop . Best for educators, non-programmers, and rapid prototyping with visual logic.

### Additional Strong Open-Source Options

- **Flax Engine** — Open-source C#/C++ game engine with a full editor, positioned as a modern alternative to Unity for developers wanting source access without Godot's GDScript-first approach.
- **Stride3D** — Open-source C# game engine with a full editor, best for .NET developers who want engine features without Unity's licensing model.
- **Frameworks for building custom systems**: Use **Godot** as the primary engine for indie projects requiring MIT licensing guarantees. Choose **Defold** for lightweight mobile/web games with a small runtime. Use **Cocos Creator** for TypeScript-centric workflows and Asian market distribution. Build on **PlayCanvas Engine** when web-first 3D is the priority and you want runtime control without editor lock-in.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Engine choice depends heavily on project scope, team skills, and target platforms. Godot excels at indie and 2D; Unreal dominates photorealistic AAA; Unity sits in the middle with the largest asset ecosystem .
- **Platform risk is real**: Unity's pricing changes and Unreal's royalty model contrast with Godot's MIT license, which cannot be revoked. Evaluate long-term financial exposure alongside technical features.
- Defold 1.14.0 introduces breaking changes (32-bit Windows removal, mandatory shared Lua state) that may require migration effort for existing projects .

---

**Made for indie developers, game programmers, studio leads, and anyone who wants to build games with full control over their engine technology.**  
Let's make game development more open, predictable, and accessible.
