# Erwin Pawliczek

Chemical engineering student at the University of Houston. I build simulation engines
for process plants and chemical supply chains, and I work close to the metal when
the problem needs it — C, C++, numerical methods, and Linux.

## Highlights

- **Linux kernel (crypto/ecc.c).** Timing side-channel fix in ECDH public-key
  generation: randomize the initial Z in `ecc_make_pub_key()` so a
  non-constant-time modular inversion cannot leak the private key through its
  running time. Applied by maintainer Herbert Xu on 12 Nov 2026 —
  [`cd65eaf17841`](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=cd65eaf17841ac76f93a0c0806215cbd0e1cd980).
- **Ocypod** (private, all rights reserved). Stochastic agent-based simulation of
  the global ethylene → PE/MEG supply chain. 1st place, AITX × MLOps World /
  Antler hackathon.
- **[Stomato](https://github.com/ErwinPawliczek/Stomato).** Process simulation and
  engineering-design engine for natural gas processing: Peng–Robinson solve,
  equipment sizing, PFD, P&ID, and isometrics from one model.
- **[OilFlood](https://github.com/ErwinPawliczek/OilFlood)** — live at
  [oilflood.xyz](https://oilflood.xyz). 72-hour oil-spill trajectory forecaster;
  OpenDrift/OpenOil vs a custom Lagrangian particle model, ensembles, and live
  NOAA currents and winds.
- **[PetroGrid](https://github.com/ErwinPawliczek/UH-Hackathon-2026)** —
  [petrogrid.xyz](https://petrogrid.xyz). Live chemical-supply-chain simulation
  (C++ engine) that shows what fails next, when, and what it costs.

## Hackathon wins and other work

- **ChemBee** — 1st place, Cognee track; invited Cognee ambassador. Agentic plant analysis: an LLM writes Python against live/sim data
  and a DWSIM engine. Live demo (login): [chembee.xyz](https://chembee.xyz).
- **QuantHouse** — Houston housing "price receipt" models (GWR / LightGBM,
  spatial block CV). Team repo:
  [salehk1/uh-ai-hackathon](https://github.com/salehk1/uh-ai-hackathon), live at
  [quanthouse.casa](https://quanthouse.casa).

## Skills

Python (NumPy, PyTorch), C, C++, Linux, numerical methods, process and
supply-chain simulation.

[LinkedIn](https://www.linkedin.com/in/erwin-pawliczek) · [X](https://x.com/erwinpawliczek)

<p align="center"><img src="koi/koi.gif" width="160" alt="Koi" /></p>
