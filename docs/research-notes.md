# tmux for UITARS15_v2: Action Grounding Adapter

## Purpose

This document records the research framing behind the static GitHub Pages site. The project studies how tmux can be adapted for UITARS15_v2 as a durable terminal substrate for agentic work.

## Research Question

How should UITARS15_v2 ground terminal actions when the visible workspace is a changing lattice of tmux panes?

## Working Thesis

The adapter provides pane-aware action grounding so the agent can separate visual terminal layout from command intent and task progress.

## Design Claims

- Pane segmentation is treated as part of the observation model.
- Keyboard actions are resolved against active pane and command phase.
- Trace metadata records grounding confidence for later analysis.

## Evaluation Lens

- Focus targeting accuracy
- Command phase recognition
- Grounding confidence under dense pane layouts


## Threats to Validity

- Terminal state can be over-instrumented, causing an adapter to measure artifacts of the harness rather than real agent behavior.
- A final successful artifact may hide poor recovery behavior, repeated command attempts, or fragile focus management.
- Agent-specific adapters can become difficult to compare unless trace schemas remain explicit and documented.

## Hero Image Prompt Summary

A 700x500 academic technical illustration for tmux adaptation research with UITARS15_v2, emphasizing terminal panes, agent traces, reproducible evaluation, and a serious research discussion style. The generated image was copied into `docs/assets/hero.png` and normalized to 700x500 pixels.
