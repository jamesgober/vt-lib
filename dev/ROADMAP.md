# vt-lib - Roadmap

> Path from scaffold to a stable 1.0. Hard parts are front-loaded; each phase has hard exit criteria.
> Master plan: C:/Dev/libraries/Rust/lang-collection/_lexersketch/ROADMAP.md and NEW-LIBS.md
>
> **Anti-deferral rule:** no listed hard task moves to a later phase unless this file records the move and the reason.

## v0.1.0 - Scaffold (DONE)
Compiles, CI green, structure correct, no domain logic.
- [x] Manifest, README, CHANGELOG, REPS, dual license, CI, deny, clippy, rustfmt, DIRECTIVES, ROADMAP.

## v0.2.0 - Foundation
- [ ] Parser state machine, screen grid with attributes, cursor and modes, scrollback, damage tracking, key encoding; conformance cases as data.

## v0.5.0 - Implementation
- [ ] Reflow, selection, alternate screen, mouse reporting, OSC 8 links, bracketed paste.

## v0.9.0 - Hardening
- [ ] Fuzzing; performance on large outputs.

## v1.0.0 - Stable
- [ ] Frozen after Studio's terminal ships on it (D18).
