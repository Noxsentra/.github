# Noxsentra Research and Evidence Standards

## Purpose

This document sets expectations for future published research and defensive intelligence. These are methodological standards, not a claim that a staffed analysis program or production threat platform is currently operating.

## Evidence record

A research record should identify the question, scope of authorization, original sources, collection dates, relevant software versions, methodology, results, confidence, known limitations, and correction history. Protect secrets, private data, and embargoed findings.

## Source hierarchy

Prefer original vendor advisories, upstream commits, reproducible test evidence, official vulnerability records, and published standards. Secondary reporting can provide context but should not silently replace primary evidence. Treat unauthenticated social posts, speculative assertions, and AI-generated summaries as leads rather than verified facts.

## Claim taxonomy

| Label | Interpretation |
| :-- | :-- |
| Reported | Attributable statement from an external source; not independently verified |
| Hypothesis | A proposed mechanism or explanation awaiting examination |
| Reproduced | Repeatable observation within explicitly authorized conditions |
| Corroborated | Multiple suitable sources or tests support the claim |
| Disputed | Credible contradictory evidence exists |
| Superseded | More recent analysis changes the prior assessment |

Severity, exploitability, exposure, and observed exploitation are separate attributes and must not be conflated. Do not present a model output, scanner signal, or CVE record as proof of active exploitation.

## Reproducibility

Where safe and permitted, specify platform, versions, configuration, inputs, test cases, expected versus observed behavior, and the boundary of generalization. Avoid publishing working exploit details if doing so would unduly endanger users before remediation.

## Publication and corrections

Use informative titles, dated updates, citations, methodological limitations, and actionable defensive guidance. If a substantive error is found, visibly correct it rather than silently rewriting conclusions. Coordinate sensitive technical publications with affected maintainers.

## AI-assisted analysis

AI systems may support summarization, clustering, code review, or hypothesis generation. Human reviewers must check citations, version assumptions, evidence, and causal claims before treating model-assisted output as established research. Protect private evidence from inappropriate model or tool exposure.
