Act to Think - 601.697 Midterm Report
Author: Qining Shen
Report date: November 11, 2026

Build:
  latexmk -pdf main.tex

Template provenance:
The course syllabus links to the RSS Paper Format page:
  https://alliance-ai.cs.jhu.edu/teaching/HCR/
  https://roboticsconference.org/2019/12/04/paper-format/
The official LaTeX archive is:
  https://roboticsconference.org/docs/paper-template-latex.tar.gz

That archive itself uses documentclass[conference]{IEEEtran}, Times,
numeric natbib citations, and plainnat. The repository's IEEEtran.cls
matches the official archive byte for byte:
SHA-256 d63d4bf27f29603a733d06e27ba5fbb40488acf9d1d696354a88b886758f70a7
No custom page geometry, font-size reduction, or spacing override is used.

Report scope:
The report distinguishes the implemented reasoning scheduler, adapted
3D evaluation, and completed four-cup pilot from proposed joint learning
and the prepared cup-count scaling experiment.
The abstract task results report five training seeds. The 3D evaluation
reports both evaluated checkpoints and all seven policies.
The cup pilot uses exact reference computations and 12 real-LLM tasks;
it does not establish a learned observer or learned belief encoder.

Course connections:
Lecture 3: optimal control and dynamic programming.
Lectures 5-6: safety filtering; the budget mask is a conceptual analogy
for resource feasibility, not a physical-safety certificate.
Lecture 11: Hu et al. (2024) is an optional reading.
Lecture 14: planning with human internal states; latent human intent
is distinct from the agent's computational state.
Lecture 17: conformal prediction.
Lecture 19: KnowNo is an assigned discussion paper. Clarification is a
motivating extension; the current experiments implement inspection and
do not implement conformal calibration.

Only LaTeX sources and supporting files are maintained here.
