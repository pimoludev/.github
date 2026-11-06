<div align="center">
  <img src="https://raw.githubusercontent.com/pimoludev/.github/main/profile/assets/banner.png" alt="Pimolu — One system. Your identity." width="100%" />
</div>

<h1 align="center">Welcome to Pimolu</h1>

<p align="center">
  <strong>A design system that keeps its promises.</strong><br />
  Accessible React components, a single source of visual truth,<br />
  and themes you can switch at runtime — with no styling framework to learn.
</p>

<p align="center">
  <a href="https://pimolu.com">Website</a> ·
  <a href="https://pimolu.com/docs">Documentation</a> ·
  <a href="https://pimolu.com/components">Components</a> ·
  <a href="https://pimolu.com/blocks">Blocks</a> ·
  <a href="https://pimolu.com/showcase">Showcase</a> ·
  <a href="https://www.npmjs.com/org/pimolu">npm</a> ·
  <a href="https://discord.gg/b2UDyvKAcH">Discord</a>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@pimolu/react"><img src="https://img.shields.io/npm/v/@pimolu/react?label=%40pimolu%2Freact&color=7C3AED&labelColor=1F2937&style=flat-square" alt="npm version of @pimolu/react" /></a>
  <img src="https://img.shields.io/badge/license-MIT-7C3AED?labelColor=1F2937&style=flat-square" alt="MIT license" />
  <img src="https://img.shields.io/badge/React-18%20%7C%2019-7C3AED?labelColor=1F2937&style=flat-square" alt="React 18 and 19" />
  <img src="https://img.shields.io/badge/TypeScript-strict-7C3AED?labelColor=1F2937&style=flat-square" alt="Strict TypeScript" />
</p>

---

## Why Pimolu

Interfaces drift. A colour is adjusted here, a radius there, and a few months later no two screens quite look like they belong to the same product.

Pimolu treats that drift as the problem worth solving first. Every visual decision lives behind a **design token**, so consistency becomes the default instead of a constant effort. Themes and styles are applied through attributes, never through conditional code — you design the interface once, then dress it for the product, today and later.

And because a foundation should stay readable, there is no CSS-in-JS runtime, no utility-class framework and no build magic. Just CSS: `pimolu-*` classes and `--pimolu-*` variables you can read, override and leave.

## What you get

| Principle | What it means for you |
| --- | --- |
| **A single source of truth** | Values are authored once as design tokens, then compiled for the web and JavaScript. A change propagates instead of being repeated. |
| **Themes without rewrites** | Light, dark and system modes, plus seven visual presets, are switched at runtime with an attribute. No component is touched. |
| **Accessibility included** | Keyboard support, visible focus, busy and disabled states, screen-reader labels and reduced-motion handling are built in. |
| **No framework to learn** | Plain, predictable CSS that is easy to override, with no lock-in. |
| **Typed end to end** | Strict TypeScript across components and public APIs, so mistakes are caught before runtime. |

Combine a theme (light, dark, system) with a preset: `default`, `monochrome`, `cartoon`, `glass`, `luxury`, `neo-brutalism` or `adaptive`. Radius, density and brand colour are configured independently, without touching a single component.

## Get started

```bash
npm install @pimolu/react@beta @pimolu/web-styles@beta
```

```tsx
import { Button, PimoluProvider } from "@pimolu/react";
import "@pimolu/web-styles/styles.css";

export function App() {
  return (
    <PimoluProvider theme="dark" stylePreset="glass">
      <Button>Get started</Button>
    </PimoluProvider>
  );
}
```

Import the stylesheet once at your application entry, wrap your interface in `PimoluProvider`, and switch themes or presets without editing a single component. Tailwind CSS is optional.

## Explore

| Resource | What you will find |
| --- | --- |
| [**pimolu.com**](https://pimolu.com) | The website, the interactive demo and the product vision. |
| [**Documentation**](https://pimolu.com/docs) | Installation, theming, API reference and practical guides. |
| [**Components**](https://pimolu.com/components) | The full catalogue, with live examples. |
| [**Blocks**](https://pimolu.com/blocks) | Ready-made compositions to move faster. |
| [**Showcase**](https://pimolu.com/showcase) | Products built with Pimolu UI. |
| [**Releases**](https://pimolu.com/releases) | Release notes and changes to the system. |
| [**npm**](https://www.npmjs.com/org/pimolu) | The published packages of the ecosystem. |

## Repositories

| Repository | Purpose |
| --- | --- |
| [**ui**](https://github.com/pimoludev/ui) | The design system: tokens, themes, React components, playground and documentation website. |
| [**react-vite-starter**](https://github.com/pimoludev/react-vite-starter) | A minimal, independent React starter with Vite, TypeScript, Tailwind and the published Pimolu packages. |
| [**nextjs-starter**](https://github.com/pimoludev/nextjs-starter) | The equivalent starting point for a Next.js application. |
| [**dashboard-starter**](https://github.com/pimoludev/dashboard-starter) | A dashboard template for getting a management application off the ground. |
| [**saas-landing**](https://github.com/pimoludev/saas-landing) | A landing page template for a SaaS product. |
| [**pimolu-headset**](https://github.com/pimoludev/pimolu-headset) | A complete storefront showcase built with Pimolu UI — [view it live](https://pimolu-headset.pimolu.com/). |
| [**cli**](https://github.com/pimoludev/cli) | The command-line tool for the Pimolu ecosystem. |
| [**.github**](https://github.com/pimoludev/.github) | The organization profile and its visuals. |

## The mascot

<table>
  <tr>
    <td width="230" align="center" valign="middle">
      <img src="https://raw.githubusercontent.com/pimoludev/.github/main/profile/assets/mascot.jpg" alt="The Pimolu otter" width="200" />
    </td>
    <td valign="middle">
      <p>Pimolu also has an otter. Curious, meticulous, never short of ideas — and a little talkative when it comes to design.</p>
      <p>It reminds us what we look for in every interface: precision, personality, and the pleasure of doing things well.</p>
    </td>
  </tr>
</table>

## Build with us

Pimolu is built in the open. A question, an idea, a bug? Open an [issue](https://github.com/pimoludev/ui/issues) on the relevant repository or join us on [Discord](https://discord.gg/b2UDyvKAcH).

Contributions are welcome. For larger changes, let's discuss them in an issue first so the system stays coherent.

---

<p align="center">
  <sub>Pimolu's public repositories are released under the MIT license. © 2026 pimoludev.</sub><br />
  <sub>Built with Pimolu UI · <a href="https://pimolu.com">pimolu.com</a></sub>
</p>
