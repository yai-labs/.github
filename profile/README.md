<p align="center">
  <img
    src="assets/yai-banner-ultra-tight1.png"
    alt="YAI Labs"
    width="58%"
  />
</p>

<p align="center">
  <strong>YAI Ain't Intelligence.</strong>
</p>

<p align="center">
  Infrastructure for controlled machine consequence.
</p>

---

YAI Labs builds system infrastructure for AI software that must operate under explicit control.

The core assumption is that model output is not the end of the system. In real software, output can enter tools, data, workflows, memory, policy, interfaces, and decisions. Once that happens, the main problem is no longer only generation quality, but execution boundary, evidence, recovery, and accountability.

YAI exists for that boundary.

## Scope

YAI is not a model provider, an inference engine, a chatbot framework, or a generic agent framework.

Inference engines, local model servers, remote APIs, tools, and specialized runtimes remain separate systems. YAI treats them as providers or subjects inside controlled operational contexts.

The central abstraction is the case.

A case is an isolated execution context where machine output, human input, tools, memory, policy, records, receipts, and projections can interact without losing control of what happened.

## Technical direction

YAI is built around a small set of runtime concerns:

- case isolation;
- subject and provider boundaries;
- controlled execution;
- durable records;
- receipts for meaningful actions;
- projections from internal state to external surfaces;
- runtime memory that can explain what happened;
- policy inside the execution boundary;
- recovery and inspection after execution.

The goal is not to make AI appear autonomous.

The goal is to make AI behavior bounded, inspectable, replayable where possible, and accountable when it touches real systems.

## Repository policy

YAI Labs repositories may have different levels of maturity, visibility, and license posture.

Some repositories are public for technical evaluation before they are ready for general use, broad contribution, or commercial integration. Public source does not automatically mean open source.

Each repository defines its own:

- status;
- license;
- contribution policy;
- supported commands;
- test surface;
- production readiness;
- third-party notices.

Do not assume a repository is open source, production-ready, or commercially usable unless its own README and license say so.

## Current work

The current work is focused on the core runtime and its supporting surfaces:

- local execution boundaries;
- case/control runtime;
- records and receipts;
- projection surfaces;
- hot state and durable storage;
- provider boundaries;
- command-line validation;
- reproducible test cases;
- documentation suitable for technical review.

The public-facing documentation is being prepared to make each repository easier to inspect, build, test, and evaluate.

## Projects

YAI Labs work is organized around several layers:

- core runtime and execution substrate;
- interface and protocol surfaces;
- developer-facing command tools;
- desktop/client surfaces;
- documentation, tests, and validation material.

Repository-specific READMEs are the source of truth for what currently exists.

## Status

YAI is under active early development.

The architecture is still being stabilized, and some public repositories may expose transitional code, incomplete command surfaces, or internal documentation while they are being cleaned up.

The intended direction is a technical repository surface where a reader can quickly understand:

- what the project is;
- what it is not;
- how to build it;
- how to run the first checks;
- what can be tested today;
- which parts are experimental;
- what license and contribution rules apply.
