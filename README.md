# Yerkhat Takatbek

I build AI systems and measure how they behave once they are deployed. Kazakhstan.

## Making AI agents do what they are told

**[fledge](https://github.com/Yerkhat1/fledge)** — a control plane for the agents a business already runs. Describe a change in plain English; Fledge restates it, applies it, replays test conversations against the edited agent, and refuses the change if behaviour moved where it should not have. Running since September 2026, invite-only. This repo is the public MVP snapshot; development continues privately with team Artifex.

**[agent-instruction-files](https://github.com/Yerkhat1/agent-instruction-files)** — the same question asked empirically. Do the rules people write into `CLAUDE.md` and `AGENTS.md` change the code? Measured across 753 rules in 410 public repositories with AST checks and no model judging. Two thirds of rules describe code that already complied. Among rules that did ask for change, those backed by a linter closed about three times more of the remaining gap than rules written only as prose, and both groups edited a similar share of their files, so the difference is not reach. Dataset, pipeline, and a script that recomputes every published figure are in the repo.

At **ADMIT**, an admissions ed-tech company, I build the multi-agent system its mentors work in: specialist agents for research, essays and program matching across 72 live student cases, and verification rules that stop an agent asserting a deadline or a test score without a quoted source. That system is private, and the research above came out of working on it.

## Language and learning tools

**[aralas-oqu](https://github.com/Yerkhat1/aralas-oqu)** — Kazakh morphology is algorithmic, so exercises can be generated from a bare word list and every answer explained by its derivation. The grader accepts Russian-keyboard spellings because that is what learners in Kazakhstan type; the scheduler tracks a lexeme and a skill as separate memories, which is where learners of an agglutinative language actually fail. [Live](https://yerkhat1.github.io/aralas-oqu/).

**[mechanics-exam-trainer](https://github.com/Yerkhat1/mechanics-exam-trainer)** — timed practice exams from a 150-problem bank, graded the way the course grades: 90% the number, 10% the unit. Writing tests for the grader found a bug that was quietly costing students the unit mark on correct answers. [Live](https://yerkhat1.github.io/mechanics-exam-trainer/).

**[tandem](https://github.com/Yerkhat1/tandem)** — shared semester planner that fits study blocks into the real gaps in two people's timetables. [Live](https://yerkhat1.github.io/tandem/).

## Elsewhere

Google Developer Groups organizer in Taldykorgan and Almaty.
