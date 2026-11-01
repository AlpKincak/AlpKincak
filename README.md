<p align="center">
  <img src="assets/frames/00-hero.webp" width="100%" alt="Alp Murat Kıncak. Software, AI infrastructure, and experimental physics.">
</p>

<p align="center">
  Founder of <b>Aftember</b> · Creator of <b>Continuum</b> · Undergraduate researcher, <b>Katz Lab</b><br>
  Physics, Computer Science &amp; Mathematics at Cornell University
</p>

<br>

<a href="https://github.com/AlpKincak/aftember-showcase"><img src="assets/frames/01-aftember.webp" width="100%" alt="Aftember. Design renders of three app screens: a map of nearby Moments, a Moment opened full screen, and the Moments timeline."></a>

**Aftember** · Founder & lead engineer<br>
A private social camera built around real-world Moments: Expo client, FastAPI, PostgreSQL, private media storage, and a durable state machine behind collaborative Rewinds.<br>
<sub>Screens are design renders, not device captures.</sub>

[Product & engineering showcase →](https://github.com/AlpKincak/aftember-showcase)

<br>

<a href="https://github.com/AlpKincak/jarvis-showcase"><img src="assets/frames/02-continuum.svg" width="100%" alt="Continuum, durable task execution. A control plane that owns state in PostgreSQL sits above replaceable workers. One task's timeline: claim, checkpoint, a second attempt whose worker crashes, lease expiry, resume from the last checkpoint on another worker, wait, resolve, and a persisted result."></a>

**Continuum** · Creator · formerly Jarvis<br>
A persistent, model-independent control plane for personal AI. It owns memory, tasks and their append-only history; models and agent workers are replaceable and never own that state. Above is one subsystem, durable task execution: work runs in leased segments that end in committed checkpoints, so after a worker dies the next attempt resumes from the last checkpoint and only the unfinished segment is redone.

[Technical showcase →](https://github.com/AlpKincak/jarvis-showcase)

<br>

<a href="https://github.com/AlpKincak/forex-trader-showcase"><img src="assets/frames/03-trading.svg" width="100%" alt="Algorithmic trading. EUR/USD price history zoomed from daily candles (context) to 4-hour (structure) to 15-minute (confirmation)."></a>

**Algorithmic trading** · Time-series research<br>
A deterministic multi-timeframe FX research system covering market structure, points of interest, liquidity and lower-timeframe confirmation. The same pipeline runs in live observation and in replay, with checks for look-ahead errors. Research only; it never places orders.

[Technical showcase →](https://github.com/AlpKincak/forex-trader-showcase)

<br>

<a href="https://github.com/AlpKincak/trading_journal"><img src="assets/frames/04-journal.webp" width="100%" alt="Trading Journal. The app's data-quality and reconciliation screen, running on its bundled sample data."></a>

**Trading Journal** · Open source<br>
An open-source, local-first trade journal: CSV import and read-only TradeLocker sync into SQLite, data-quality checks, risk analytics and a Streamlit dashboard. Analysis only, with no order placement.<br>
<sub>Screenshot of the real app on its bundled sample data.</sub>

[Source code →](https://github.com/AlpKincak/trading_journal)

<br>

<img src="assets/frames/05-katz-lab.svg" width="100%" alt="Katz Lab, functional diagram rather than the physical layout. A 795 nm laser's higher-power optical-pumping beam and a lower-power two-channel X/Y spin-control path pass through beam preparation to the atomic spins. Long-term research objective: high-precision quantum magnetometry.">

**Katz Lab** · Undergraduate researcher, Prof. Or Katz's Quantum Optics Lab, Cornell<br>
I build and optimize the 795 nm optical-pumping system for an atomic spin-control platform: beam-path design, alignment, collimation and mode matching, polarization control with AOMs and PBS optics, fiber coupling, tapered-amplifier diagnostics and stabilization, and a lower-power two-channel (X/Y) spin-control path. The platform's long-term goal is high-precision quantum magnetometry.<br>
<sub>Functional diagram, not the optical layout.</sub>

<br>

<p align="center">
  <a href="https://www.linkedin.com/in/alp-murat-k%C4%B1ncak-a97052304/">LinkedIn</a> · <a href="https://github.com/AlpKincak?tab=repositories">All repositories</a><br>
  <sub>Production code for Aftember, Continuum and the FX research system is private; the showcases document their architecture. trading_journal is fully public.</sub>
</p>
