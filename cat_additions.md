# Additional remarks

## Metrics
In the slides we use the macro-average for precision, recall, f1-score, accuracy

These are the scores for match:

**First model**:

| type | precision | recall | f1-score | accuracy |
| --| ----------|--------|----------|----------|
| f_1 | 0 | 0 | 0 | 0.84 |
| m_1 | 0.48 | 0.12 | 0.19 | 0.82 |
| f_2 | 0.28 | 0.76 | 0.41 | 0.66 |
| m_2 | 0.34 | 0.68 | 0.46 | 0.71 |
| f_3 | 0.59 | 0.19 | 0.28 | 0.85 |
| m_3 | 0.56 | 0.12 | 0.20 | 0.83 |

## Weighted classes
The proportion of 4499 (no matches) to all obervations is the weight for the match class -> inverse

## Conclutions
Instead of If you don't like dating => if you like dating, you should use the weighted model, as we suggest a lot of matches but only 1/3 (even less for woman) of them are a real match.<br>
We have a high precision but low recall. This also means you don't miss a lot of real matches.

On the other side if you only want to have some dates and don't care that you don't meet most of the matches, take the third model.

The first model is pretty useless.
