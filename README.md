# machine_learning

Notebook file names: 1) __credit_risk_ensemble.ipynb__, 2) __credit_risk_resampling.ipynb__

# Ensemble Learners

## Balance Accuracy
Although the Random Forest resulted in marginally less accuracy score (0.92) vs ADABoost (0.94), the balanced accuracy of the Random Forest method is significantly lower at 0.81 vs ADABoost at 0.92. 

## Recall 
The weighted average recall comparing the two methods are also very similar with ADABoost being slightly better at 0.94 compared to Random Forest at 0.92.

## Precision 
The weighted average precision comparing the two methods are exactly the same with ADABoost and  Random Forest at 0.99. Macro average scores are very close 0.54 for ADABoost and 0.52 for Random Forest.

## Recommendation for Ensemble Methods

Of the two methods used in ensemble learning models ADABoost appears to be the slightly more accurate model based on the balanced accuracy scores, recall and precision. Therefore, ADABoost is recommended to be used to predict credit risk.

# Resampling Techniques

## Precision
    
All methods resulted in the same precision at 0.99

## Recall

Recall resulted in best scores for SMOTE Oversampling at 0.7, with Naive Oversampling at 0.66, Combination 0.55. Undersampling has the lowest score at 0.43.

## Balanced Accuracy

Naive Oversampling - 0.65

SMOTE Oversampling - 0.62

Undersampling - 0.52

Combination - o.61

## Recommendation for Resampling Techniques
The scores above indicates balanced accuracy for Naive Oversampling as the highest among the methods used. It also resulted in the best recall scores. In this instance, Naive Oversampling should be used to best predict credit risk.

# Resampling Methods vs Ensemble Methods Recommendation

Comparing the resampling methods vs ensemble methods, in this analysis, the ensemble methods appears to be providing better accuracy as compared to resampling methods. Therefore, __ensemble methods should definitely be considered__.


