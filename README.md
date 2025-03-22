<!-- omit from toc -->
# Awesome Formal AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of recent advancements in formal reasoning AI, including but not limited to papers and datasets about autoformalization, (semi-)automated theorem proving, code verification, and so on.

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

<!-- omit from toc -->
## Table of Contents

- [Models](#models)
- [Datasets](#datasets)
- [Benchmarks](#benchmarks)
- [Papers](#papers)

## Models

| Time | Name | Language | Links |
|------|------|----------|-------|
| 2025.02 | Goedel-Prover | Lean 4 | [[HuggingFace]](https://huggingface.co/Goedel-LM/Goedel-Prover-SFT) [[pdf]](https://arxiv.org/abs/2502.07640) |
| 2025.02 | STP | Lean 4 | [[HuggingFace]](https://huggingface.co/kfdong/STP_model_Lean) [[pdf]](https://arxiv.org/pdf/2502.00212) |
| 2024.10 | InternLM2.5-Step-Prover | Lean 4 | [[HuggingFace]](https://huggingface.co/internlm/internlm2_5-step-prover) [[pdf]](https://arxiv.org/abs/2410.15700) |
| 2024.08 | DeepSeek-Prover-V1.5 | Lean 4 | [[HuggingFace]](https://huggingface.co/deepseek-ai/DeepSeek-Prover-V1.5-RL) [[pdf]](https://arxiv.org/pdf/2408.08152) |
| 2023.06 | ReProver | Lean 4 | [[GitHub]](https://github.com/lean-dojo/ReProver) [[pdf]](https://arxiv.org/pdf/2306.15626) |

## Datasets

NL indicates problem statements in natural language.

| Time | Name | Language | Proof | Size | Links |
|------|------|----------|-------|------|-------|
| 2025.02 | STP | Lean 4 | ✅ | 1.7M | [[HuggingFace]](https://huggingface.co/datasets/kfdong/STP_Lean) [[pdf]](https://arxiv.org/pdf/2502.00212) |
| 2024.06 | Lean-Workbook | NL, Lean 4 | 🟨 | 140k | [[HuggingFace]](https://huggingface.co/datasets/internlm/Lean-Workbook) [[pdf]](https://arxiv.org/pdf/2406.03847) |
| 2023.06 | LeanDojo | Lean 3 & 4 | ✅ | 122k | [[Lean 3]](https://zenodo.org/doi/10.5281/zenodo.8016385) [[Lean 4]](https://zenodo.org/doi/10.5281/zenodo.8040109) [[pdf]](https://arxiv.org/pdf/2306.15626) |

## Benchmarks

Italics indicates that some problems are unavailable in this language. Asterisk indicates that this language is provided by the community.

| Time | Name | Language | Size | Links |
|------|------|----------|------|-------|
| 2024.07 | PutnamBench | NL, Lean 4, Isabelle, *Coq* | 657 | [[GitHub]](https://github.com/TrishulLab/PutnamBench) [[pdf]](https://arxiv.org/pdf/2407.11214) |
| 2023.02 | ProofNet | NL, Lean 3 & 4* | 371 | [[GitHub]](https://github.com/zhangir-azerbayev/ProofNet) [[Lean4 ver.]](https://github.com/rahul3613/ProofNet-lean4) [[pdf]](https://arxiv.org/pdf/2302.12433) |
| 2021.09 | MiniF2F | NL*, Lean 3 & 4*, Metamath, Isabelle, *Hol Light* | 488 | [[GitHub]](https://github.com/openai/miniF2F) [[NL ver.]](https://github.com/rah4927/lean-dojo-mew) [[Lean4 ver.]](https://github.com/yangky11/miniF2F-lean4) [[pdf]](https://arxiv.org/pdf/2109.00110) |

## Papers

This category only includes papers not mentioned in the above lists.

| Time | Name | Links |
|------|------|-------|
| 2024.12 | Formal Mathematical Reasoning: A New Frontier in AI | [[pdf]](https://arxiv.org/pdf/2412.16075) |
| 2023.10 | LEGO-Prover: Neural Theorem Proving with Growing Libraries | [[pdf]](https://arxiv.org/pdf/2310.00656) |
