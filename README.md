# Shifu

Build pandas scripts by stacking blocks.

Drag blocks like filter, parse datetime, regex extract, merge and group into a recipe and watch the DataFrame change at every step. Shifu writes the matching pandas as you go, so you can export a .py or a notebook, and sends results straight to Recap or Spoke. Starts with six recipes for EvtxECmd, Hayabusa, PECmd and MFTECmd output.

**Good for:** Triage on EZTools and Hayabusa CSVs, and learning pandas one step at a time.

**Live:** https://jon.glass/shifu/

A single self-contained page with no build step. Open `index.html` or serve the folder over HTTPS.

Uses the shared suite script at `/assets/suite/handoff.js` from [jon.glass](https://jon.glass) to pass data between tools, so cross-tool handoff only works when served from jon.glass.
