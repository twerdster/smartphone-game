# Material provenance

The 16-page Spring 2012 report and historical game image were recovered from the project records associated with Aaron Wetzler's former Technion website. They remain unchanged in `docs/report.pdf` and `assets/project-preview.jpg`.

On 12 November 2026, Idan Banani supplied [a source repository on his GitHub account](https://github.com/IdanBanani/iOS-4-2D-game-for-iPad). Aaron chose to link to that repository. No application code or game assets have been imported into this archive.

## Source inspection

The documentation update inspected [commit `270b45c`](https://github.com/IdanBanani/iOS-4-2D-game-for-iPad/tree/270b45ce6a1e149209e1d595e492766ede3b7747) on 13 November 2026:

- Application files include Objective-C `.m` and Objective-C++ `.mm` sources, with bundled C/C++ libraries and image/audio assets.
- `CreditLayer.m` reads “This is Liav Sitruk & Idan Bannani Project” and names Aaron Wetzler as supervisor. This archive uses “Banani”, the spelling in Idan's reply and GitHub account.
- `libs/cocos2d/cocos2d.m` reports `cocos2d v1.0.1`. `libs/Box2D/` contains a bundled Box2D library.
- The complete inspected file tree contains no `.xcodeproj`, `.xcworkspace`, `project.pbxproj`, Makefile or Podfile. Resource configuration such as plist files is present. The report's Xcode 4.3.2 and iOS 4-or-later requirements describe the original project environment, not a reproduced build.
- `libs/LICENSE_*.txt` files cover bundled dependencies. No root application-wide license was identified, and dependency licenses do not establish the terms for the students' game code or artwork.

The inspection checked file contents and repository structure. It did not build, launch or test the game, establish compatibility with current Xcode/iOS, or verify that this is the final submitted version.
