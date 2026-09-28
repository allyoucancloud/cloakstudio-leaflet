<h1 align="center">CloakStudio</h1>
<p align="center"><strong>Design every Keycloak authentication screen. Visually.</strong></p>

<p align="center">
  <a href="https://allyoucancloud.com/">Website</a> ·
  <a href="#getting-started">Getting started</a>
</p>

<p align="center">
  <img alt="Keycloak" src="https://img.shields.io/badge/Keycloak-26%2B-4f46e5">
  <img alt="Setup" src="https://img.shields.io/badge/setup-no%20code-5ad1c4">
  <img alt="Product type" src="https://img.shields.io/badge/type-commercial%20product-f0b429">
</p>

---

> **About this repository.** CloakStudio is a hosted, commercial product — this repository is a documentation and reference page, not the application's source code. Use the links above to try it or read the full docs.
>

## What is CloakStudio

CloakStudio is a **Keycloak theme builder**: a fully visual, drag-and-drop tool built to customize every Keycloak authentication screen, from logins, registration, password reset pages to OTP and more. No need for FreeMarker or CSS. Just design and deploy.

CloakStudio works with the Keycloak instance you already have, or sets one up for you if you don't. From there, you design every page in the authentication flow with a live preview on desktop, tablet and mobile, and deploy straight to your realm through one guided flow: design, connect, deploy, done.

Once deployed, these are the exact pages your users see whenever they to log in, sign up or reset a password on your app. They land on the screens you designed, not on Keycloak's default ones.

## Is branding in authentication even important?

Whether it's an employee logging into an internal tool or a customer signing into your product, seeing the same logo, colors and tone every time reinforces the company's image. Every login becomes more consistent, and that leaves a more positive picture of your brand over time.

There's also perceived security. A login page that matches the brand feels safer. A generic, out-of-the-box Keycloak page, for example, can look like a hand-off to a third-party service, and that mismatch is enough to make careful users hesitate. CloakStudio gives you a fully white label Keycloak login and complete control over your Keycloak branding, so authentication looks and feels like the rest of your digital experience, not a step outside of it.

- **Unlike code-first tools like Keycloakify**, which require React and CSS to build a theme, CloakStudio needs no code at all. If you can use Canva, you can redesign Keycloak.
- **Unlike lighter tools like Keycloak Quick Theme**, which only let you tweak colors and logos, CloakStudio gives you full control over every screen and layout, not just the surface.

## Without CloakStudio / With CloakStudio

| Without CloakStudio | With CloakStudio |
|---|---|
| Every Keycloak screen ships with the same generic default look | Every screen matches your brand — logo, colors, layout and components |
| Customizing a theme means writing FreeMarker templates and CSS by hand | Design visually, drag and drop — no code required |
| Login feels like a hand-off to a third-party service | Authentication feels like a native part of your product |
| Only developers can touch the theme | Anyone — brand managers, designers, admins — can build it |
| Re-checking compatibility by hand on every Keycloak update | Design once with CloakStudio, stay compatible as Keycloak evolves |

## Features

- 🎨 **Visual, drag-and-drop editor** — no FreeMarker, no CSS
- 🖥️ **Live preview** — desktop, tablet and mobile, before you deploy
- 🔌 **Connects to your Keycloak** — use your existing instance, or let CloakStudio set one up
- 🧩 **Component library** — pre-built elements for every authentication screen
- ↩️ **Real editor, not a one-shot generator** — undo/redo, copy/paste, duplicate, reorder
- 🌍 **Localized editor** — Italian and English
- 🚀 **Guided deployment flow** — design, connect, deploy, done

## What you can customize

The visual builder covers eight authentication pages:

- Login
- Registration
- Forgot password
- Reset password
- Magic Link request
- Magic Link verify
- Success
- OTP / 2FA

## Editor capabilities

- Component library, organized by category and searchable
- Canvas with drag-and-drop, with insertion zones before, inside and after existing elements
- Tree view for selecting and reordering nested elements
- Property panel with basic and advanced modes
- Undo/redo history, copy/paste, duplicate, delete, hide, lock and reorder
- Live preview across desktop, tablet and mobile viewports
- Localized editor text in Italian and English

## Design tokens

CloakStudio themes are built on a standard design-token system, not one-off CSS hacks:

- Style values accept `px`, `%`, `vh`, `vw`, `rem` and `em` units
- Responsive properties organized per breakpoint: desktop, tablet, mobile
- Visual states covered: hover, focus, active, disabled, error, success, loading
- Sensible defaults out of the box (base font, colors, radius, shadow) that you fully override in the editor

## About

CloakStudio is part of the AYCC Auth's own authentication module, so it's designed around real Keycloak deployments, not just theory. Already using AYCC Auth? CloakStudio works there too, alongside any other Keycloak instance you run.

Stop maintaining your custom Keycloak theme by hand. Design once with CloakStudio, and we'll keep it compatible with Keycloak as it evolves.

## FAQ

**Do I need to write code to build a theme?**
No — CloakStudio is a fully visual, drag-and-drop builder. No FreeMarker, no CSS.

**Can I connect CloakStudio to a Keycloak instance I already run?**
Yes. CloakStudio connects to your existing Keycloak instance, or sets one up for you if you're starting from scratch.

**Which Keycloak versions are supported?**
CloakStudio is compatible with Keycloak 26 and above.

**Can I preview my theme before deploying it?**
Yes — CloakStudio includes a live preview across desktop, tablet and mobile before you deploy.

**What happens when Keycloak updates?**
Design once with CloakStudio, and it stays compatible with Keycloak as the platform evolves, without manual rework on every update.

**Who is CloakStudio built for?**
Brand managers, designers, product owners and admins, not just developers.

## Getting started

CloakStudio is a hosted product — there's nothing to clone or build here.

1. Download AYCC Auth
2. Connect it to your existing Keycloak instance, or let it set one up for you
3. Design your theme visually and deploy it to your realm

## License

This repository (documentation only) is © All You Can Cloud. CloakStudio is a commercial product — see the [website](https://allyoucancloud.com) for details and terms.
