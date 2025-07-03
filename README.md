# Ecommerce_order_status_classification
"A machine learning project to classify e-commerce order statuses (Completed, Cancelled, Returned, In Process) using customer and product behavior features."
## Features Used
- `Total`
- `Sales`
- `SessionDuration`
- `DeliveryRating`
- `ProductRating`

---

## Models Trained
- Logistic Regression
- Random Forest ✅ *(Best performer)*
- Decision Tree
- Support Vector Machine (SVM)

**Evaluation:**
- Models were evaluated using **Stratified K-Fold Cross-Validation**
- Metrics: `Accuracy`, `F1-score`, and per-class classification report

---

## Best Model Summary
**Random Forest Classifier**
- Accuracy: ~77%
- Macro F1 Score: ~0.48
- Consistently performs best across all classes including `Cancelled` and `Returned`

Saved using `joblib`:
- `models/final_rf_model.pkl`
