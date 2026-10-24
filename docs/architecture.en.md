# Architecture — Elyne Next

[Français](architecture.md) · [Overview](../README.en.md)

## Simplified flow

Interaction → orchestration and context → resident model via EIE → scoped tools → persistent memory/retrieval/journal → sourced answer.

## Components and boundaries

- The resident model provides inference; memory, versioned beliefs, and documents remain in application-owned stores.
- Retrieval combines lexical indexing and embeddings; provenance accompanies items reused in context.
- Tools access authorized resources. A tool interface alone does not prove OS isolation or denial of every direct path.

This textual flow describes the product architecture. It does not replace verification on a specific build, hardware profile, and configuration. The [evidence summary](evidence.en.md) states what is actually documented.
