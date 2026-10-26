# NeutronGate

**A fully local Japanese AI, written in Rust, running on CPU only.**

> Source code is private. This repository describes the project.

NeutronGate is a research project by [NEXSPACE](https://www.nexspace.jp) exploring whether a conversational Japanese AI can be built on an associative-memory architecture instead of a large transformer — small enough to run entirely on an ordinary laptop CPU, with no cloud and no GPU.

## Core: 360-DQHM

A holographic associative memory based on Vector Symbolic Architecture.

- **360-dimensional complex vector space** for encoding concepts
- **Synaptic Permutation Binding** to compose concepts into structured memories
- **Phase-resonance similarity** for recall
- Constant-time retrieval, independent of memory size
- No GPU required

## Design principles

- **Measure, don't feel.** Conversation quality is scored by an evaluation harness across five categories (word-salad resistance, short conversation, natural chat, knowledge answers, safety control). "It feels better" is not accepted as progress.
- **No canned answers.** Fixed replies, per-input answer maps and template sprawl are explicitly forbidden.
- **Fully local.** Nothing leaves the machine.

## Status

Active development on a CPU-only build (Intel i5-6200U laptop). Current work: the generator and the internals of 360-DQHM (resonance-reflection mechanism, mapping, dedicated generator compute).

## Related

- Papers on Zenodo: [18922676](https://zenodo.org/records/18922676), [18815443](https://zenodo.org/records/18815443)
- Contact: contact@nexspace.jp

---

**日本語**：NeutronGateは、Rust製・CPUのみで動作する完全ローカルの日本語AIです。大規模なTransformerではなく、360次元複素ベクトル空間のホログラフィック連想記憶「360-DQHM」を中核にしています。ソースコードは非公開で、このリポジトリでは概要のみを公開しています。
