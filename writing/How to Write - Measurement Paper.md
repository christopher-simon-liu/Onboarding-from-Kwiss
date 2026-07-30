# What Makes a Strong Measurement Research Paper?
 
Unlike Tool Papers, Measurement Papers do not have an existing baseline or benchmark to build off of and outperform. A Strong Measurement Paper has a higher burden to prove:
 
1. Does the problem matter?
2. Is the measured phenomenon real?
3. Is the dataset representative?
4. Is the methodology sound and controlled?
6. Do the metrics capture something meaningful?

Remember to write defensively:
- Section 2 is defending realism.
- Section 3 is defending methodology.
- Section 4 is defending measurement validity.


## Recommended order to write sections
Remember to write the paper out of order. I usually do Design, Evaluation/Main Figures, Discussion, Overview, Big Picture Figure, Related Work, Introduction, Conclusion, Abstract
 
## Each section has a rhetorical job
| Section      | Job                                                                                                       | Question   |
| ------------ | --------------------------------------------------------------------------------------------------------- |------------|
| Abstract     | Framework → Dataset → Results → Insight → Impact → Artifact                                               | What did we do, find, and contribute? |
| Introduction | Broad Motivation → Concrete Gap → Question → Measurement Framework → Findings → Contributions → Artifacts | Why does this measurement matter? |
| Overview     | Build domain understanding, demonstrate expertise and passion, justify realism and scope                  | Why is this interesting and realistic? |
| Design       | Explain how the measurement instrument was constructed                                                    | How was it methodically measured? |
| Evaluation   | Answer research questions with evidence                                                                   | What does the evidence show? |
| Discussion   | Generalize findings into broader lessons, implications, and future directions                             | What do the results mean? |
| *Limitations | Define the boundaries of the claims and avoid over-claiming                                               | What should we not conclude? |
| Related Work | Construct the gap and demonstrate why this measurement was still needed                                   | Why was this measurement needed? |
| Conclusion   | Restate the central takeaway and lasting contribution                                                     | What should the reader remember? |

*Limitations is a part of Discussion

Every section in a measurement paper exists to establish trust:
- Introduction: trust the problem.
- Overview: trust the realism.
- Methodology: trust the measurement.
- Evaluation: trust the evidence.
- Discussion: trust the interpretation.
- Related Work: trust the novelty.
- Limitations: trust the boundaries.
- Conclusion: remember the contribution.

## Research Questions
A strong measurement paper is organized around research questions.

Good research questions are:
- measurable
- answerable with the collected data
- broad enough to matter
- specific enough to evaluate

```
How does X affect Y?
How do A and B compare under X?
```

## What Counts as a Measurement Contribution?
Strong measurement contributions often include:
- Taxonomies
- Datasets
- Benchmarks
- Metrics
- Methodologies
- Characterizations
- Empirical findings

A Strong Measurement Paper doesn't just measure stuff but figures out how.

## Abstract
This section is required by conferences, but not important. Write this based on the introduction. Should only be 1 paragraph, at most 2 paragraphs.

Quickly answer the following questions:
- What did you build? 
- What is being measured? 
- What did you find? 
- What is the broader insight? 
- Why does it matter?

## 1 Introduction
This is the most important section of the paper. Often called the "mini paper", this section contains key facts from other sections. It show the reader what they are going to learn from the rest of the paper and why it matters. Write this towards the end.

- Paragraph 1: convince readers why they should care and position the work within a larger field
    * Broad motivation.
    * Why the domain matters.

```
X is important because it enables Y.
Prior work has substantially advanced X.
```

- Paragraph 2: identify a mismatch between assumptions and practice or why previous evaluatins may be incomplete
    * Real-world gap.
    * Why existing evaluations miss something important.

```
Researchers evaluate on X inputs.
Practitioners often use Y inputs.
```

- Paragraph 3: provide a clear objective for the paper
    * Central research question.

```
This raises a central question...
```

- Paragraph 4: explain how you will answer the central question
    * Measurement framework.
    * How the problem will be studied systematically.

```
We propose X for systematically evaluating the Y
...
We evaluate X using a controlled design that holds the A fixed while varying only the B, C, D.
```

- Paragraph 5: give readers the headline findings and tell readers the paper found something interesting 
    * Preview major findings.

```
X go brrr
Y less predictable
```

Unexpected and generalizable? Don't just list numbers.

- Paragraph 6: clarify novelty and separate contributions from implementation details
    * Contributions.

```
We measured 
We formulated
We operationalized
```

```
I built a benchmark :^( 
I built a way to observe a phenomenon :^)
```

- Paragraph 7: highlight the longterm value of this paper
    * Public artifacts and reproducibility.

```
To promote future work, we provide a public release of 
A B C
to support reproducible comparisons of future D.
```

Frame the work as infrastructure for future research


## 2 Overview (Motivation / Background)
This is the second most important section. It is the most flexible in terms of content. It is a unique opportunity for the author to show they are passionate about the field being studied. Why is this subject important and why is it realistic?

```
Before explaining the technical details of X
we first discuss different aspects of Y that make them challenging and interesting.
```

- Background, Taxonomy, Problem Scope
- Motivating example, Limitations of Prior work, Assumptions and Threat Model

In many measurement papers, Section 2 is generic background that readers skim. In a strong paper, the section provides evidence that the measurement target is meaningful.
The introduction motivates the measurement. The overview motivates the subject matter.

## 3 Design (Methodology)

This section argues how we systematically constructed a measurement instrument. This is where you put the Big Picture architecture diagram, workflow, algorithms, etc.

```
X isolates the effects of Y by doing Z
```

No one really cares if you used Python or C or how many lines of code was required. Benchmarks should focus on the benchmark construction process.

Magic numbers are dangerous! Show the math on how you arrived to important numbers (e.g., 500 generated samples)

## 4 Evaluation
This section is where you describe your experiments. Experiments should be driven by research questions. The job of the evaluation is not to report every number. The job is to identify patterns that answer the research question. Imagine using the scientific method:

```
Research Question
↓
Metrics
↓
Controlled Experiment
↓
Figures
↓
Takeaways
```

Read off and highlight the takeways from each figure and table. Paragraphs with numbers!

## 5 Discussion
This section contains sentences that derive from the experimental results which do not contain numbers. Examples include case studies, limitations, and future work. Emphasize trends and patterns and actionable insights. Evaluation reports observations. Discussion extracts meaning. It is not results but again!

```
This suggest X
This appears to show Y
```

Limitations section should not just hand ammunition to an unfavorable reviewer. Add defensive writing on why something is out of scope! Be careful with claiming causation

## 6 Related Work
This section highlights novelty and positions the contributions of the paper. Any work cited should be followed up by a sentence expaining why there is a research gap filled with your paper.

```
Community studies A, B, C. 
Collectively, these works assume D. 
Assumption leaves E unmeasured. 
Our work measures E.
```

## Conclusion
This section is technically required, but mostly useless. Write one short paragraph.
 
```
In this work, we presented X
Our results show Y
providing Z
```

## Other Notes
- For figures, use vector images and make sure the font is at least as big as the paper text.
- Always download the papers you are citing. Claims require the necessary evaluation to back it up or a citation.
- Feel free to steal citations from other papers
- Defensive writing! Be careful of overclaiming. Justify scope decisions.
- Define important terminology explicitly and use terms consistently.
- Some conferences require a dedicated ethics section

