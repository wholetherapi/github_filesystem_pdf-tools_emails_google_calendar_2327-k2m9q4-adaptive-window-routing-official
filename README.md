# Adaptive Window Routing — official implementation

Official implementation of the paper
**Adaptive Window Routing for Efficient Transformers** (NeurIPS 2025).
The paper is a follow-up to the technical report
**Elastic Window Routing for Long-Context Sequence Modeling** (`NRL-TR-2026-0117`)
and cites it as prior work.

AWR learns per-head window sizes at inference time. It builds on the same broad
idea of windowed routing but is a different method with a different paper.

This repository does not implement Elastic Window Routing and contains no
implementation of `NRL-TR-2026-0117`; it implements Adaptive Window Routing only.
