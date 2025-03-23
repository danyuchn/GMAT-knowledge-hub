# Understanding GMAT Scoring: Why Similar Answer Patterns Yield Different Scores

![Candidate 1 (V83)](/images/gmat-irt-scoring-explained-1.png)
![Candidate 2 (V77)](/images/gmat-irt-scoring-explained-2.png)

Have you ever wondered why two candidates with similar incorrect answer distributions end up with drastically different GMAT scores? One hits V83 (84th percentile), while the other lands at V77 (31st percentile). Let’s dive into the mechanics behind this.

## The Algorithm: Beyond Simple IRT
The GMAT isn’t your basic IRT single-parameter model—where performance just tweaks the next question’s difficulty (\(b\)). It uses a full-blown **IRT 3-parameter model**, factoring in:
- **Difficulty (\(b\))**: How hard the question is.
- **Discrimination (\(a\))**: How well it separates candidates near that difficulty level.
- **Pseudo-guessing Parameter (\(c\))**: The odds a low-ability candidate guesses correctly.

### Key Insight
Questions with **high \(a\)** (discrimination) and **low \(c\)** (guessing) provide more "information" and weigh heavier in your score calculation. Miss these, and your score takes a hit; nail them, and you’re golden.

## Case Study: Candidate 1 vs. Candidate 2
- **Candidate 1 (V83)**: Likely aced questions with high \(a\) and low \(c\) (e.g., \(V_b = 1.88, 1.76\)). These high-impact items boosted their ability estimate (\(\theta\)), leading to a stronger score.
- **Candidate 2 (V77)**: Might’ve scored on tougher questions (\(V_b = 1.98, 1.94\)), but if those had low \(a\) or high \(c\), they contributed less. Meanwhile, they stumbled on high-\(a\), low-\(c\) items, dragging their \(\theta\) down.

## But How Do You Know \(a\), \(b\), or \(c\)?
You don’t. As test-takers, these parameters are hidden. Guessing "Is this easy question a sign I’m tanking?" is futile—difficulty alone doesn’t tell the full story. The interplay of \(a\) and \(c\) is what really shapes your fate.

## Actionable Strategy
Forget overanalyzing mid-exam. Focus on execution:
- **Time Limits**:
  - Critical Reasoning / Problem Solving / Data Sufficiency: **2 min**
  - Multi-Source Reasoning / Reading Comprehension: **6-8 min**
  - Two-Part Analysis / Graphics Interpretation: **3 min**
- **When Stuck**: Mark, guess, and move on.
- **Pace Yourself**: Stay steady, keep calm, and finish every question—no blanks!

## Conclusion
The GMAT rewards consistency and smart pacing over obsessing about question difficulty. Master your timing, trust the process, and let the algorithm do its thing.
