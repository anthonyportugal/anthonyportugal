<div align="center">

# Anthony Portugal

<a href="https://anthonyportugal.github.io/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&pause=1400&color=9BC1FB&center=true&vCenter=true&width=640&lines=I+design+systems+that+teams+can+build+on.;Software+engineer+%C2%B7+Frontend+architect;Creator+of+Sanctuary%2C+a+design+system;Tokens+from+the+browser+to+the+terminal;Tech+lead+%C2%B7+Linux+%26+DX+craftsman" alt="I design systems that teams can build on. Software engineer, frontend architect, creator of Sanctuary." />
</a>

Software engineer from Peru with 7+ years across frontend and backend.<br />
I lead teams, build design tokens and component libraries, and ship multiplatform products.

[![Portfolio](https://img.shields.io/badge/Portfolio-anthonyportugal.github.io-9bc1fb?style=for-the-badge&labelColor=0d111b&logo=astro&logoColor=eee7d9)](https://anthonyportugal.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-6bcdf7?style=for-the-badge&labelColor=0d111b&logo=linkedin&logoColor=eee7d9)](https://www.linkedin.com/in/bruceeanthonyportugalrobles/)
[![Sanctuary](https://img.shields.io/badge/Sanctuary-Design_system-f6af57?style=for-the-badge&labelColor=0d111b&logo=github&logoColor=eee7d9)](https://github.com/sanctuary-ds)

</div>

---

### ⛪ Featured · Sanctuary

<a href="https://sanctuary-ds.github.io/playground/"><img src="https://raw.githubusercontent.com/sanctuary-ds/.github/main/brand/rose-spectrum-transparent.png" alt="The Sanctuary rose window" width="132" align="right" /></a>

**[Sanctuary](https://github.com/sanctuary-ds)** is a design system of stone, glass and light that I created and maintain. It ships as design tokens first, so one source of color can theme web interfaces today and, through ports, the apps and tools around them. My [personal website](https://anthonyportugal.github.io/) is built with it.

- **Four flavors**, the hours of the day: Lauds, Vespers, Compline and Matins.
- **Twelve pigments** as accents, each re-toned per flavor and checked for WCAG AA contrast.
- **Three glazings** for how an accent sits on a surface: pot-metal, flashed and grisaille.
- **OKLCH** color and **DTCG** tokens: one palette, built to be ported to any app, from editors and terminals to window managers.

[Playground](https://sanctuary-ds.github.io/playground/) · [Docs](https://sanctuary-ds.github.io/docs/philosophy) · [`@sanctuary-ds/tokens` on npm](https://www.npmjs.com/package/@sanctuary-ds/tokens) · [Source](https://github.com/sanctuary-ds/tokens)

---

### 🏛️ Focus

- **Design systems & tokens:** core, semantic and component tokens that keep design and code in the same language, with typed component APIs and predictable releases.
- **Frontend architecture:** Clean Architecture boundaries and SOLID, so domain logic outlives the framework of the year.
- **Technical leadership:** leading product teams through multiplatform migrations, interviews and onboarding.
- **Linux & developer experience:** reproducible workstations, shell automation and CI/CD pipelines that let a team ship without friction.

Current role and full history: [anthonyportugal.github.io/#experience](https://anthonyportugal.github.io/#experience)

---

### 📊 Production Impact

<div align="center">

| | |
| :---: | :---: |
| ![−30% technical debt](https://img.shields.io/badge/−30%25-technical_debt-8cd584?style=for-the-badge&labelColor=0d111b)<br /><sub>Clean Architecture + SOLID</sub> | ![−80% manual deployments](https://img.shields.io/badge/−80%25-manual_deployments-9bc1fb?style=for-the-badge&labelColor=0d111b)<br /><sub>GitLab CI/CD automation</sub> |
| ![+40% frontend velocity](https://img.shields.io/badge/+40%25-frontend_velocity-d2abfb?style=for-the-badge&labelColor=0d111b)<br /><sub>Unified design system</sub> | ![−50% build time](https://img.shields.io/badge/−50%25-build_time-f6af57?style=for-the-badge&labelColor=0d111b)<br /><sub>Migration to Vite</sub> |
| ![5 platforms](https://img.shields.io/badge/5_platforms-one_codebase-74d5b8?style=for-the-badge&labelColor=0d111b)<br /><sub>Flutter: Android, iOS, Windows, Linux, macOS</sub> | ![~7 engineers led](https://img.shields.io/badge/~7_engineers-led-fca1b8?style=for-the-badge&labelColor=0d111b)<br /><sub>Tech lead, multiplatform team</sub> |

</div>

---

### 🐧 Workstation as Code

Modular Linux environments, versioned and documented so they can be rebuilt from scratch.

| Project | What it is | Stack |
| :--- | :--- | :--- |
| [**dotfiles-mangowm**](https://github.com/anthonyportugal/dotfiles-mangowm) | **Daily driver.** Dynamic tiling Wayland session, featured in the official MangoWM showcase. | `Wayland` `MangoWM` `Waybar` `Fuzzel` |
| [**dotfiles**](https://github.com/anthonyportugal/dotfiles) | **Core and orchestrator.** Modular user space with an interactive CLI and a 3-tier privacy model. | `GNU Stow` `Zsh` `Starship` `FZF` |
| [**dotfiles-system**](https://github.com/anthonyportugal/dotfiles-system) | **System layer.** Ly display manager, non-destructive Limine theming and DNS-over-TLS. | `Limine` `Ly` `systemd-resolved` |
| [**walls**](https://github.com/anthonyportugal/walls) | **Wallpaper pipeline.** Curated WebP collection with conversion, multi-monitor sync and diagnostics. | `WebP` `swaybg` `FZF` |
| [**dotfiles-bspwm**](https://github.com/anthonyportugal/dotfiles-bspwm) | *Classic X11 alternative.* Ergonomic BSPWM session with dynamic Polybar detection. | `X11` `BSPWM` `Polybar` `Picom` |

<details>
  <summary>🖼️ <strong>Preview the MangoWM desktop</strong></summary>
  <br />
  <div align="center">
    <a href="https://github.com/anthonyportugal/dotfiles-mangowm">
      <img src="https://raw.githubusercontent.com/anthonyportugal/dotfiles-mangowm/main/assets/screenshot.webp" alt="MangoWM desktop preview" width="85%" />
    </a>
  </div>
</details>

---

### 🤖 How I Work with AI Agents

Agents write a large share of my code. Engineering is making sure that code deserves to ship.

- **Spec before prompt:** every task starts from a written spec with acceptance criteria and the check that proves them.
- **The author never approves its own work:** risky changes go to independent reviewer agents that only see the frozen diff.
- **I own what ships:** I verify the result where it runs, sign the commits and decide when to push.

---

### 🛠️ Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,js,vue,nuxtjs,react,angular,astro,vite,tailwind,flutter,dart&perline=11" alt="Frontend and mobile" />
</p>
<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,nestjs,laravel,graphql,mysql,docker,aws,gitlab,githubactions,linux,arch,bash,python,go&perline=14" alt="Backend, infrastructure and tooling" />
</p>

---

<div align="center">

Design systems, frontend architecture or Linux tooling? Let's talk at<br />
**[anthonyportugal.github.io](https://anthonyportugal.github.io/#contact)** · **[LinkedIn](https://www.linkedin.com/in/bruceeanthonyportugalrobles/)**

</div>
