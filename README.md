# Newton Playground

Interactive 2D physics sandbox in the browser. Verlet integration, spring-mass constraints, rigid body collisions — no dependencies.

## Features

- **Rigid bodies** — circles and boxes with realistic collisions and bounce
- **Spring-mass connections** — zigzag-rendered springs with strain visualization
- **Pin constraints** — fix any body in space
- **Static walls** — draw collision surfaces
- **7 presets** — Pendulum, Bridge, Cloth, Stack, Chain, Newton's Cradle, Wrecking Ball
- **Interactive** — click to spawn, drag to throw, right-click to delete
- **Tunable physics** — gravity, damping, bounce, stiffness, substeps
- **Touch support** — works on mobile

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `1-5` | Select tool (Circle/Box/Spring/Pin/Wall) |
| `Space` | Pause / play |
| `G` | Toggle gravity |
| `C` | Clear scene |
| Right-click | Delete body |

## Tech

Pure JavaScript + Canvas 2D. Verlet integration with constraint solving. No frameworks, no build tools, no dependencies.

## Run

Open `index.html` in any browser.
