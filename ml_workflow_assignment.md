Task 1
Identify which column in the dataset is the label, and which column, if included as a feature, would introduce data leakage. For each, write one sentence justifying your choice.

The column repeat_purchase_flag is the label in the dataset, as it indicates whether a customer makes a repeat purchase within 30 days, which isthe outcome the model is intended to predict
If discount_used_on_repeat_order is used as a feature, would introduce data lekage,because it is only known after the repeat purchase has occured and thus contains future information and not available at prediction time

Task 2
Your manager skips straight to training a gradient boosting model. Suggest two steps from the complete ML workflow that should have been completed first, and briefly explain why each step matters before jumping to a complex model.

* Data auditing and pre-processing:
      This step ensures the dataset is clean , free from missing or inconsistent values, and
    does not contain data leakage which is critical for building a reliable model
* Establishing a baseline model:
      A simple baseline model provides a reference point to evaluate whether the complex 
    model offers any meaningful improvement in performance
    
