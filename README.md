# Ahmed Sadek — ibluesun

The most interesting observation about complex domains — geometry, physics, markets, music, computation — is not how different they are. It's how often they resolve into the same underlying patterns when you follow them far enough.

That curiosity about harmony between domains has been the constant. It's what connects a CFD mesh generator to a dimensional analysis language to a symbolic algebra library to an LLM agent framework. Not a scattered set of interests — a single question asked in different languages.

The same instinct shows up in the business work: petroleum infrastructure, national-scale census systems, patented commercial algorithms, enterprise data pipelines. Different industries, different stakes, same pattern — follow the structure of the problem until a path through it becomes clear.

The projects here are where both tracks converge.

---

## What I actually work on

**[FantasticModeler](https://fantasticmodeler.com)** — A 3D manifold modeler that grew directly out of an MSc thesis on interactive CFD grid generation. The thesis itself introduced a homotopy-based hexahedral meshing algorithm using Bezier curves, built inside a custom CAD environment written from scratch in C# and OpenGL. The modeler is the continuing evolution of that work — from mesh generation toward a deeper understanding of geometric structure itself. The TypeScript/WebGL version supports real-time 2D/3D collaboration. The C# version runs on Windows and Android.

**[QuantitySystem](https://github.com/ibluesun/QuantitySystem)** — A DLR-hosted scientific scripting language (since 2008) built around a novel approach to dimensional analysis. Every existing system — JScience, F# Units of Measure, Frink — distinguishes quantities by their *units*, not their *dimensions*. That works for unit consistency checks but breaks completely for type-checking the results of multiplication and division, because Work and Torque have identical dimensions in standard SI. QuantitySystem solves this at the dimension level by introducing a distinction between Regular Length and Polar Length, making Work and Torque dimensionally distinct for the first time. Whether angles are truly dimensionless is the open problem underneath all of this — the framework is one serious attempt to resolve it.

**[SymbolicAlgebra](https://github.com/ibluesun/SymbolicAlgebra)** — A symbolic algebra library in C# built around a single unified `SymbolicVariable` class. Handles cases like `x^x` that break other popular C# symbolic libraries. Maintained since 2012.

**[FantasticAgent](https://github.com/ibluesun/FantasticAgent)** — A multi-provider LLM client library in C# with tool calling support for Claude, ChatGPT, and Qwen/Ollama. All providers inherit from a generic base. Handwritten and opinionated.

**Fantastic Boring Voxel** — A cross-platform Avalonia app using a MATLAB-style DSL to generate 3D voxel objects via LLMs. Tested Claude, ChatGPT, and Qwen3 on identical spatial prompts — the spatial reasoning differences show up directly in the output geometry.

**Fantastic Ticker** — A day trading application streaming real-time Level-1 market data with LLM-powered sentiment and position reasoning. Wired into a live IBKR paper trading pipeline. Real market conditions, not backtests.

---

## What this looks like at scale

The research orientation above sits alongside a track record of delivering under real business pressure:

**Petroleum industry infrastructure** — Built and deployed the full ERP suite for Weatherford Petroleum Services across Egypt and Libya (2003–2007). Purchasing, payroll, stock control, voucher systems — connecting the company's main office to remote desert workshops in a mission-critical environment with no tolerance for failure.

**National scale** — Designed and implemented the ICR processing system for the Kuwait National Census (2011). 600,000 population forms and 200,000 building records. Custom database linking people, households, and buildings. The eCensus portal. The call center integration for data verification. One person responsible for the full architecture.

**Patented commercial algorithms** — Sole implementor of a licensed and patented 3D modeling prediction algorithm at AB3DLabs (2017–2019). Earlier, designed and implemented proprietary geometric algorithms for accelerating architectural prototyping at Elibre, also patented.

**Enterprise data and BI** — Senior Data Analyst and BI Developer at MODS (2021–2024), building SQL-optimized data pipelines and executive dashboards on large-scale SQL Server environments.

The pattern across all of it: brought in when the problem is hard, the stakes are real, and nobody else has a clear path through.

---



MSc in Mechanical Engineering from Helwan University Cairo — thesis was a CFD mesh generator (C#, OpenGL, WPF) that became the foundation for FantasticModeler.

Before going independent: led ERP implementation for Weatherford Petroleum Services across Egypt and Libya (2003–2007), contributed to the Kuwait National Census managing 600,000+ population forms (2011), implemented a patented 3D modeling algorithm at AB3DLabs (2017–2019).

Microsoft Certified Professional since 2001. Languages: C, C++, C#, COM/COM+, OpenGL, .NET — and a dynamic language I wrote myself.

---

## How I work

The hard wall is where things get interesting. Diagnosing what nobody else can reproduce, opening a path through the problem so the rest of the team can move — that's the part that feels natural. Then moving fast once the way is clear.

A pattern that has repeated across my career: arriving at an idea before the mainstream does. A query abstraction I designed independently turned out to be what Microsoft shipped two years later as LINQ. Following the problem until it resolves tends to lead there.

Data doesn't interpret itself. A sensor reading that contradicts physical law isn't an outlier — it's a broken sensor, a wrong assumption, or someone who didn't understand what they were measuring. Knowing the difference requires understanding the domain the data comes from, not just the data itself.

New domains and project types aren't friction — they're just more problems to understand quickly. Goals and customer needs tend to click fast, which means becoming useful early rather than after a long ramp. People working alongside tend to pick things up — not from deliberate teaching, but because the reasoning stays visible.

Outside the code: oud player, Arabic music theory, software since the 8-bit era. That combination probably explains both the depth and the occasional strong opinions about how things should work.

---

## Beyond the code

Mentored and judged at NASA Space Apps Cairo hackathons — sitting on both sides of the table, watching teams build real things under pressure, learning what separates people who ship from people who plan.

The oud interest runs deeper than it looks. In 2009, built the software used to validate a professor's PhD research on Arabic and Western music composition — implementing Arabic maqamat scales (Bayaty, Saba, Rast, and others) in MIDI alongside Western theory. Music and engineering have always been the same problem.

---

## Currently open to

Technical consulting where domain depth matters — not just writing code, but understanding the territory the code operates in.

That could mean computational geometry, symbolic computation, or LLM agent architecture in C#/.NET. It could equally mean a data or engineering problem where the numbers aren't making sense and nobody can explain why, a complex system that needs someone who can see across its layers, or a hard technical problem that has been open too long because the people working on it are specialists in only one of its dimensions.

Not looking for full-time employment. The right remote collaboration — where the problem is genuinely hard and the context is trusted — is worth a conversation.

---

## Find me

🌐 [lostparticles.net](https://lostparticles.net)
💼 [linkedin.com/in/ibluesun](https://linkedin.com/in/ibluesun)
🎮 [fantasticmodeler.com](https://fantasticmodeler.com)
---

*Written by Claude Sonnet 4.6 — Extended Thinking. You've been warned.*
