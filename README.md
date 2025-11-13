# Intermit

Intermit is an early stage exploration of how to structure digital work so it can be put down and picked up again across long stretches of time. We are at the ideation phase and focused on a problem that sits above traditional preservation. Many groups already work on the technical layers of long term storage and access, including efforts like [ISO 16363](https://www.iso.org/standard/56510.html), [Software Heritage](https://www.softwareheritage.org), the [Internet Archive](https://archive.org), and century scale storage research from the Library Innovation Lab at Harvard ([link](https://lil.law.harvard.edu/century-scale-storage)). These efforts are essential, and we want to build on the best practices they promote. At the same time, they solve a different part of the puzzle. Intermit concentrates on continuity and comprehension: how people, teams, and communities can understand, resume, and reuse work after long pauses.

A project can have perfect bit preservation in formats that remain readable and still be unusable. Files may survive, but the unwritten logic, intentions, structures, and tacit knowledge behind the work may disappear. Intermit focuses on this gap: the human ability to re-enter work in the future, not only the technical guarantee that data remains intact.

## Progressive Longevity

Progressive longevity is the idea that every project should have a set of stable elements that stay understandable and usable even as tools evolve. These elements might take the form of a single stable core or multiple modular cores that each remain durable on their own. The point is not to preserve everything, but to ensure that the parts that matter are easy to resume.

This differs from archival approaches. Progressive longevity is concerned with future readability, structure, and navigability, not just storage. Someone returning after years should be able to understand the shape of the work, where to start, and how to continue. Stable or modular cores might involve open, human readable formats, clear directory layouts, minimal build instructions, or a short guide explaining how to restart.

A future Progressive Longevity Framework might offer patterns and small conventions that help teams create these durable cores without adding unnecessary complexity.

## Tacit Burden

Tacit burden refers to hidden complexity inside tools, datasets, and systems. Preservation efforts can keep the files and formats readable, but they cannot capture the undocumented decisions, heuristics, contingencies, and institutional memory that make something workable in practice. Intermit focuses on this missing layer.

Many technologies appear simple but hide years of accumulated behavior, such as:
- regular expression engines with incompatible edge cases  
- Unicode text shaping systems like [HarfBuzz](https://harfbuzz.github.io)  
- compilers whose quirks become relied on over decades  
- datasets shaped by tacit institutional knowledge or opaque preprocessing  
- curated or proprietary corpora such as the Pandora Music Genome Project  

These components are theoretically reproducible but practically very difficult to recreate. Intermit explores ways to make this hidden complexity more visible and documentable so that future contributors can understand and work with it safely. A Tacit Burden Rating System is one example of what this could look like.

## Modular Survivability

Modular survivability addresses the fact that many projects fail because everything is too entangled. When a large initiative slows or ends, useful pieces often vanish along with it simply because they were never separated.

Modular survivability promotes designs where durable parts can stand alone. This applies to specifications, schemas, code libraries, curated data, and research tools. The goal is to make it easy for future contributors to extract, preserve, migrate, or adopt the parts that still have value without requiring the full project to continue. Future guides might describe patterns for identifying these components and structuring repositories so that they can persist independently.

## How to Get Involved

Intermit welcomes collaborators, curious readers, and constructive critics.  
If you are thinking about continuity, understandability, digital public goods, or ways to make long lived work easier to resume, we would love to hear from you. Open an issue or start a discussion. We keep things simple and friendly.  ♡

---

Intermit - put it down, pick it up later.
