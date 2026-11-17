# Updated browser example

Added 17 November 2026 as a new, project-specific interaction. It is separate from the recovered software and is not the students' implementation.

## What runs

Play a new cannon-and-trampoline level with adjustable launch speed, angles and trampoline position.

The simulation uses gravity, fixed time steps and a line-segment bounce. It does not use Box2D or reproduce the original levels. The original report, image and student-supplied source link remain available in the repository.

## Run

Open https://twerdster.github.io/smartphone-game/ or serve the repository's `docs/` directory with any static HTTP server. For example, from the repository root:

```sh
python3 -m http.server 8000 --directory docs
```

Open `http://localhost:8000`. The demo uses standard Canvas 2D and local browser controls. No additional demo packages, SDKs or credentials are required. No camera permission is requested.

## Implementation

`docs/index.html` contains the controls and factual scope labels; `docs/demo.js` implements the interaction; `docs/demo.css` contains the responsive layout. All generated images/data are illustrative. This is an independent game with new vector artwork and simplified physics, not a port of the students’ code, assets or levels.

## Recorded checks

[VALIDATION.json](VALIDATION.json) records 9 passed browser assertions on the new interaction, JSON export where present, local-only requests, error-free JavaScript and a 390-pixel responsive layout. These are interaction assertions on generated/local examples, not accuracy or compatibility benchmarks. Original native application/hardware coverage is unchanged; see [historical recovery notes](../docs/RECOVERY.md).

## Attribution and terms

Original project: Liav Sitruk, Idan Banani. Supervision: Aaron Wetzler. The new browser example was prepared with Codex assistance in November 2026; Claude reviewed the README wording and factual scope. The new files have a [scoped MIT license](../docs/DEMO-LICENSE.txt); it does not relicense historical code, images, slides, reports or third-party dependencies.

The default shot (25° cannon angle, 500 px/s, −20° trampoline angle) was advanced through the simulation and verified to touch the trampoline and then the target. The check establishes one playable trajectory in this simplified level; it does not reproduce historical Box2D behavior.
