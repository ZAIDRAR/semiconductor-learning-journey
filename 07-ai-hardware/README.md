# 07 — AI Hardware

**Status:** Study plan.

## Concepts
- Multiply-accumulate units and fixed-point arithmetic
- Dataflow, throughput and latency
- Systolic arrays and memory bandwidth
- Energy efficiency and numerical precision
- Verification of hardware against a software reference

## First experiment
Design a signed or unsigned MAC module in Verilog with a clearly specified width and overflow policy. Test it against Python-generated reference results.

## Follow-up
Extend to a small 2×2 processing-element array only after verifying the basic MAC.

## Artifact evidence — 18 November 2026

The existing signed MAC now has Python-reference RTL verification and generic synthesis evidence; the 2×2 array remains planned. See the [Operation X audit](../docs/operation-x-review-2026-11-18.md). This does not automatically complete the learner competence goals above.
