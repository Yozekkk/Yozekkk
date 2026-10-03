<div align="center">
  <h1>Yozekkk</h1>
  <p>Developer building desktop tools, web applications, and Minecraft projects.</p>
  <p>Rust · TypeScript · React · Vue · Linux</p>
</div>

I work across the NCreate ecosystem: a desktop launcher, a versioned Minecraft pack, publication tooling, and a community site. I also build the NCEA platform and the English Step learning app. The repositories below show the implementation and current limits of each project.

## Featured projects

| Project | What it contains |
| --- | --- |
| [NCreate Launcher](https://github.com/Yozekkk/ncreate-launcher) | Tauri v2 desktop app in Rust and Vue 3. Installs and launches Minecraft instances, browses Modrinth content, and installs the official NCreate Server pack. [v0.6.0 Beta](https://github.com/Yozekkk/ncreate-launcher/releases/tag/v0.6.0) is the current tagged release. |
| [NCreate Site](https://github.com/Yozekkk/ncreate-site) | React and TanStack Start site with NCreate pages, shared Supabase Auth, and a dedicated forum. Some server information is still shown as “Coming soon.” |
| [NCEA](https://github.com/Yozekkk/ncea-tra) | Public site and community platform, plus a separate admin application and Supabase migrations. |
| [English Step](https://github.com/Yozekkk/nelli-english) | Twenty English lessons with quizzes and shared progress stored in Supabase. |

## NCreate release chain

```text
ncreate-pack Stable manifest → NCreate Launcher → installed NCreate Server instance
```

- [ncreate-pack](https://github.com/Yozekkk/ncreate-pack) publishes the current official pack manifest, reviewed mod sources, and versioned configuration files
- [ncreate-launcher](https://github.com/Yozekkk/ncreate-launcher) verifies the manifest and files before installation
- [ncreate-manifests](https://github.com/Yozekkk/ncreate-manifests) contains a separate pipeline for Minimal, Standard, and Ultra editions; those channels are not published or consumed by the current launcher

## Technologies

<p>
  <img src="https://img.shields.io/badge/Rust-242424?logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Tauri-v2-242424?logo=tauri&logoColor=white" alt="Tauri v2">
  <img src="https://img.shields.io/badge/TypeScript-242424?logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Vue-3-242424?logo=vuedotjs&logoColor=white" alt="Vue 3">
  <img src="https://img.shields.io/badge/React-19-242424?logo=react&logoColor=white" alt="React 19">
  <img src="https://img.shields.io/badge/TanStack_Start-242424" alt="TanStack Start">
  <img src="https://img.shields.io/badge/Supabase-242424?logo=supabase&logoColor=white" alt="Supabase">
</p>
