# Hunting Run — Gameplay17 Reactive Archery

[Play in your browser](https://wasiqnkhurshid.github.io/HuntingRunGame-Gameplay17/). No login or installation required. Choose **SHOOTING LAB → A PREDICTABLE / B REACTIVE → START / RESTART TEST**.

Both modes use the same simple tap shooting: fast physical arrows, moderate deterministic release-only assistance, actual obstacles and same-lane eligibility. Swipes anywhere, including on/across Shoot, move normally. Independent fingers can move and shoot. Holding never repeats. No charging, crosshairs or meters. Mouse/Enter shoot once; A/D or arrows move, W/Space jumps, S ducks, Escape pauses.

A uses standard animal movement. B adds seeded lane changes, a warned proximity dodge/leap, crossings and rises above suitable existing cover. All patterns recover. Turn cues precede significant movement by 300–350 ms. Cover is physically blocked/clear; no invulnerability or hit rolls. Late shots remain possible, and close collision trajectories restore standard motion. Repeated firing can still compensate; learn timing rather than an aiming minigame.

Defaults: Predictable, behavior proposal frequency 65%, assistance 75%, Accuracy 50, Range 40, seed 78213. Balanced reference: 125 m/s, gravity 0.8 m/s², 10° base cone and 0.14 m collision radius. Accuracy improves limited correction; Range opens earlier engagement without widening accuracy. The common observed-motion predictor does not know a forthcoming dodge.

Normal 90-second generated Jungle, 32 m/s, Closer camera, 99 arrows, zero experimental cooldown, normal health/pickups/obstacles and nonviolent clears. Shoot 84 dp and swipe threshold 18 dp remain unchanged. Optional behavior/result diagnostics are OFF by default. RESET LAB restores defaults; Pause → Shooting Lab → Start repeats the selected seed with 99 arrows. Frequency is a proposal rate; unsafe arrangements retain standard motion, and exposure depends on existing cover.

Source `262d33ba8e1cfa57c9799ef1c98bcebfd18a8d4d` on `codex/gameplay17-reactive-archery`. Compiled WebGL only. Gameplay12–16 sources and sites remain unchanged. Saves isolated with `HuntingRun.Gameplay17:/idbfs`, a separate key and filename. Experimental rewards/resume data do not modify stable saves.

Unity and Chrome desktop/mobile-viewport simulations passed. Human engagement, one-thumb feel, warning readability, physical Android/iPhone, Safari and sustained mobile performance remain untested. WebGL2/WebAssembly required; download, memory, storage and startup vary by device/browser. Both full simulated runs cleared 21 animals; this does not prove better gameplay. Controlled fixtures showed anticipation improves arrows per clear.

## Rollback

Unpublish only this repository's Pages to withdraw Gameplay17. After future updates, restore tag `gameplay17-reactive-archery` into a **new main commit** and push; do not force-push. Earlier sites remain independent: [Gameplay12](https://wasiqnkhurshid.github.io/HuntingRunGame-WebGL/), [Gameplay13](https://wasiqnkhurshid.github.io/HuntingRunGame-Gameplay13/), [Gameplay14](https://wasiqnkhurshid.github.io/HuntingRunGame-Gameplay14/), [Gameplay15](https://wasiqnkhurshid.github.io/HuntingRunGame-Gameplay15/), [Gameplay16](https://wasiqnkhurshid.github.io/HuntingRunGame-Gameplay16/).
