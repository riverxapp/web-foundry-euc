# Project Overview

This project is a deterministic frontend bootstrap built around a small set of core application and layout files.

## Current Scope

- Application entry and routing:
  - `src/main.tsx`
  - `src/app/routes.tsx`
- Page content:
  - `src/pages/home.tsx`
- Layout and navigation:
  - `src/components/layout/AppLayout.tsx`
  - `src/components/layout/Header.tsx`
  - `src/components/layout/Navbar.tsx`
  - `src/components/layout/Footer.tsx`
- Shared UI primitives:
  - `src/components/ui/navigation-menu.tsx`
  - `src/components/ui/sidebar.tsx`
- Supporting documentation:
  - `design.md`

## Goal

Provide a stable, reproducible project foundation with consistent structure across pages, layout, and navigation components.

## Constraints

- Keep changes deterministic and narrowly scoped.
- Preserve unrelated sections and existing project intent.
- Prefer implementation updates that align with the established component and routing structure.

## Success Criteria

- The listed files reflect the completed bootstrap execution.
- The project description matches the current repository shape.
- Future changes can build on the documented layout, navigation, and route organization without ambiguity.
