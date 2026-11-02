# Graph, Quantum and DimeNet Models for HOMO–LUMO Gaps

**Directed study with Dr. Don Roosan, December 2025.**

The research investigated HOMO–LUMO molecular-gap prediction using the QM9 dataset. A classical graph neural network was trained for 20 epochs and reached **training MSE 0.3012** and **validation MSE 0.2981** on a normalized target. A hybrid quantum-classical tutorial reached **training MSE 0.2924** after 10 epochs. DimeNet was researched for geometry-aware directional message passing; implementation and debugging were unfinished at the conclusion of the study.

**Interpretation note:** The two final MSE values represent different partitions (classical validation versus hybrid training). They do not alone establish that the hybrid approach generalized better.
