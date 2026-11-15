# Smartphone Game

<p align="center">
  <img src="assets/project-preview.jpg" alt="Underwater-themed 2D physics game screen with a red ball, coral columns, cartoon sea creatures and a treasure chest, and a 'balls left: 8 / 8' counter" width="440">
</p>

![Platform: iPad (iOS)](https://img.shields.io/badge/platform-iPad%20%28iOS%29-lightgrey)
![Documents: 16-page report](https://img.shields.io/badge/documents-16--page%20report-informational)
![Source: external repository](https://img.shields.io/badge/source-external%20repository-informational)

An archive of the report for a Cocos2D/Box2D physics game for iPad, with a link to the source repository supplied by Idan Banani.

Students: Liav Sitruk, Idan Banani.

Supervision: Aaron Wetzler.

## Available materials

The [16-page Spring 2012 report](docs/report.pdf), *2D iOS Game*, describes a touch-controlled physics game developed with Cocos2D and Box2D. Its example level uses a cannon, balls, adjustable trampolines, obstacles and targets. The report documents scene organization, game-object classes and screenshots from the original implementation.

This repository contains the report and a historical game image. Idan Banani supplied [a source repository on his GitHub account](https://github.com/IdanBanani/iOS-4-2D-game-for-iPad) in November 2026. Source and assets are available in that repository and have not been copied here. The inspected copy has not been verified as the final submitted version.

## Use and validation

Read the report for the game structure and historical screenshots. The source is in the linked repository. The [inspected commit `270b45c`](https://github.com/IdanBanani/iOS-4-2D-game-for-iPad/tree/270b45ce6a1e149209e1d595e492766ede3b7747) contains Objective-C and Objective-C++ application files, bundled C/C++ dependencies and game assets. Its bundled Cocos2D implementation identifies itself as version 1.0.1. No `.xcodeproj`, `.xcworkspace` or `project.pbxproj` was found in that commit, so an Xcode project would need to be recovered or reconstructed before attempting a build.

The report records Objective-C, Xcode 4.3.2, Cocos2D for iPhone, Box2D and CocosBuilder, targeting an iPad with iOS 4 or later. These describe the historical environment. They have not been verified as a working setup for the linked source on a current system.

The report lists iPad testing as a project step but records no numerical or automated test results. No application build or gameplay test was performed during recovery.

## Links

- [Source repository supplied by Idan Banani](https://github.com/IdanBanani/iOS-4-2D-game-for-iPad)
- [Project entry on Aaron Wetzler's website](https://twerdster.github.io/#smartphone-game)
- [Material provenance and source inspection](PROVENANCE.md)

## Attribution and reuse

On 15 November 2026, Liav Sitruk individually approved keeping this archive with his attribution, using the project code and agent-assisted attempts to run or update that code. He supplied no additional source copy. See [author response and permission scope](PROVENANCE.md#author-response).

The credits above follow the archived project page. The linked source's `CreditLayer.m` credits the same students and supervisor, spelling Idan's surname “Bannani”. The linked repository includes third-party dependency license notices, but no application-wide license was identified in the inspected commit. This archive does not assign a license to that source, the recovered report or the historical image. Original authors can open an issue to contribute updates or request corrections or removal of their material.

Figure provenance: `assets/project-preview.jpg` is the original student-project game image from the archived project page on Aaron Wetzler's website, copied without modification. Any third-party characters or artwork shown remain the property of their owners.
