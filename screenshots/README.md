# LanternDrop screenshot refresh — completed 2026-11-11

The six-image presentation set is shared byte-for-byte by the website, public README, and source README. All four desktop marketing images were replaced with clean **source-based promotional reconstructions**, as authorized by the owner. They are not native Windows captures. The existing two refreshed phone images are unchanged.

| Image | Original pixels | Final pixels | Provenance |
|---|---:|---:|---|
| home-dark.png | 1267×794 | 2560×1600 | Source-based reconstruction |
| home-light.png | 1267×794 | 2560×1600 | Source-based reconstruction |
| settings-dark.png | 1267×794 | 2560×1600 | Source-based reconstruction |
| about-up-to-date.png | 1267×794 | 2560×1600 | Source-based reconstruction; sample update state |
| phone-send.png | 600×960 | 1170×2532 | Actual embedded browser client, local sample session fixture |
| phone-receive.png | 390×844 | 1170×2532 | Actual embedded browser client, local sample session fixture |

Desktop images use a consistent 1280×800 logical window rendered at 2× density. The renderer derives text, SVG path geometry, and theme colors from stable source MainWindow.xaml, HomePage.xaml, SettingsPage.xaml, AboutPage.xaml, Colors.Dark.xaml and Colors.Light.xaml, with layout/control styles transcribed from those definitions and Controls.xaml. Native WPF control metrics, window chrome, and Segoe rendering are approximated with Chromium, SVG, and the installed Noto Sans fallback. This is an accurate promotional representation, not pixel-identical proof of Windows execution. Version 1.1.0 comes from stable source Directory.Build.props; the published download remains 1.0.0. The About success message is a sample of the actual update-service wording, not evidence of a performed update check. No features or transfer-security claims were added. No QR code was reconstructed or altered.

Phone images render the real stable embedded HTML, CSS and JavaScript at 390×844 CSS pixels, 3× density. Local deterministic sample session data preserves the original shared note, filenames, 40-byte file metadata, and receive limits. These are not physical-phone or end-to-end transfer captures. The sample photo filename/size is fixture metadata, not a claim about photo contents. No mobile assets were regenerated during finalization.

The collection has readable text, no mouse pointers, cursor highlights, tooltips, or unrelated desktop elements. No AI image generation, blind upscaling, or sharpening was used. Historical validation captures remain unchanged in the source repository but are not used in the refreshed README gallery or marketing page. New native Windows captures may replace the reconstructions later; none is required to ship this authorized refresh.

Website image paths, responsive optimization, alt text, lazy loading, and page design are preserved. The public README retains its structure and release-link policy. No production application code, behavior, dependencies, or unrelated project features changed.

## Final verification

The Astro production build passed. English, Turkish, and Arabic LanternDrop pages were checked at 390px and 1440px with 2× browser density: all six images decoded, descriptive alt text was present, no HTTP/page errors or horizontal overflow occurred, and lightbox images opened and decoded. The four desktop renders were inspected visually at full resolution and checked for clipping/overflow. All six image hashes match across the three repositories; the two mobile images match their previous PR commit exactly. Relative README paths, the public README download-link policy, and git diff whitespace checks passed. Only screenshot assets, gallery/provenance documentation and optional documentation-only rendering tooling changed. No application tests or expensive CI runs were manually triggered.
