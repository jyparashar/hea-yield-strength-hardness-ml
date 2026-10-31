# Draft figure captions

**Figure 1** (Main). Predicted vs. measured room-temperature yield strength (random forest) under random, composition-grouped and system-grouped 5-fold cross-validation. The same model appears far less accurate when test alloys (or alloy families) are excluded from training.

**Figure 2** (Main). Grouped cross-validation R² (mean ± std over 5 seeds) for the five ways of using hardness data, for unseen alloys (blue) and unseen alloy families (orange). Left: alloys with a measured hardness; right: all alloys.

**Figure 3** (Main). Parity plots for unseen alloy families: baseline (M0) vs. training with hardness-derived pseudo-strengths when hardness of the new alloys is available (M4).

**Figure 4** (Main). Calibration curves of the bootstrap-ensemble uncertainty (M4) before and after group-aware recalibration.

**Figure 5** (Main). Confidence curve for unseen alloy families: MAE of the remaining predictions as the least-confident predictions are removed, compared with random and ideal (error-ordered) removal.

**Figure 6** (Main). SHAP dependence of predicted yield strength on VEC, atomic size mismatch δ, mean melting point and mixing entropy for models trained without (M0) and with (M4) hardness data.

**Figure S1** (Supplement). Number of measurements per distinct alloy composition in the cleaned room-temperature dataset.

**Figure S2** (Supplement). Measured yield strength vs. Tabor estimate (HV × 9.807 / 3) for alloys with both measurements.

**Figure S3** (Supplement). Random-forest feature importances of the baseline model.

**Figure S4** (Supplement). Global SHAP importance (mean |SHAP|, ± std over 5 bootstrap refits) for M0 and M4.

**Figure S5** (Supplement). SHAP beeswarm plot of the physics descriptors for M4.

**Figure S6** (Supplement). SHAP explanation of the M4 prediction for HfNbTaTiZr: contribution of each descriptor to the predicted yield strength.
