# saltFrame releases

Builds of saltFrame for macOS, and the update feed the app reads.

- **Install:** download the latest `.dmg` from [Releases](../../releases), open it, and drag saltFrame to Applications.
- **Updates:** saltFrame checks `appcast.xml` in this repo once a day (and from saltFrame › Check for Updates…).
  Every build is signed with Moonlabor's Developer ID, notarized by Apple and signed with the saltFrame update key;
  the app refuses anything else.
- **Versions:** `saltFrame <version> (<build>)`, tagged `v<version>-<build>`. The build number only ever goes up;
  updates follow it.
- **Needs:** macOS 27 on an Apple silicon Mac.

saltFrame was called saltROOM until October 2026. It is in a private alpha. This repository holds no source code:
only the update feed and release notes.
