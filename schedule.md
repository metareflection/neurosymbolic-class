# Schedule

## Week 1

### Tuesday, September 2

First day of class.
TF Matthew Retchin lead a discussion on the taxonomy of neurosymbolic programming.

### Thursday, September 4

TF Matthew Retchin leads an introductory session.

- _Hybrid computing using a neural
network with dynamic external memory_ ([PDF](https://gwern.net/doc/reinforcement-learning/model-free/2016-graves.pdf)) by Graves et al. in Nature 2016.

## Week 2

### Tuesday, September 9

[Gabriel Poesia](https://gpoesia.com/), incoming Kempner fellow, will give a guest lecture.
- (NeurIPS 2024) Minimo: _Learning Formal Mathematics From Intrinsic Motivation_ ([code](https://github.com/gpoesia/minimo), [paper](https://arxiv.org/abs/2407.00695)).
- (Dafny 2025) _dafny-annotator: AI-Assisted Verification of Dafny Programs_ ([code](https://github.com/metareflection/dafny-annotator), [paper](https://arxiv.org/abs/2411.15143), [blog](https://dafny.org/blog/2025/06/21/dafny-annotator/)).

### Thursday, September 11

No class.

## Week 3

### Tuesday, September 16

We set the schedule for the course.

### Thursday, September 18

Prof. Nada Amin discusses her work at the intersection of formal verification and LLMs.

Some links:
- Relaxed Machines: [namin/relaxed-machines](https://github.com/namin/relaxed-machines)
- VerMCTS: [namin/llm-verified-with-monte-carlo-tree-search](https://github.com/namin/llm-verified-with-monte-carlo-tree-search)
- Dafny Sketcher: [namin/dafny-sketcher](https://github.com/namin/dafny-sketcher)
- dafny-annotator: [metareflection/dafny-annotator](https://github.com/metareflection/dafny-annotator)
- Software archaeology of Eurisko: [namin/eurisclo](https://github.com/namin/eurisclo)
- LeanDisco: [namin/LeanDisco](https://github.com/namin/LeanDisco)
- Holey: [namin/holey](https://github.com/namin/holey)
- Argument Debugger & Argir: [namin/argument-debugger](https://github.com/namin/argument-debugger) & [namin/argir](https://github.com/namin/argir)

## Week 4

### Tuesday, September 23

Simon leads a session on mathematical reasoning with LLMs.

- Reading of the day:
  - _DeepSeek-R1 incentivizes reasoning in LLMs through reinforcement learning_ ([Nature'25](https://www.nature.com/articles/s41586-025-09422-z)).
  - Extra: _DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models_ ([PDF](https://arxiv.org/pdf/2402.03300)).
- [Reasoning Gym](https://github.com/open-thought/reasoning-gym).
- [Open Proof Corpus](https://proofcorpus.ai).

### Thursday, September 25

Dennis leads a session on constraint decoding, grammar aligned and semantically constrained.

- Reading of the day: _ChopChop: a Programmable Framework for Semantically Constraining the Output of Language Models_ ([paper](https://arxiv.org/abs/2509.00360)).

## Week 5

### Tuesday, September 30

Valerio leads a session on program synthesis and library learning, with a focused reading on _DreamCoder_ ([PLDI'21](https://dl.acm.org/doi/10.1145/3453483.3454080) edition).

- _DreamCoder: growing generalizable, interpretable knowledge with wake–sleep Bayesian program learning_
  - [PLDI'21](https://dl.acm.org/doi/10.1145/3453483.3454080)
  - [Royal Society](https://royalsocietypublishing.org/doi/10.1098/rsta.2022.0050)
  - [code](https://github.com/ellisk42/ec)
- Stitch: _Top-Down Synthesis for Library Learning_
  - [POPL'23](https://arxiv.org/abs/2211.16605)
  - [code](https://github.com/mlb2251/stitch)
  - [docs](https://stitch-bindings.readthedocs.io/en/stable/)
- _LILO: Learning Interpretable Libraries by Compressing and Documenting Code_
  - [ICLR'24](https://arxiv.org/abs/2310.19791)
  - [code](https://github.com/gabegrand/lilo)
- Application to recovering Chinese characters: _Finding structure in logographic writing with library learning_
  - [CogSci'24](https://arxiv.org/abs/2405.06906)
  
### Thursday, October 2

[Paul Krogmeier](https://paulkrog.github.io/), postdoctoral fellow, will give a guest lecture. Some papers:
- Reading of the day: _Synthesizing DSLs for Few-shot Learning_ (OOPSLA'25) ([PDF](https://paulkrog.github.io/papers/DSLSynth.pdf)).
- _Synthesizing Axiomatizations using Logic Learning_ (OOPSLA'22) ([PDF](https://paulkrog.github.io/papers/LasOOPSLA22.pdf)).
- _Languages with Decidable Learning: A Meta-theorem_ (OOPSLA'23) ([PDF](https://paulkrog.github.io/papers/MetaTheorem.pdf)).

Reading guide from Paul:
- Focus on reading of the day.
- First, read Sections 1, 2, and 4.
- Second, read the problem statements in Sections 5 and 6.
- Rest of the paper is very optional, including the proofs.
- Read with an eye toward conceptual differences with DreamCoder and library learning
- Paul will talk about "Axiom synthesis" and "Languages with...", but they can be skimmed.

## Week 6

### Tuesday, October 7

Mike leads a session on automated theorem proving.

- Reading of the Day: _Reviving DSP for Advanced Theorem Proving in the Era of Reasoning Models_ ([paper](https://arxiv.org/abs/2506.11487))

- Extra: _Proving Theorems Recursively_ ([paper](https://neurips.cc/virtual/2024/poster/93034), [alt](https://arxiv.org/abs/2405.14414))

### Thursday, October 9

Jeremy leads a session on programming prompts.

- _Prompting Is Programming: A Query Language for Large Language Models_ (PLDI'23) ([paper](https://dl.acm.org/doi/abs/10.1145/3591300)).

## Week 7

### Tuesday, October 14

Richael leads a session on jailbreaking and particular solutions involving PL+AI.

- Reading of the day: _R2-Guard: Robust Reasoning Enabled LLM Guardrail via Knowledge-Enhanced Logical Reasoning_ ([paper](https://arxiv.org/abs/2407.05557)).
- Optional reading: _Constitutional Classifiers: Defending against Universal Jailbreaks across Thousands of Hours of Red Teaming_ ([paper](https://arxiv.org/abs/2501.18837))

### Thursday, October 16 (Assignment 1 Due)

[Dat Nguyen Thanh](https://github.com/datvo06), postdoctoral fellow, will give a guest lecture on prompt optimization and tool orchestration.

- Reading of the day: _GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning_ ([paper](https://arxiv.org/abs/2507.19457)).
- Extra: _Optimizing Instructions and Demonstrations for Multi-Stage Language Model Programs_ ([paper](https://arxiv.org/abs/2406.11695)).
- Code: [DSPy](https://dspy.ai/).

## Week 8

### Tuesday, October 21

Milligan leads a session on evaluating "intelligence".

- _On the Measure of Intelligence_ ([paper](https://arxiv.org/abs/1911.01547)). See also [ARC Prize](https://arcprize.org/).
- _Sudoku-Bench: Evaluating creative reasoning with Sudoku variants_ ([paper](https://arxiv.org/abs/2505.16135)).

### Thursday, October 23

Suhwan leads a session on neural causal modeling.

- [Neural Algorithmic Reasoning with Causal Regularisation](https://proceedings.mlr.press/v202/bevilacqua23a).

## Week 9

### Tuesday, October 28 (Project Proposals Due)

Zekai leads a session focusing on _Statically Contextualizing Large Language Models with Typed Holes_ ([OOPSLA'24](https://dl.acm.org/doi/10.1145/3689728)).

### Thursday, October 30

Discussion on project proposals.

## Week 10

### Tuesday, November 4

Jeffrey leads a session focusing on _SWE-Search: Enhancing Software Agents with Monte Carlo Tree Search and Iterative Refinement_ ([paper](https://arxiv.org/abs/2410.20285)).

### Thursday, November 6

Arya leads a session on using DSPy for his research, _SwizzlePerf: Hardware-Aware LLMs for GPU Kernel Performance Optimization_ ([paper](https://arxiv.org/abs/2508.20258)).

## Week 11

### Tuesday, November 11

Theo leads a session on AlphaGeometry ([blog](https://deepmind.google/discover/blog/alphageometry-an-olympiad-level-ai-system-for-geometry/), [paper](https://www.nature.com/articles/s41586-023-06747-5)) and AlphaGeometry 2 ([paper](https://arxiv.org/pdf/2502.03544)).

### Thursday, November 13

Each student briefly discusses a library/software artifact that they plan to use or that inspires them.

## Week 12

### Student Presentations of their Ongoing Projects

### Tuesday, November 18

### Thursday, November 20

## Week 13

### Tuesday, November 25

Project workout.

### Thursday, November 27

Thanksgiving.

## Week 14

### Tuesday, December 2

Last day of class.

TF Matthew Retchin presents his research.
