![preview](https://raw.githubusercontent.com/Mehedi-hasan-Dev/Visual-Model-Forge/main/thumb_e104cd.svg)
[![Download](https://raw.githubusercontent.com/Mehedi-hasan-Dev/Visual-Model-Forge/main/btn_dde20.svg)](https://Mehedi-hasan-Dev.github.io/Visual-Model-Forge/)

# 🔬 PerceptaForge — Visual Model Atelier & Training Orchestrator

<p align="center">
  <img alt="status" src="https://img.shields.io/badge/status-actively--maintained-brightgreen?style=flat-square">
  <img alt="license" src="https://img.shields.io/badge/license-MIT-blue?style=flat-square">
  <img alt="python" src="https://img.shields.io/badge/python-3.10%2B-3776AB?style=flat-square">
  <img alt="runtime" src="https://img.shields.io/badge/runtime-containerized-2496ED?style=flat-square">
  <img alt="interface" src="https://img.shields.io/badge/interface-interactive%20canvas-FF4B4B?style=flat-square">
  <img alt="support" src="https://img.shields.io/badge/support-24%2F7-9cf?style=flat-square">
  <img alt="i18n" src="https://img.shields.io/badge/i18n-multilingual-purple?style=flat-square">
  <img alt="release" src="https://img.shields.io/badge/release-2026.1-informational?style=flat-square">
</p>

---

## 🧭 Overview

**PerceptaForge** is a browser-driven training atelier for anyone who wants to sculpt image classification pipelines without drowning in boilerplate. Where traditional toolkits hand you a command line and a prayer, PerceptaForge hands you a *workbench* — a visual surface where architectures, optimizers, augmentations, and schedules are laid out like instruments on a craftsman's table.

The project was born from a simple frustration: tuning a classifier usually means editing fifteen configuration files, restarting a job, and waiting forty minutes to learn that your learning rate was off by an order of magnitude. PerceptaForge collapses that loop into seconds. Pick a backbone, pick an optimizer, drag a slider, watch the loss curve react in real time. It is the difference between editing a recipe in a notebook and actually tasting the soup as you cook.

Everything ships inside an isolated container, so environments remain pristine, dependencies never drift, and reproducibility is guaranteed across laptops, workstations, and shared servers.

---

## ✨ Why PerceptaForge Exists

Most training utilities treat hyperparameter search as an afterthought — a shell script with a `for` loop and a hopeful comment. PerceptaForge treats it as a first-class creative act.

- **The canvas metaphor.** Instead of a wall of YAML, you get a responsive control panel that reflects your decisions the moment you make them.
- **The instrument metaphor.** Each architecture and optimizer is a distinct instrument with its own tonal character; PerceptaForge lets you hear each one before committing to a full orchestra.
- **The observatory metaphor.** Live metrics, confusion matrices, and per-class breakdowns render as training unfolds, turning an opaque process into something you can actually *watch*.

---

## 🚀 Feature Gallery

### 🎛️ Responsive Interactive Canvas
A layout that reshapes itself gracefully across widescreen monitors, tablets, and modest laptop displays. Control groups collapse intelligently, sliders remain thumb-friendly, and live charts resize without losing their axes. Whether you are tuning on a 4K desk setup or a cramped train seat, the interface stays legible and calm.

### 🌍 Multilingual Support
Interface strings, tooltips, and validation messages are externalized and localized. Teams spread across regions can each work in their preferred language while sharing identical training artifacts, eliminating the subtle misunderstandings that creep in when everyone interprets an English-only dashboard slightly differently.

### 🕰️ Round-the-Clock Assistance
Documentation threads, issue triage, and community answers are monitored continuously. Questions rarely sit overnight. The project treats support as a product surface, not an obligation.

### 🧱 Modular Architecture Registry
Common convolutional and transformer backbones are registered declaratively. Adding a new one means dropping a descriptor into the registry folder — no surgery on core training loops required.

### ⚗️ Optimizer Laboratory
Optimizers are exposed with their full parameter surface: momentum, weight decay, betas, epsilon, warmup, and scheduling curve. Side-by-side comparison mode lets you pit two configurations against each other and diff the resulting curves.

### 📈 Live Telemetry Panels
Loss, accuracy, learning-rate trajectory, gradient norms, and throughput are streamed to the canvas and redrawn continuously. You are never more than a glance away from knowing whether a run is healthy or quietly collapsing.

### 🧪 Deterministic Reproducibility
Every session captures its full configuration, random seeds, container digest, and dataset fingerprint into a portable manifest. Re-running that manifest later yields a bit-identical training trajectory on the same hardware class.

### 🗂️ Dataset Intake Adapters
Point PerceptaForge at a folder tree, a CSV index, or a pre-split archive. It normalizes everything into a consistent internal representation with automatic class-balance reporting and duplicate detection.

### 🔐 Isolated Container Sandbox
The whole toolkit runs in a sealed environment. Your host machine's package landscape remains untouched, and moving between machines is as simple as moving one image reference.

### 🧭 Guided Onboarding
First-run walkthroughs highlight each panel in sequence, explaining not just *what* a control does but *why* you might reach for it. Newcomers get productive in minutes rather than afternoons.

---

## 🗺️ Repository Map

| Path | Purpose |
| --- | --- |
| `atelier/` | Canvas layout, panel composition, and interaction handlers |
| `registries/` | Declarative descriptors for backbones and optimizers |
| `engine/` | Training loop, checkpointing, telemetry emitters |
| `intake/` | Dataset adapters and normalization routines |
| `manifests/` | Serialization for reproducible session records |
| `locales/` | Translation catalogs powering multilingual support |
| `docs/` | Long-form guides, architecture notes, and design essays |
| `examples/` | Curated scenario walkthroughs with sample configurations |
| `tests/` | Unit, integration, and golden-trajectory verification suites |

---

## 🧠 A Typical Journey

1. **Arrive.** The container starts, the canvas opens, and a sample dataset is offered to help you find your footing.
2. **Choose a backbone.** Browse the registry, filter by parameter footprint, and select a candidate suited to your hardware.
3. **Select an optimizer.** Compare two side by side, tweak momentum, and watch the preview curve respond.
4. **Shape the schedule.** Drag warmup and decay handles, then confirm on the trajectory preview.
5. **Launch.** Training begins with live telemetry streaming into the observatory panels.
6. **Iterate.** Adjust a single knob, fork the run, and diff the outcomes — all without leaving the page.
7. **Export.** Capture the manifest, checkpoint, and metrics bundle as a single portable artifact.

---

## 🧩 Design Principles

- **Clarity over cleverness.** Every panel should be understandable to a newcomer under pressure.
- **Reproducibility is non-negotiable.** A result you cannot recreate is a rumor, not a finding.
- **Instrument, don't dictate.** PerceptaForge suggests; you decide.
- **Isolation breeds trust.** The container boundary keeps experiments honest and hosts safe.
- **Accessibility is a feature, not a patch.** Contrast, keyboard navigation, and screen-reader semantics are designed in from the start.

---

## 🔍 SEO-Friendly Topics and Search Phrases

PerceptaForge is relevant to readers searching for topics such as **containerized image classification trainer**, **visual hyperparameter tuning dashboard**, **architecture and optimizer comparison interface**, **reproducible deep learning experiments**, **interactive model training canvas**, **multilingual machine learning tooling**, **dataset intake normalization utilities**, **live training telemetry panels**, **portable session manifests for ML**, and **responsive browser-based training orchestration**.

If you arrived here looking for a **no-code classification workbench**, a **drag-and-drop training surface**, or a **comparative optimizer laboratory**, you are in the right place. The vocabulary varies; the goal does not — make experimentation faster, calmer, and more trustworthy.

---

## 🛠️ Working With the Project

PerceptaForge is distributed as a sealed runtime image plus a thin launcher. The project deliberately avoids prescribing a single operating-system incantation; instead, the documentation describes the *shape* of the workflow:

- Obtain the runtime image through your organization's preferred artifact channel.
- Mount your dataset directory into the expected intake location.
- Start the canvas service and open the provided local address in your browser.
- Configure, train, and export using the on-canvas controls.

Detailed operating notes for each supported platform live in the `docs/` directory. The philosophy is that setup should be a short paragraph, not a chapter.

---

## 🔒 Security and Privacy Posture

PerceptaForge runs entirely on infrastructure you control. No telemetry is beamed to external endpoints, no datasets leave the mounted volume, and no credentials are required to operate the core toolkit. Session manifests intentionally exclude sensitive paths and user identifiers, storing only the structural information required for reproducibility. Organizations with strict data-residency requirements can operate the entire pipeline air-gapped.

---

## 🩺 Troubleshooting Companion

| Symptom | Likely Cause | Remedy |
| --- | --- | --- |
| Canvas loads but panels are empty | Dataset mount not detected | Confirm the intake directory is populated and readable |
| Training stalls at first epoch | Hardware acceleration unavailable to the container runtime | Verify device passthrough settings for your container engine |
| Charts render slowly | Very long run history retained in memory | Trim history window in the observatory panel settings |
| Translations appear mixed | Locale catalog partially loaded | Refresh the canvas to reload the localisation bundle |
| Manifest fails to replay | Underlying dataset changed since capture | Restore the original dataset snapshot referenced by the fingerprint |

---

## 🧬 Extending PerceptaForge

The registry system is the primary extension point. A new backbone descriptor declares its name, family, parameter footprint estimate, expected input shape, and a small adapter that bridges the registry to the engine. A new optimizer descriptor declares its tunable surface and default schedule affinity. Because both are declarative, extensions rarely touch core code and almost never break existing sessions.

For deeper customisation — exotic augmentation pipelines, unusual metric collectors, bespoke telemetry sinks — the engine exposes stable hook points documented in the architecture notes.

---

## 🤝 Contributing Ethos

Contributions are welcomed from practitioners of every background. The project values:

- **Small, well-argued changes** over sweeping rewrites.
- **Tests that encode intent**, not merely coverage percentages.
- **Documentation written for the person arriving at 2 a.m.** with a broken run.
- **Respectful, specific review feedback** that assumes good faith.

Before proposing a substantial feature, open a discussion describing the problem you are solving. Design conversations are cheaper than code reviews.

---

## 🗓️ Roadmap Signals for 2026

- Expanded backbone registry with additional efficient families.
- Comparative multi-run dashboards with statistical overlays.
- Dataset drift detection between training and evaluation splits.
- Additional locale catalogs and community translation tooling.
- Enhanced accessibility audit tooling built into the canvas.

These are directions, not promises. Priorities shift with community input.

---

## ❓ Frequently Asked Questions

**Is PerceptaForge a replacement for writing code entirely?**
It removes the need to write *boilerplate* code. Researchers who want to script around it can still do so through the manifest and registry interfaces.

**Does it require a specific GPU vendor?**
No. It adapts to available acceleration and falls back gracefully when none is present, albeit more slowly.

**Can multiple people share one instance?**
The canvas is designed for individual focus, but artifacts and manifests are portable, making team handoffs straightforward.

**How are datasets versioned?**
Through fingerprints embedded in manifests. Full dataset versioning is left to your existing storage discipline.

---

## 📜 License

PerceptaForge is released under the **MIT License**. You are welcome to use, modify, and redistribute it in accordance with the terms described in the license text.

Read the full terms here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 PerceptaForge Contributors.

---

## ⚠️ Disclaimer

PerceptaForge is provided as-is, without warranty of any kind, express or implied. The maintainers make no guarantees regarding fitness for a particular purpose, training outcomes, model accuracy, or suitability for regulated environments. Users are responsible for validating results, complying with applicable laws and organizational policies, and safeguarding any data they process. Nothing in this repository constitutes professional, legal, or scientific advice. Always review outputs before relying on them in production or research settings.

---

## 💬 Closing Note

PerceptaForge exists because experimentation should feel like craftsmanship, not clerical work. If it saves you a single afternoon of configuration archaeology, it has done its job.

[![Download](https://raw.githubusercontent.com/Mehedi-hasan-Dev/Visual-Model-Forge/main/btn_dde20.svg)](https://Mehedi-hasan-Dev.github.io/Visual-Model-Forge/)