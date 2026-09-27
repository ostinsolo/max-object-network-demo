# Max Object Network — Public Demo

Interactive browser demo of **Max Object Network**, a 3D knowledge graph for exploring Max/MSP, MSP/DSP, Jitter and Max for Live objects, references and reconstructed help patches.

## What this demo includes

- 3D Three.js / React object graph
- 2,911 indexed objects in the current public snapshot
- object search, categories, filters and graph relationships
- reference / See Also navigation
- static Help Patch previews and the large bottom patch viewer

## Demo limitation

This GitHub Pages build is a **static browser demo**. Max objects are not executed here: MSP/DSP does not process audio, Jitter does not execute matrix/video/GPU processing, and Max for Live does not control Ableton Live. Help patches are visual browser reconstructions rather than running Max patchers.

The full product is being developed as an executable browser-based Max/MSP-style environment in which supported Max, MSP/DSP, Jitter and related object families can run and interact.

## Public/private boundary

This repository intentionally contains only the compiled public demo and a sanitised static dataset. The private R&D source, corpus-generation pipeline, binary-analysis and reverse-engineering tooling are not published here.
