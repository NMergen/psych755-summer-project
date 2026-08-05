# Contributions

**Group:** [psych755-summer]

**Group Members:** [Brenna Pratt, Sasha Sweat, Nick Mergendahl]

**Project:** []

**Repository:** [https://github.com/bepratt/psych755-summer-project.git]

---

## How to use this file

Each member of the group completes one section below. Fill in every bullet. Delete the
instructions in *italics* as you go, and delete any unused student sections at the bottom
if your group has fewer than five members.

Three rules:

1. **Components are not co-owned.** No two students may not claim the same component. If you and a partner pair-programmed something, decide who owned it and ackowledge the two person effort. Each person needs their own entry below.
2. **Everything here must be checkable.** We will follow your file paths and click your links. A claim we cannot verify does not count.
3. **Link to permanent URLs, not moving ones.** See the note on line numbers below.

> **Reminder — Markdown link syntax.** Write links as `[link text](https://example.com)`. The visible words go in the square brackets and the URL goes in the parentheses, with no space between the two. For example, `[Permalink to load.py](https://github.com/...)` renders as [Permalink to load.py](https://github.com/...). Bare URLs work too, but named links are easier to read.

### A note on line numbers and links

Line numbers go stale the moment someone edits the file above yours. So do links to a branch. Use GitHub **permalinks**, which pin to a specific commit and never move:

> Open the file on GitHub → click the line number (or drag to select a range) → press **`y`** to convert the URL to a permalink → copy.

A permalink looks like this. Note the 40-character commit SHA in the path:

```
https://github.com/ORG/REPO/blob/a3f2c1e9d4b7.../analysis/model.qmd#L112-L168
```

Not like this (this one rots):

```
https://github.com/ORG/REPO/blob/main/analysis/model.qmd#L112-L168
```

### The data science process

The last bullet in each section asks which portion of the data science process your work contributes to. Name the stage and be specific about your part in it ("data acquisitionand ingestion," "cleaning and validation," "exploratory analysis," "modeling," "evaluation," "visualization and communication," "infrastructure and reproducibility.") If your component spans two stages, say so, and say which one it mostly lives in.

---

## Example (delete this section before submitting)

### Jane Doe (`jdoe-wisc`)

- **The component I "owned" and that I summarize here is best described as** the modeling and training or fit step — the KNN classifier that takes the cleaned feature matrix and predicts the target class, together with the grid search that chose the value of *K*.
- **You can find this contribution in a file called** `src/models/knn.py` **at lines** 1–98, and in `manuscript.qmd` at lines 112–168 where the model is described and the grid-search results table is generated. [Permalink to `knn.py`](https://github.com/ORG/REPO/blob/a3f2c1e.../src/models/knn.py#L1-L98)
- **Owning this component means** I chose KNN over the two other classifiers we considered (write-up in PR #21); I designed the *K*-grid (odd values from 3 to 51) and the 5-fold stratified cross-validation used to score each candidate; I wrote the fit-and-predict loop; and I debugged the scaling bug that was letting one high-variance feature dominate the distance metric. I did not build the feature matrix — Marcus did the wrangling, and he covers that in his section.
- **The commits or PRs that are most relevant are** [#21 — model selection write-up](https://github.com/ORG/REPO/pull/21), [#24 — KNN + grid search over *K*](https://github.com/ORG/REPO/pull/24), and [a3f2c1e — scale features before distance calc](https://github.com/ORG/REPO/commit/a3f2c1e).
- **The portion(s) of the [data science process](https://adamrossnelson.github.io/integsci375-public/readings/data_science_processes.html) that this effort contributes to is** stage 5, **Select + Apply** — reviewing candidate techniques, selecting KNN, and applying it with a grid search over *K* to produce the predictive model the manuscript reports on. It also has a foot in stage 6, **Check + Recheck**: the 5-fold cross-validation inside the grid search is where each candidate *K* is validated against held-out folds before the final *K* is chosen.

---

## Student 1: [Brenna Pratt] (`bepratt`)

- **The component I "owned" and that I summarize here is best described as** *[regression analysis and the literature review.]*
- **You can find this contribution in a file called** `manuscript.qmd` **at lines** XX–YY and file `references.bib`. *[***manuscript link*** and https://github.com/bepratt/psych755-summer-project/blob/49f319248bb7b0e0504d746b839aa989181ac670/references.bib ]*
- **Owning this component meannt** *[that I needed to decide how to handle the data, including deciding how to code the communication apprehension score, and what type of analysis to run in order to determine if group communication apprehension correlates with public transportation usage and how that factors into our larger research question. This required that I double check all communication-related questions were included in the composite score and that appropriate questions were reverse coded if necessary.]*
- **The commits or PRs that are most relevant are** *[Two to four actual links. Not SHAs typed out as text — links we can click.]*
- **The portion of the data science process that this effort contributes to is** *[Select + Apply. Say why your part of it mattered to the project's findings.]*

---

## Student 2: [Sasha Sweat] (`sweat2-create`)

- **The component I "owned" and that I summarize here is best described as**
- **You can find this contribution in a file called** `filename.qmd` **at lines** XX–YY.
- **Owning this component means**
- **The commits or PRs that are most relevant are**
- **The portion of the data science process that this effort contributes to is**

---

## Student 3: [Nick Mergendahl] (`NMergen`)

- **The component I "owned" and that I summarize here is best described as** The research memo documenting the effect of the number of days a person used public transportation per month on average on their composite communication apprehension scores.
- **You can find this contribution in a file called** `research_memo_c.qmd` **at lines** https://github.com/bepratt/psych755-summer-project/blob/402d5d5c20b5c6af130e9000dadc195af2ed815a/Memos/Nick/research_memo_c.qmd .
- **Owning this component means** writing the code for the document, interpreting the results of the code, and designing the graphs shown in the associated documents. 
- **The commits or PRs that are most relevant are** https://github.com/bepratt/psych755-summer-project/commit/90ed356f033b2c69929fbc01ca4e9b9883dace60, https://github.com/bepratt/psych755-summer-project/commit/00abb7496c45e72a9017e8e1059e5510d29679db, and https://github.com/bepratt/psych755-summer-project/commit/13ae5bd5085df4c0aad82f64ec126f454b47313a. 
- **The portion of the data science process that this effort contributes to is** Select + Apply -- Applying an ANOVA analysis of composite communication apprehension scores to individuals grouped by responses to how many days in the last month on average have they used public transportation.

---

## Group sign-off

By adding your name below, each member affirms that the account of their own contribution is accurate, and that they have read the other four sections and believe them to be accurate as well.

- [ ] [Brenna Pratt] (`bepratt`) — [date]
- [ ] [Sasha Sweat] (`sweat2-create`) — [date]
- [ ] [Nick Mergendahl] (`NMergen`) — [8-5-2026]
