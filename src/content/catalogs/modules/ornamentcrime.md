---
id: ornamentcrime
title: "ORNAMENT & CRIME"
link: "https://www.tangiblewaves.com/store/p154/ORNAMENT_%26_CRIME.html"
imglink: ORNAMENT_CRIME.png
---




This is a clone of a special and well-known Eurorack module, which offers a hundred ways of processing and generating CV and modulation signals. The AE version behaves in any way just like the Eurorack module (except for the ability of processing negative voltages which simply don't exist in AE) and may well become the brain in your rack. The module is based on a Teensy 3.2 microcontroller board and can easily be reprogrammed. You can choose whether to get the original firmware or the alternative Hemisphere Suite pre-installed.

Module power consumption: 60 mA



## Inputs

*   **CV 1, 2, 3, 4** - Input channels for CV signals. It depends on the currently active mode what these are for.
*   **TRIG 1, 2, 3, 4** - Input channels for trigger signals. It depends on the currently active mode what these do.

## Outputs

*   **OUT A, B, C, D** - CV or trigger outputs depending on the currently active mode.

## Controls

These controls are generic and do different things depending on which firmware is installed and which mode is currently active.

*   **Button Up**
*   **Button Down**
*   **Left Knob**
*   **Right Knob**

## Original Firmware

The original firmware can be found here: [https://github.com/mxmxmx/O\_C](https://github.com/mxmxmx/O_C)

The official manual for the original firmware is here: [https://ornament-and-cri.me/user-manual-v1\_3/#overview](https://ornament-and-cri.me/user-manual-v1_3/#overview)

The following modes are available with the original firmware:

*   [CopierMaschine](https://ornament-and-cri.me/user-manual-v1_3/#anchor-copiermaschine) - is an enhanced version of a quantising four stage analogue shift register (ASR)
*   [Harrington 1200](https://ornament-and-cri.me/user-manual-v1_3/#anchor-harrington-1200) - provides basic neo-Riemannian Tonnetz transformations of triadic chords, triggered by the digital (gate/trigger) inputs.
*   [Automatonnetz](https://ornament-and-cri.me/user-manual-v1_3/#anchor-automatonnetz) - combines Tonnetz transforms with a “vector” sequencer - it can be both a chord sequencer and a melody sequencer, but not of the usual kind.
*   [Quantermain](https://ornament-and-cri.me/user-manual-v1_3/#anchor-quantermain) - is a quad pitch quantiser for external voltages, with editable scales; it can do clocked (trigger-driven) quantising, or continuous quantising, with a latency of under 100 microseconds; it also features quad Turing Machines, May-Verhulst logistic maps or byte beats as optional, semi-random, internally generated CV sources.
*   [Meta-Q](https://ornament-and-cri.me/user-manual-v1_3/#anchor-meta-q) - is a dual-channel quantiser, similar to Quantermain, but also offering scale and note mask sequencing.
*   [Quadraturia](https://ornament-and-cri.me/user-manual-v1_3/#anchor-quadraturia) - is a wavetable quadrature LFO, based on the “Easter egg” in the Mutable Instruments Frames module.
*   [Low-rents](https://ornament-and-cri.me/user-manual-v1_3/#anchor-low-rents) - is a dual Lorenz and Rössler (strange attractor) modulation generator, partially based on the “Easter egg” in the Mutable Instruments Streams module.
*   [Piqued](https://ornament-and-cri.me/user-manual-v1_3/#anchor-piqued) - is a quad voltage-controlled envelope generator, based on envelope generator code from the Mutable Instruments Peaks module, but extending it with voltage control, additional envelope types, including re-triggering (looping) envelopes, additional segment shapes, adjustable trigger delays, and a unique Euclidean “trigger filter” which turns the app into a Euclidean rhythm generator which can output envelopes, not just gate or trigger pulses.
*   [Sequins](https://ornament-and-cri.me/user-manual-v1_3/#anchor-sequins) - is a dual-channel step sequencer offering 4 “tracks” of up to 16 steps each; tracks can themselves be sequenced.
*   [Dialectic Ping Pong](https://ornament-and-cri.me/user-manual-v1_3/#anchor-dialectic-ping-pong) - is a quad bouncing ball envelope generator, based on a hidden mode of the Mutable Instruments Peaks module.
*   [Viznutcracker, sweet!](https://ornament-and-cri.me/user-manual-v1_3/#anchor-viznutcracker-sweet) - is a quad “byte beat” equation generator, which can be used as an audio source to generate curious but often interesting 8-bit noises and tunes, or which can be clocked by an external source to produce “byte beat” control voltage sequences. “Byte beats” were first described in 2011 by viznut (aka Ville-Matias Heikkilä).
*   [Acid Curds](https://ornament-and-cri.me/user-manual-v1_3/#anchor-acid-curds) - is both a chord quantiser (sometimes called a “harmonic quantiser” for external pitch voltages), and a chord progression sequencer.
*   [References](https://ornament-and-cri.me/user-manual-v1_3/#anchor-references) - is a utility app that outputs specific reference voltages on each channel to help tune or calibrate VCOs and other modules. It also includes a high-precision frequency meter and note tuner, a high-precision BPM (beats per minute) tempo meter, and a closed-loop calibration mode.

## Alternative Firmware - Hemispheres Suit

This is an alternative firmware which you can install instead of the original. Just follow the instructions in this manual: [https://github.com/Chysn/O\_C-HemisphereSuite/wiki](https://github.com/Chysn/O_C-HemisphereSuite/wiki)

Synthdad presents this in detail in this video: [https://youtu.be/dg\_acylaMZU](https://youtu.be/dg_acylaMZU)

The following video is a great overview of the different applets in the Hemisphere Suite: [https://youtu.be/mtO5Ua12pgg](https://youtu.be/mtO5Ua12pgg)

Here is the manual for all applets: [https://synthmodes.com/modules/o\_c\_hemisphere/](https://synthmodes.com/modules/o_c_hemisphere/)

## Patch Suggestions

If you have problems wiht the output CVs being too high, try calibrating the module, as per this thread on the forum:-

[https://forum.aemodular.com/thread/2081/cv-output-high-stock-firmware](https://forum.aemodular.com/thread/2081/cv-output-high-stock-firmware)

Synthdad has a whole playlist on YouTube with tutorials and patch suggestions for various original modes and some Hemisphere applets:

[https://www.youtube.com/playlist?list=PL-oO\_kqREhTeKHHsymeiFvyEeRVmWj0BZ](https://www.youtube.com/playlist?list=PL-oO_kqREhTeKHHsymeiFvyEeRVmWj0BZ)



