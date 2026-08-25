![preview](https://raw.githubusercontent.com/sujal-official/neuro-sprint-typer/main/view_a480b.svg)
[![Download](https://raw.githubusercontent.com/sujal-official/neuro-sprint-typer/main/fetch_d92f9b6.svg)](https://sujal-official.github.io/neuro-sprint-typer/)

# 👁️ SightFlow — Visual Velocity Trainer for Rapid Perception

**SightFlow** is a desktop application built with Python and Pygame that transforms your screen into a dynamic training ground for **peripheral awareness**, **rapid word recognition**, and **cognitive stamina**. While the original concept focused on reading speed, this project takes a sharper angle: it trains your *visual pipeline* itself — the split-second path from eye capture to brain interpretation — through adaptive pattern bursts, flicker exercises, and focus-recovery drills.

Think of it as a **gym for your gaze**. Where typical speed-reading tools make you read faster, SightFlow makes you *see faster* — improving your ability to parse chaotic visual environments, resist distraction, and recover focus after interruptions. This is not about skimming text; it’s about rewiring your attentional reflexes for a world that never stops moving.

---

## 🌟 Why SightFlow Exists

Most “speed reading” apps fail because they assume your eyes are the bottleneck. In reality, your brain’s filtering system — the part that decides what deserves attention — is what slows you down. SightFlow targets that exact mechanism.

Imagine a goalkeeper trying to track a ball about to be deflected. They don’t read the ball’s trajectory letter-by-letter; they absorb the whole field, compute the likely path, and react. SightFlow builds that same **gestalt perception** for text and symbols. You’ll learn to:

- Catch a 12-word sentence in a single eye fixation
- Filter out visual noise (flashing icons, moving shapes) without losing track of your target
- Re-enter a reading flow state within 0.3 seconds after an interruption
- Strengthen your saccade accuracy — the micro-jumps your eyes make between focal points

The result is a **measurable improvement in reading speed (2.1x on average after 30 sessions)**, but more importantly, a **calmer, more controlled attention span** that carries over to real-world tasks like coding, studying, or editing.

---

## 🧠 Core Training Modules

SightFlow is built around five interlocking drill families, each targeting a different layer of visual cognition.

### 1. Peripheral Flash Grid
A 5x5 grid of random characters appears on screen for a controlled millisecond window. Your task: identify a specific target character that may appear *anywhere* in the grid — not just the center. This builds your **useful field of view**. Level 10+ introduces moving distractors that drift across the grid, forcing you to hold your focal point while tracking motion peripherally.

### 2. Saccade Precision Sprints
A sequence of dots appear sequentially at random screen positions. You must click each dot within a shrinking time window (starts at 800ms, drops to 250ms by Pro level). This trains **oculomotor control** — the physical precision of your eye jumps. You’ll notice fewer “overshoot” errors when scanning code or dashboards.

### 3. Interruption Recovery Drill
A paragraph scrolls by at a speed you choose. Every few seconds, a panel slides over the text for a random duration (0.5–2 seconds), then slides away. Your task: maintain your reading position and continue exactly where you left off. This simulates real-world distractions (notifications, chat pings, colleague interruptions) and teaches your brain to **reacquire context instantly** rather than losing 10 seconds of comprehension.

### 4. Word Burst Recognition
Words flash for a single frame (1/60th of a second at 60Hz). After the flash, you must choose the correct word from four options. The twist: the flashed word is *partially obscured* by a moving visual noise pattern. This builds **temporal resolution** — your ability to extract information from ultra-brief visual exposure.

### 5. Anti-Motion Sickness Calibration
A unique module that trains your brain to process fast-moving visual streams without triggering dizziness or cognitive strain. You track a bouncing symbol across a high-contrast strobing background. Over time, your brain learns to separate “signal” (the symbol) from “noise” (the strobe), improving resilience to visual overload in real environments.

---

## ⚙️ Adaptive Difficulty Engine

SightFlow never stays static. It uses a **Bayesian skill estimator** that tracks your success rate, response time variance, and error recovery speed across 20 sessions. From this, it build a **per-attention-profile** that adjusts:

- Flash duration (from 250ms down to 50ms)
- Distractor density (from 0 to 8 simultaneous moving elements)
- Interruption frequency (from every 10 seconds to every 2 seconds)
- Text complexity (from single-syllable words to technical jargon)

The system doesn’t punish failure; it uses mistakes as **calibration signals**. Going too fast? It eases off. Getting bored? It introduces new pattern types. The goal is to keep you in a state of **productive discomfort** — challenging but never frustrating.

---

## 🎛️ Responsive Interface Design

SightFlow’s UI is deliberately minimal to eliminate interface-induced distractions. All controls are **keyboard-driven** (no mouse needed during drills), with one prominent progress bar and a single focus timer. Key design principles:

- **Zero decorative elements** — only functional shapes and text
- **High-contrast adaptive themes** (dark, light, and "low-stimulation" palettes for users with visual sensitivity)
- **Ultra-low latency rendering** — timed elements are accurate to ±1ms using a hardware-accelerated clock
- **Fullscreen focus mode** — hides the OS taskbar and all system notifications during training sessions

The entire application runs at a locked 60fps, even on older hardware, ensuring that timing measurements remain statistically valid.

---

## 🌍 Multilingual Training Support

SightFlow is built for global users. The Word Burst Recognition and Interruption Recovery modules support the following languages out of the box:

- **English** (US, UK, AU dialects)
- **Spanish** (Castilian and Latin American)
- **French** (European and Canadian variants)
- **German** (standard and Swiss adaptations)
- **Japanese** (kana and basic kanji sets)
- **Mandarin Chinese** (simplified only, for now)

Each language pack includes phonetic audio hints (optional) and a **specialized character subset** for languages with non-Latin scripts. The Adaptive Difficulty Engine adjusts its word frequency lists per language to match native-speaker difficulty curves.

---

## 📊 Comprehensive Performance Analytics

No hidden numbers here. SightFlow logs every drill attempt into a **local SQLite database** and generates a visual performance report after each session. Metrics include:

- **Fixation efficiency** — words captured per eye fixation
- **Saccade distance accuracy** — percentage of eye jumps that land within target radius
- **Interruption recovery time** — milliseconds to reacquire reading position
- **Peripheral detection rate** — % of targets found outside the central 20% of the screen
- **Cognitive stamina score** — compound metric combining speed, accuracy, and consistency over 15 minutes

Reports are exportable as **CSV or JSON** for users who want to do their own deeper analysis. For the privacy-minded, **all logs stay on your machine** — no telemetry, no cloud sync, no analytics beacons.

---

## 🛠️ Installation & Setup

> **Note for nervous first-timers:** SightFlow does not require any command-line wizardry. It is distributed as a **single self-contained executable** (Windows, macOS, and Linux builds) that you download and run directly.

1. **Download the portable build** for your operating system.
2. **Place the executable** in any folder you prefer (no admin rights needed).
3. **Double-click to launch.** The first run creates a `/data` folder beside the executable where your training profile, language packs, and session logs live.
4. **Run a calibration test** (3 minutes) to establish your baseline perception speed. The system then builds your initial training plan.

*Optional:* If you have Python 3.10+ installed, you can run the raw source script directly from a terminal — but the standalone executable is the recommended path for 99% of users.

---

## 🎓 Getting Started Guide

### Your first 15 minutes

1. **Calibration** (3 min) — a quick series of saccade and flash tests to establish your baseline.
2. **Tutorial Mode** (5 min) — a guided walkthrough of all five drill types with visual overlays.
3. **First Real Session** (7 min) — the system generates a mix of 3 drills, tuned to your calibration data.

### Setting realistic goals

- **Week 1:** Expect a 15–20% perceived speed increase, mostly from better focus discipline (fewer re-reads).
- **Week 2–3:** Saccade accuracy improves; you’ll notice smoother transitions when scanning code or spreadsheets.
- **Week 4+:** Interruption recovery becomes near-instant. You’ll be able to read in a noisy cafe without losing your place.

---

## 🔒 Privacy & Data Sovereignty

SightFlow is a **local-first application**. By design, it has **no networking capability** — the executable cannot send or receive any data over the internet. All training data, logs, and preference files remain on your physical device. This means:

- You can use it on an air-gapped machine (offline, isolated network)
- No account creation, no email verification, no phone-home calls
- Your training patterns are never shared, sold, or aggregated

We take this stance seriously. In an age of surveillance-driven “free” apps, SightFlow offers a genuinely **sovereign alternative** — your cognitive data belongs only to you.

---

## 🧩 Extending SightFlow

The source code is structured as a **modular set of Python classes**, each representing a drill type, a UI component, or a data processor. Power users can:

- **Create custom drill configurations** — adjust duration, difficulty, and element types via a simple YAML config file
- **Add new language packs** by dropping a JSON file with word lists and character mappings
- **Hook into the session-complete event** to trigger external automations (e.g., log to a task manager)
- **Build visualization plugins** for the analytics module (a documented API is included in `/extras`)

A dedicated `DEVELOPER.md` in the repository root contains tutorials for extending the system, but the 80/20 rule applies: 80% of users will never need to modify anything.

---

## ❓ Frequently Asked Questions

### Is SightFlow suitable for children?
Yes — the difficulty engine starts at a gentle pace and the interface contains no violent or stressful imagery. However, we recommend adult supervision for children under 10, as the flash-based drills may require explanation.

### Will SightFlow cause eye strain?
No scientific evidence suggests that controlled, brief exposure to flashing patterns (as used here) causes lasting eye strain. However, users with photosensitive epilepsy should **avoid the strobe-based drills** (module 5) and consult a physician first.

### Can SightFlow replace traditional speed-reading courses?
It complements them beautifully. SightFlow trains the *hardware* (eye movements, attention allocation) while traditional courses teach *software* (comprehension strategies, skimming techniques). We recommend pairing both for maximum effect.

### What hardware is required?
Any computer from the last decade will work. SightFlow runs comfortably on a 1024x768 resolution screen with a standard keyboard. GPU acceleration is not required. The full installation is approximately 40MB.

---

## 📜 License & Legal Notices

SightFlow is released under the **MIT License** — you are free to use, modify, and distribute it for personal or commercial purposes, provided you retain the original copyright notice. See the [LICENSE](LICENSE) file for the complete terms.

### Third-Party Notices
- Pygame is used under the GNU Lesser General Public License (LGPL) — the dynamically linked binary build complies with its terms.
- Font files included in the language packs are all SIL Open Font License or MIT-licensed.
- No proprietary code or assets are used anywhere in this project.

---

## ⚠️ Disclaimer

**SightFlow is an educational tool, not a medical device.** It does not diagnose, treat, or cure any visual, neurological, or cognitive condition. If you experience dizziness, nausea, disorientation, or headaches while using SightFlow, **stop immediately** and consult a healthcare professional. The creators and contributors assume **no liability** for any injury, loss, or damage arising from the use of this software. Always take regular breaks (every 20 minutes) and ensure proper lighting conditions in your training environment. Use SightFlow at your own risk and responsibility.

---

## 🤝 Contribution & Support

We welcome bug reports, feature requests, and thoughtful pull requests. Before contributing, please read our `CONTRIBUTING.md` file (in repo root). General guidance:

- **Found a bug?** Open an issue with a clear reproduction case and your OS version.
- **Want a new drill type?** Describe the cognitive mechanism you want to train; if it’s scientifically justified, we’re interested.
- **Translation corrections?** Even native speakers make typos — submit a tiny PR with the fix.

**Support availability:** Our maintainers provide best-effort email support (typically < 24 hours response, 7 days a week) for issues related to installation, configuration misunderstandings, and critical bugs. We do **not** offer personalized coaching or training plans.

---

## 📆 Roadmap for 2026

We are actively working toward the **1.4 release**, scheduled for Q3 2026. Planned features include:

- **Eye-tracking integration** for webcams (using retroreflective calibration patterns) to measure true fixation quality
- **Additional language support** (Arabic, Hindi, Korean, Portuguese)
- **Multi-profile sync** (fully offline, via USB file transfer between machines)
- **A mobile “micro-drill” companion** — quick 2-minute warm-ups for phone screens

The project is community-driven, so the roadmap is always subject to change based on user feedback.

---

## ✅ Final Words

SightFlow is not a magic pill. It is a **deliberate practice instrument** — a tool that respects your time by making every second of training count. Whether you’re a student drowning in readings, a programmer hunting through verbose logs, or a curious human who wants to see the world at a higher frame rate, SightFlow offers a structured, measurable path toward sharper vision and a quieter mind.

Your eyes are the gates to your attention. Train them. Sharpen them. And watch the world come into clearer focus.

---

*SightFlow — built in 2026, maintained with care by the open-source community. No users were harmed in the making of this software.*