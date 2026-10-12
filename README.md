# Engineering Learning Lab

> Hands-on engineering experiments connecting infrastructure tools and Python libraries through shared concepts, reproducible examples, and technical reflections.

This is a personal curriculum, written in the open. Each phase pairs an infrastructure tool with a Python library and investigates one shared idea — not as an equivalence claim, but as a structured comparison.

The experiments use real code from my other projects ([OpenBI](https://github.com/adnanphp/openbi), [openbi-aws-cloud](https://github.com/adnanphp/openbi-aws-cloud), [openbi-gcp-cloud](https://github.com/adnanphp/openbi-gcp-cloud)). Reading about a concept is useful; changing something and observing the result is much more memorable.

## Why this exists

Most engineers accumulate tools without ever unpacking what each one *teaches*. After a while, "I've used Docker" and "I understand Docker's image model" become two very different claims, and only the second one matters.

Each phase here is one attempt to close that gap: pick a tool, find the concept it embodies, prove it with a small experiment, and write about it in my own words.

## What a phase looks like
0N-<infra>-and-<python>/
├── README.md ← phase overview
├── <infra>/ ← runnable experiments for the infra tool
├── <python>/ ← runnable experiments for the Python library
├── experiments/ ← observations, measurements, notes
└── reflection.md ← the deliverable: my own words

text

## Roadmap

See [ROADMAP.md](ROADMAP.md) for the 10 planned phases and their status.

See [CONCEPTS.md](CONCEPTS.md) for the concept map: which tool teaches which idea.

## Important caveat

Some pairings in the roadmap are **analogies**, not equivalences. A Docker image layer and a NumPy array view are not the same mechanism. One concerns container-image construction and caching; the other concerns how an array accesses memory.

The learning opportunity is to compare their structure, reuse behavior, and implications — **not** to claim they work identically. Each phase's `reflection.md` documents where the analogy holds and where it breaks down.

## Status

This repository is a work in progress, built one phase at a time. Phases with no code yet are marked 📋 in [ROADMAP.md](ROADMAP.md).

## License

MIT
