# smartphone-game: maintenance context

Read this file, then SKILL.md, README.md and linked recovery/provenance records. Current update: 17 November 2026.

The students built a touch-controlled iPad physics game with Cocos2D and Box2D: launch balls, adjust trampolines and reach targets.

## Original material

The 16-page Spring 2012 report and original image are preserved. Idan supplied an external source repository; its inspected revision lacks an Xcode project, and no current build is recorded. Original source, submodule pins, images, reports, slides, notices and author-response records are unchanged. [Historical implementation and recovery notes](docs/RECOVERY.md) retain the earlier setup and failed-build evidence; existing PROVENANCE.md or source/PROVENANCE.json remains authoritative where present.

## Updated demo

Play a new cannon-and-trampoline level with adjustable launch speed, angles and trampoline position. This is new independent JavaScript/Canvas code in docs/, not a restored or ported historical application. This is an independent game with new vector artwork and simplified physics, not a port of the students’ code, assets or levels.

Run https://twerdster.github.io/smartphone-game/ or `python3 -m http.server 8000 --directory docs` from the repository root. No build, account, SDK or external service is required. Serve docs/ as the GitHub Pages source.

## Checks and review

updated/VALIDATION.json records 9 passing Chromium browser assertions for the new demo, including responsive layout checks; these are scoped interaction checks on synthetic/local examples. No original native build, sensor accuracy or physical-mobile/Safari/Firefox coverage was added. Two Claude CLI editorial passes reviewed the concise README and new-demo guide; useful wording and scope qualifications were checked against code and recovery records. Detailed review records are private.

Preserve attribution, original bytes and licensing boundaries. New demo code has a scoped MIT license in docs/DEMO-LICENSE.txt; it does not cover historical materials or third-party dependencies. Correspondence, personal contact data and machine-specific setup details stay private. Before every commit review and synchronize this file and SKILL.md.
