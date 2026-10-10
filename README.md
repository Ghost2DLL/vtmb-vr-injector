# Ghost2DLL — VTMB VR Injector

First Playable Release Available!

The first playable version of BloodlinesVR is now available for download!

After two weeks of development, Vampire: The Masquerade – Bloodlines can finally be experienced in immersive stereoscopic VR using Meta Quest 3 and Virtual Desktop.

This is an early experimental release, and there’s still a lot of work to do.

Current limitations:

* Performance and FPS still need significant improvements.
* Some pre-rendered sequences are not yet properly handled in VR.
* Certain interactions, particularly with in-game computers, still require keyboard input.
* Additional improvements to VR controls, rendering and gameplay are planned.

Tested configuration:

* Vampire: The Masquerade – Bloodlines (Steam)
* Unofficial Patch 11.5
* Italian translation mod
* Meta Quest 3
* Virtual Desktop

Download

The first playable build is available in the Releases section of this repository.

Important: This is an experimental work-in-progress build, not a finished VR conversion. Feedback and bug reports are welcome!

### Experimental PC VR injector for Vampire: The Masquerade – Bloodlines

Ghost2DLL is an experimental project aimed at bringing **Vampire: The Masquerade – Bloodlines** to PC VR while keeping the original game and its engine as the foundation.

## Development preview

Early footage from the current **Ghost2DLL VTMB VR Injector** development build.

[![Ghost2DLL VTMB VR Injector - Development Preview](https://img.youtube.com/vi/6mkSutSAaLg/maxresdefault.jpg)](https://youtu.be/6mkSutSAaLg)

▶️ **[Watch the development preview on YouTube](https://youtu.be/6mkSutSAaLg)**

> **Work in progress.** This footage shows an early development build and does not represent final VR rendering, interaction or performance.
The project is currently at a **very early stage of development**.

This is a hobby project developed in my spare time, driven by my love for Vampire: The Masquerade and by the belief that Bloodlines could be an exceptional game to experience in VR.

Development time is therefore limited, and I cannot currently make promises about a release date or how far the project will ultimately go.  
The goal, however, is to investigate whether Bloodlines can be turned into a genuinely playable PC VR experience.

---

## The idea

Rather than rebuilding Bloodlines in another engine, Ghost2DLL is being developed as a **VR injection layer for the original PC game**.

Conceptually:

```text
Vampire: The Masquerade – Bloodlines
                |
                v
       Original game engine
                |
                v
       Ghost2DLL VR Injector
                |
                v
             OpenXR
                |
                v
              PC VR
Required Unofficial Patch

BloodlinesVR was developed and tested with Vampire: The Masquerade – Bloodlines Unofficial Patch 11.5.

For compatibility, use version 11.5 rather than the newer 12.0 release.

The original 11.5 installer is available in this repository’s Releases section, credited to Wesp5 and the original contributors.

A legitimate copy of Vampire: The Masquerade – Bloodlines is required.