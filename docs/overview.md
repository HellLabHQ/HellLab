# What we’re building

When you ship a desktop application, parts of your product’s logic ship with it. That might be a scoring algorithm, a data-processing routine, or a feature that took months to build. HellLab MAX focuses on making selected logic harder to reconstruct and making changes to protected files detectable.

We’re working with three approaches. Code virtualization changes how selected logic is represented and executed. Obfuscation adds work for someone reading the compiled code. Integrity checks help detect changes to files covered by the build.

## How we’ll evaluate it

We want to compare protected and unprotected builds of the same workload. First we’ll check that both produce the same outputs. Then we’ll measure runtime and file size so developers can see what the protection costs. Trial #003 covers a different question: whether someone can reconstruct the behavior of a few protected functions.

The project is still in development. This repository is home to public documentation and evaluation notes.

[Back to HellLab](../README.md) · [Trial #003](trial-003.md)
