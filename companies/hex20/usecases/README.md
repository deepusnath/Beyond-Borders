# HEX20 — Draft Problem Statements

*Status: AI-drafted proposals pending anchor validation. Do not build against these until Space Evolve's lead confirms scope; bring them to a Space Evolve session instead.*

## PS-01: Open ground-station telemetry dashboard

Build an open-source dashboard that visualizes CubeSat telemetry (from public amateur-band downlinks, e.g. SatNOGS network data) with decoding, health monitoring, and pass prediction. Skills: SDR basics, data pipelines, web viz. Why it matters: every small-sat team needs this; an open Kerala-built version becomes shared infrastructure and a hiring signal.

## PS-02: VLEO mission simulator for MAGNETO-class missions

An orbital-mechanics simulation (Python, open libraries like poliastro-class tooling) modeling very-low-Earth-orbit drag, decay, and coverage for a 12U CubeSat, with a notebook explaining tradeoffs. Skills: orbital mechanics, scientific Python. Why: VLEO is a live frontier and the math is learnable at student level.

## PS-03: Edge-AI payload prototype on ground hardware

Prototype an onboard-inference payload pipeline on a Raspberry Pi/Jetson-class board: take raw Earth-observation imagery, run detection/compression at the edge, output insight-sized downlink packets. Skills: embedded ML, the exact intersection of Kerala's edge-silicon story (Netrasemi) and spacetech. Why: downlink is the industry bottleneck; insight-not-pixels is the direction HEX20's segment is moving.
