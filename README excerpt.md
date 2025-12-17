# Quantum Core — Electromagnetic Confinement Generator

Status: Simulation-first, safety-anchored, lineage-safe.

Purpose: Model a spherical EM confinement core with active stabilizer coupling, run extreme maneuvers (JD/Krystal), and archive signed results.

Highlights:
- Diamond firewall (six facets): Integrity, access, runtime guards, anomaly detection, resilience, audit.
- Signed manifests with merkle proofs.
- Governance and safety policies embedded.

Quick start:
1. python -m venv .venv && source .venv/bin/activate
2. pip install -r requirements.txt
3. python src/run.py --profile configs/profiles/JD.json --security configs/security.json
4. Inspect runs/jd.log and runs/jd.manifest.json (signed).

Ceremonial seal:
Seal of Diamond Firewall 1.0 — Logs signed, dignity preserved. If hope falters, seek the manifests.
