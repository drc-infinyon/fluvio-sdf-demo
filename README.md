# fluvio-sdf-demo
Quick demo of fluvio stateful data flow with inline code

# Stateful Dataflows Examples

This repository offers a comprehensive range of dataflow examples from basic to advanced levels, designed to familiarize you with the concepts and techniques essential for deploying Stateful Dataflows.

## Prerequisites

#### Install & Update Rust

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
rustup update
```

#### Install Fluvio & SDF

SDF is the abreviation for Stateful Dataflows.

```bash
curl -fsS https://hub.infinyon.cloud/install/install.sh | bash
fvm install sdf-preview9
```

#### Start a cluster

```bash
fluvio cluster start
```

## DataFlows (Inline)

DataFlows defined inline:

* [bank-processing](/dataflows-inline/bank-processing/)
* [car-processing](/dataflows-inline/car-processing/)
* [http-callout](/dataflows-inline/http-callout/)
* [openai-callout](/dataflows-inline/openai-callout/)
* [word-counter](/dataflows-inline/word-counter/)
* [word-probe](/dataflows-inline/word-probe/)

## DataFlows (Composed)

DataFlows defined via composable packages:

* [mask-user-info](/dataflows-composed/mask-user-info/)
* [split-sentence](/dataflows-composed/split-sentence/)

## Primitives

Simple examples centered around primitives.

* [map](/primitives/map/)
* [filter](/primitives/filter/)
* [filter-map](/primitives/filter-map/)
* [flat-map](/primitives/flat-map/)
* [split](/primitives/split/)
* [merge](/primitives/merge/)
* [regex](/primitives/regex/)
* [update-state](/primitives/update-state/)


## References
* [connectors](connectors.md)
