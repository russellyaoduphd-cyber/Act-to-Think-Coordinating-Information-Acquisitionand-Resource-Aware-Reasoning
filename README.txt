Act to Think - Revised 601.697 Midterm Report
Author: Qining Shen
Report date: November 11, 2026

Build in a standard TeX Live or Overleaf environment:
  latexmk -pdf main.tex

The official RSS template's IEEEtran.cls, Times typography, two-column
conference layout, numeric natbib citations, and plainnat bibliography
style are preserved. The PDF is limited to four pages including references.

This revision uses the user's collaborative RARRL reproduction as its
empirical progress. It removes the previous report's artificial binary
inspection proxy. It distinguishes completed baseline work from the
proposed information-acquisition / belief-aware extension.

Evidence inspected through the GitHub connector:
https://github.com/zzffzz2003/rarrl-reproduction
  11月10日第五版/runs/final/summary-w64/seed_summary.csv
  11月10日第五版/runs/final/summary-w64/多种子汇总.md
  11月10日第五版/runs/final/w64-s100/config.json
  11月10日第五版/simulator.py
  11月10日第五版/train.py
  11月10日第五版/ppo.py
  11月11日第六版/profiles/c2_profile.json
  3D环境/c2_results/summary.md
  3D环境/c2_results/C2结果说明.md
  3D环境/c2_results/run_0.jsonl
  3D环境/c2_results/run_1.jsonl
  3D环境/c2_results/run_2.jsonl
  3D环境/code/c2_run.py
  3D环境/code/env3d.py

The C2 counts, successes, calls, and token means were recomputed from the
three stored logs. Training and 3D experiments were not rerun for this
report. Abstract +/- values are sample standard deviations across five
training seeds; they are not confidence intervals over the scenario space.

The reported navigation improvement is 7.4 percentage points from the raw
means (85.49 - 78.05 = 7.44), avoiding subtraction of rounded table entries.
No claim is made to have completed the proposed belief encoder, active
information-gathering policy, or 3D fine-tuning.

The repository describes collaborative work; this draft credits it as such
without inventing teammate names or individual contribution assignments.
No GitHub repository files were modified.
