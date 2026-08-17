# Project Source Index / Retrieval Map — Master Status

## Purpose

Master File 5 is the project navigation and provenance master.

It maps:

- public source families
- private-only source boundaries
- canonical maintainable inputs
- generated packaging artifacts
- relationships between project source families

It does not replace or override substantive trading-rule masters.

## Public Source Layer

The public source layer is maintained under:

`source-index/`

These Markdown files are the canonical public-safe provenance inputs.

## Private Build Layer

The collapsed master is generated through a private manifest, builder, and one-command wrapper.

These private packaging files are not part of the public repository.

## Generated Outputs

The stable and latest Project Source Index text files are generated packaging artifacts.

They are rebuilt from the public provenance source layer in controlled manifest order.

## Status

Master File 5 is operational and rebuildable.

Final integrity checks confirmed:

- all manifest-listed public sources exist
- stable and latest outputs match
- the one-command rebuild works independently of the current working directory
- the public repository contains no unintended changes
