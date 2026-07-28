# Project Charter - Natiq Frontend

**Last Updated**: [Date]
**Version**: 1.0.0
**Status**: In Progress

---

## 1. Project Identification

| Field                  | Value                               |
| ---------------------- | ----------------------------------- |
| **Project Name**       | Natiq Frontend                      |
| **Project Repo**       | natiq-frontend                      |
| **Project Manager**    | [ekiuse](https://github.com/ekiuse) |
| **Development Team**   | Frontend                            |
| **Start Date**         | 2022-09-01                          |
| **Estimated End Date** |                                     |

---

## 2. Vision and Goals

### Vision

The primary point of contact for users with Natiq—a modern gateway that builds trust through exceptional design and seamless UX, paving the way to our services.

### High-Level Goals

- Develop and maintain a high-performance, responsive, and SEO-friendly landing page (homepage) for the Natiq website.
- Provide a reusable UI component library and design system (tokens, typography, layout) to be consumed by other Natiq frontend projects.

---

## 3. Project Scope

### In-Scope

- Developing the main landing page layout, hero sections, and public sub-pages (e.g., About, Contact, Blog index).
- Establishing global design tokens (colors, typography, spacing, breakpoints) and a cohesive design system.

### Out-of-Scope

- Core business logic and feature development for downstream applications (e.g., user dashboard, admin panel, payment gateways, or analytics modules).

---

## 4. Architecture & Technologies

### Frontend

- **Framework**: React(PWA)

**Features as Template**:

- Installable PWA
- Handle Online, Connecting... & Offline Bar
- Check Ping and Status of Multi Servers
- Get Domain from ENV
- Control Global Contexts
- Control Cross Domain Cookies
- Common UI Comps
- Default Header + Menu & Footer
- Default 5 Tab pages with header, Desktop & Mobile
- Connected to Natiq API
- Get data from API and cathe
- Routing System
- Settings Tab:
  - Theme Handling
  - Language selection
  - Update/Reset Button

#### URLs

- /
- /launcher
- /launcher/settings
- /iframe

### Infrastructure

- **CI/CD**: GitHub Actions
- **Hosting**:
  - Single standalone server (Linux) running Docker
  - AWS
- **Docker available containers**:
  - natiq-frontend

---

## 5. Pending Decisions

TBD

---

## 6. Timeline

TBD

---

## 7. Risks & Challenges

TBD

---

## 8. Success Metrics

TBD

---

## 9. Budget & Resources

- **Human Resources**: 1 developer
- **Hardware/Software Resources**: 1 server

---

## 10. Approval Signatures

| Role            | Github Account                                    |
| --------------- | ------------------------------------------------- |
| Curator         | [Al-Abd](https://github.com/al-abd)               |
| DevOps          | [codebysilence](https://github.com/codebysilence) |
| Project Manager | [ekiuse](https://github.com/ekiuse)               |
