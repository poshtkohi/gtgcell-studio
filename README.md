<p align="center"><img src="assets/gtg-logo.png" width="82" alt="GTG Cell Studio logo"></p>

<h1 align="center">GTG Cell Studio</h1>

<p align="center"><strong>A Windows research workspace for ion-channel modelling</strong></p>

<p align="center"><a href="https://github.com/poshtkohi/gtgcell-studio/releases/download/v0.8.13/GTG.Cell.Studio.Installer.exe"><strong>Download for Windows x64</strong></a> Â· <a href="https://www.gtgcell.com">Project website</a></p>

![Ion-channel illustration](assets/ion-channel-artwork.png)

GTG Cell Studio brings model editing, experimental-data inspection, simulation, fitting and scientific figures into one application. The GTG research papers are currently in preparation.

This repository is a download page for the **compiled application**. The GTG IDE, fitter and framework implementation sources and the theory/language manuals are not published here.

## Evaluation access

An installation key is required. Request access from **Dr Alireza Poshtkohi**, [a.poshtkohi@herts.ac.uk](mailto:a.poshtkohi@herts.ac.uk). Keys are issued privately; do not post them in public issues or screenshots.

Limited evaluation supports model editing, data inspection, Parse, Simulate, Fit and scientific figures. Full access also provides built-in Help, Copilot and guides within the authorised installation. Full-access guides are not offered as separate public downloads. Optional Copilot needs the user's own provider configuration.

## Install and run

1. Download **GTG.Cell.Studio.Installer.exe** from the [current release](https://github.com/poshtkohi/gtgcell-studio/releases/tag/v0.8.13).
2. Run the installer normally, enter your issued key and check the access level shown. The per-user installation does not request administrator rights.
3. Open **GTG Cell Studio** and **Examples** from the Start menu folder. Open the supplied small example, then choose **Parse** followed by **Simulate**.

The package includes its compiler, build tools, runtime dependencies, PDF support and examples. No separate MATLAB, compiler or TeX installation is needed for the supplied workflows.

**Installer targets:** Windows 10 version 1809/build 17763 or later, x64; Windows 11 x64. Allow about 3 GB plus space for projects and results. No Linux, macOS, 32-bit Windows or native ARM64 package is supplied. An independent fresh Windows 10 VM check remains pending.

**Unsigned research release:** Windows SmartScreen may warn about this download, and organisational application policies may restrict installation. Check the published checksum and follow your organisation's software policy. Signing has not been claimed for this release.

Keep your projects outside the application directory. Updates preserve existing writable example-workspace files. Uninstall removes the owned application folder and Studio settings/shortcuts while preserving outside user files. Full-to-Limited changes require uninstalling first.

## Verify the installer

Version **0.8.13** Â· **412,603,296 bytes** Â· SHA-256:

```text
E5AAFB10EB08ACE90CC5823C49FDCEAE64E5C2E1A671423D0C0C8D2F59227BDA
```

The release's [SHA256SUMS.txt](https://github.com/poshtkohi/gtgcell-studio/releases/download/v0.8.13/SHA256SUMS.txt) lists the checksums of its downloadable assets.

## Required third-party materials

[Third-party dependency sources](https://github.com/poshtkohi/gtgcell-studio/releases/download/v0.8.13/GTG-Cell-Studio-Third-Party-Sources-0.8.13.zip) are supplied for Qt, GCC and other bundled components. **That ZIP contains dependency sources and build material, not GTG application implementation or theory manuals.** It is unencrypted and needs no Studio installation key.

Read [LICENSE-NOTICES.txt](https://github.com/poshtkohi/gtgcell-studio/releases/download/v0.8.13/LICENSE-NOTICES.txt) and [THIRD-PARTY-SOURCES.txt](https://github.com/poshtkohi/gtgcell-studio/releases/download/v0.8.13/THIRD-PARTY-SOURCES.txt) for component rights, source coverage and provenance limits. Third-party licence rights remain independent of GTG access keys. Compatible replacement Qt libraries/plugins may be used under their licences.

GitHub also automatically supplies archives labelled **Source code** for release tags. Those archives contain only this public download-page repository and branding files; they do not contain the GTG framework or manuals.

GTG Cell Team: Dr Alireza Poshtkohi, Professor Mark L Dallas and Dr Moza Al-Owais. Direct questions to [Dr Alireza Poshtkohi](mailto:a.poshtkohi@herts.ac.uk).

Copyright Â© 2026 GTG Cell Team. [www.gtgcell.com](https://www.gtgcell.com)
