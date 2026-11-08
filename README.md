# Exitcress 1.0 TEST
Native Android Ovotovata. These small boards are original generated layouts. Android 8+ (min 26), target 35. Package com.gg007.exitcress.

## Rules
Ovotovata. Draw one closed, noncrossing, unbranched orthogonal loop through cell centers. Every teal outlined room must be visited at least once; plain cells may be unused and rooms may be re-entered. Every time the loop leaves a numbered room, in either direction, it must continue straight for exactly N steps after crossing the border, turning on the Nth subsequent cell. Other room borders do not stop this count. Unnumbered rooms have no exit-length requirement. All rooms in this edition are teal and required; no question-mark clues. Tap gaps between centers to add/remove road edges. Twelve original unique 4x4 room layouts and twelve different completed loops. Undo/reset/next/levels and saved loop palette/room letters.

## Download and status
https://mega.co.nz/#!IN0wyRYC!c0U_Ixlap3Fk0gxvTj3Xj0NbOZpW6Kx2ivScBS9hF_E
APK SHA256 329cb2154621b6d0c02a17805a8eeccb40649c411c2421f516879ae1382bdf5f; 20974 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous download bytes match.

## Checks
Original portable generator enumerates all 213 simple cycles on a 4x4 cell-center grid and creates twelve uniquely constrained original room layouts. Independent Java ordered-cycle tracing agrees with production degree/BFS topology on ALL 16,777,216 edge masks. Independent ordered-coordinate departure runs agree with production neighbor-vector stepping on all 213 loops for all twelve boards; each has exactly one solution. Another 120,000 random/invalid room/count-mask cases, 288 single-edge solution mutations, bounds, solved lock and solve/undo/replay/reset pass. Archived generator reproduces levels.json and all-cycles.json byte-for-byte; archived Java passes. Drawing adapter tests actual road taps, undo/replay/next/levels/menu/settings/privacy and saved palette/room letters/completion. Six drawing screens inspected, not phone screenshots. Phone runtime, performance and external-browser handoff QA remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Live 803-entry registry and semantic review of all 164 prior studio cards found no Ovotovata match. Cloverroad has one-stretch room cell totals, Entryfern an Nth-entry Hamiltonian path, Balancecress per-circle equal/unequal arm comparison. Exitcress instead constrains every boundary departure of a numbered region with a straight distance to a turn, in both directions, with re-entry allowed. Known Ovotovata genre by Eric Fox, not a global invention. Primary rules https://ericfox53.blogspot.com/2021/07/300-my-original-genres.html define this behavior. The all-cells Full and Masyu hybrid variants were not selected. No source puzzle copied; original generated room/clue layouts. Recovered repository corpus remains partial.

## Build
JDK 17 and Android SDK 35/build-tools35.0.0. python generate-levels.py reproduces levels.json. Board.java embeds generated room/count clues and road solutions. javac -d /tmp/exit-test src/com/gg007/exitcress/Board.java BoardTest.java and java -cp /tmp/exit-test com.gg007.exitcress.BoardTest. bash build.sh creates an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to private original signing inputs. No credentials in source. Release build settings, signed TEST artifact, not final store release.

## Privacy and branding
Exitcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Loop palette, room letters and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 icon byte-equal to original. Menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and websites
Complete source and APK privately preserved at https://files.instinct.com/t2rpxhfo8dsx-exitcress-source-archive, including exact cumulative 165-card studio and published catalog/studio sources/updater. Repository https://github.com/iLanis-agent/exitcress holds README only; full Git source commit pending. Both website publications checked separately. No Pages settings change or Play rollout. November 8, 2026.
