# stacking
Making a Stacking ensemble. Some metrics on test set:
1. Accuracy- 0.9203
2. precision- 0.9201
3. recall- 0.9203
4. f1-score- 0.92009
(Weighted average for all digits in 2., 3., 4.)

# issues (for now)
1. **Saving**: saving paths are made as per my PC, and need to be changed for every other
2. **Logistic regression**: for some reason, logistic regression is better performer than other base estimators (the hyperparams of other base models were not tuned at all), hence votiing classifier (and possibly stacking) does not perform very well.
