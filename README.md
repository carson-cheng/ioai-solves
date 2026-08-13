# IOAI 2026 Unofficial Solutions

My solutions for the IOAI 2026 tasks. Note that these are upsolves -- I didn't achieve such high scores in the actual competition.

Scoring formula:
$$normalized\_score = \frac{score - baseline\_score}{\max(0.9 \times SC\_score,\ top\_contestant\_score) - baseline\_score}$$

where SC_score is the official solution score of the IOAI Scientific Committee.

| Task | Name | Score | Baseline | Top contestant Score | 90% of SC Score | Normalized Score |
|------|------|-------|----------|---------------|-----------------|------------------|
| 1    | Find the Order | 70.9511 | 49.0477[^1] | 71.6573 | 73.1604 | 90.83% |
| 2    | Robot Chasing | 52.0555 | 20.5833 | 57.9444 | 63.9250 | 72.61% |
| 3    | Potato | todo | 17.0800 | 52.5600 | 58.4000 | -- |
| 4    | Double Agent Dilemma | todo | 0.0000 | 97.6427 | 87.2540 | -- |
| 5    | Ghost of Machine | todo | 32.6772 | 93.6104 | 85.0197 | -- |
| 6    | IOAI Field | todo | 32.7571 | 97.7604 | 66.4630 | -- |

[^1]: The baseline posted in the IOAI official GitHub repository uses prefix.json in each split and achieves 69.1459 score. The baseline score here is that of the baseline shown to contestants during the on-site contest, which did not use prefix.json.
