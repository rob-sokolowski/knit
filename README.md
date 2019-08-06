# Open questions

## Logical \<-> physical data storage

Local FS, S3, relational DB, Google Sheets, Google Drive.
Non-storage mediums: e-mail, message queue, RPC, Slack, Arrow.
Immutability (tamper proofing) vs tamper evidence.
Storage system abstraction.

## Side effects

Actions: publish, Slack.

## Asynchronicity

Manual: QA, closed data analysis, Mechanical Turk.
Long-running operations.
Convergent operations: model training.

## Datasets

Defined by flow?
vs directories.

## Resource abstractions (unit, job result, direct inputs)

## Non-materialized transforms

DB views.
Streaming pipelines.

## Streaming data

In some use cases, maybe data partitioning.
vs Nifi.

## Reusability

Flow parameterization.
Instantiate parameterized flow with overridden units.
Relate to parameterized type systems, traits.
Open-closed principle. Composition (trait-like) vs overrides (OOP-like).

## Modularity

1:1 w/ flows?

## Dependency graph evaluation

Runtime vs top-down dynamic vs static.

## Inter-flow dependencies

# TODO

## Demo features

- Pipeline history by target unit
- Reddit voting

## Value props

- Collaboration and commenting
- Data vetting
- Frictionless branching
- Templatized presentation

## Logical units

- csv
- sql
- jinja
- html
- command