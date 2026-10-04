# NEXUS — Turn Chaos Into Your Next Move

NEXUS is an adaptive AI decision-engine prototype for the Miro × Qwen event.

## Run
Open `index.html` in a browser. Enter a goal, deadline, available time and energy, then click **RUN NEXUS**.

## Core idea
Instead of producing a long task list, NEXUS identifies the biggest friction and recommends **ONE high-impact next move** that fits the user's real constraints.

## Qwen
The UI is designed for Qwen/ModelScope integration. This submission includes a local fallback decision engine so the demo remains functional without exposing an API key in browser code. For production, call Qwen from a secure backend and never place the API key in frontend JavaScript.

## Stack
HTML + CSS + JavaScript; Miro for visual product flow/presentation; Qwen as the intended reasoning layer.
