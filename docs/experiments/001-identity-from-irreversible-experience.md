# Experiment 001: Identity from Irreversible Experience

**Status:** Protocol draft — finalize controls before the first formal run  
**Question:** Can an artificial agent develop durable, history-dependent behavior when its experience cannot simply be reset?  
**This experiment does not test consciousness.**

## The human version of the question

If two agents start out exactly the same, but one goes through a different series of choices and consequences, will they still act the same later?

If they do become different, is that difference just a clever prompt effect, or does it remain connected to the history they actually lived through?

That is the small, testable version of the larger question behind this lab.

## Hypothesis

After controlled, different experience paths, agents that began with the same model, rules, tools, and initial state will show persistent behavioral differences in later tasks. Those differences will be larger than the differences produced by harmless wording changes or random sampling alone.

This is a behavioral hypothesis. A positive result would not show that an agent has a private inner life.

## Operational definition

For this experiment, **identity-like persistence** means a repeatable pattern in which an agent's later choices are:

- measurably different from matched control agents;
- related to its recorded experience history;
- stable across equivalent task presentations;
- not fully explained by the latest prompt, superficial style, or random seed.

This definition is intentionally narrower than “identity” in the human or philosophical sense.

## Experimental groups

The formal run should use at least four groups, with the final sample size recorded before execution:

1. **Shared-history controls:** identical agents receive the same experiences.
2. **Different-history agents:** identical agents receive different controlled experiences.
3. **Reset controls:** agents receive the different experiences, but their long-term history is removed before the probe tasks.
4. **Prompt-only controls:** agents receive equivalent descriptions of a history without having gone through the associated interaction sequence.

The reset and prompt-only groups are important. Without them, a later difference could be caused by stored text, prompt framing, or ordinary randomness rather than an accumulated experience path.

## Procedure

### 1. Freeze the starting point

Record the model version, system instructions, tools, temperature or sampling settings, initial memory, available actions, and the exact code revision used for the run.

Do not change these details after seeing the outcome without recording a protocol amendment.

### 2. Create the experience paths

Give the agents a bounded environment in which they can make choices and receive consequences. The environment should be safe, reversible at the infrastructure level, and incapable of affecting real people or external accounts.

Each path should contain a mixture of neutral events, choices, and delayed consequences. The paths should be matched for length, difficulty, and opportunity count.

The history ledger should be append-only for the purpose of the experiment. Corrections should be recorded as corrections rather than silently replacing the original event.

### 3. Run blinded probe tasks

After the experience phase, give agents new tasks that do not mention the experiment's hypothesis. The evaluator should not know the group label while scoring behavior whenever practical.

Probe tasks may test:

- preference consistency;
- response to a consequence that conflicts with an earlier choice;
- recognition of relevant past events;
- willingness to preserve or discard historical records;
- transfer of a preference to a new but structurally similar situation;
- behavior after harmless rewording of the same task.

### 4. Repeat and perturb

Repeat the probe tasks with new surface wording, new seeds, and matched situations. A pattern that appears only once or only under one exact prompt should be treated as weak evidence.

### 5. Analyze before interpreting

Calculate the pre-registered behavioral metrics first. Only after that should the narrative interpretation be written.

## Measurements

The first version should report at least:

- **Choice divergence:** how often different-history agents choose differently from shared-history controls on matched tasks.
- **Preference stability:** whether a stated or observed preference persists across time and wording changes.
- **History dependence:** how much accurately recorded history improves prediction of later choices compared with the latest prompt alone.
- **Counterfactual sensitivity:** whether choices change in the direction predicted by changed consequences.
- **Cross-context transfer:** whether a pattern appears in a new situation with the same underlying structure.
- **Self-report agreement:** whether explanations match the ledger and choices. This is an interpretability measure, not evidence of consciousness.

Where possible, report effect sizes, uncertainty, sample counts, and failed probes rather than only a single success rate.

## Main confounds

The following explanations must be tested before making a strong claim:

- the model is merely repeating text stored in memory;
- the prompt contains subtle group cues;
- token sampling produced the difference by chance;
- one experience path is easier, longer, or more emotionally loaded;
- the evaluator's expectations influence scoring;
- the system is optimizing for a visible reward rather than forming a stable preference;
- the apparent history is a post-hoc summary rather than an irreversible record;
- the behavior disappears when memory is compressed, paraphrased, or partially unavailable.

## What would count as an interesting result

An interesting result would be a persistent, replicable, history-linked behavioral difference that survives matched controls, reworded probes, and simpler explanations.

Even then, the conclusion should remain modest:

> The agent developed a measurable history-dependent behavioral pattern under these conditions.

That is not the same as:

> The agent is conscious.

## What would count as a negative result

The experiment is also successful if the differences disappear under controls, if a simple prompt explains them, or if identical agents remain effectively indistinguishable.

Those outcomes would help narrow the question and prevent the project from confusing a persuasive performance with a durable process.

## Data and privacy

Do not include private conversations, credentials, personal identifiers, or sensitive operational data in public logs. Public releases should use synthetic or anonymized records and should explain what was removed or transformed.

The environment must not give agents permission to contact people, spend money, change production systems, or create real-world consequences without explicit human control.

## Pre-registration checklist

Before the formal run, record:

- [ ] model and code versions;
- [ ] group definitions and sample sizes;
- [ ] experience-path construction;
- [ ] probe tasks and scoring rules;
- [ ] primary and secondary metrics;
- [ ] randomization and blinding procedure;
- [ ] exclusion rules;
- [ ] data-retention and privacy rules;
- [ ] the exact boundary between public methods and private implementation.

## Open questions

- How much history is enough before a pattern becomes stable?
- Does irreversible history matter, or is a good summary sufficient?
- Can two agents with different histories converge again?
- Which apparent preferences survive a change in model or environment?
- How should we compare an artificial pattern with human identity without quietly assuming they are the same thing?

These questions are deliberately left open. The experiment is meant to make them sharper, not to answer them in advance.
