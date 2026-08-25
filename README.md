
# manuscript-figures

Reproducible figure-generation notebook for the PINN (Richards equation) slope-stability
manuscript — Device 108, plus cross-site (California) and cross-device (101→107/108)
transfer results.



## How to run

1. open `manuscript_figures.ipynb` in Colab manually.
2. Upload all 14 files listed below on content tab of Colab
3. Run the rest of the notebook top to bottom.

## Contents

| File | What it is |
|---|---|
| `pinn_108_new.csv` | Raw Device-108 telemetry |
| `107_pinn.csv` | Device-107 telemetry |
| `california_hourly_rain.csv` | California rainfall data for cross-site transfer |
| `Obs_Node_6/7/8/31.out` | HYDRUS-1D observation node outputs |
| `piml_slope_model_108_pinn_richards_final.pt` | Trained PINN (Richards) checkpoint, Device 108 |
| `piml_slope_model_108_ml_baseline_final.pt` | ML baseline checkpoint, Device 108 |
| `piml_slope_model_108_lstm_final.pt` | LSTM baseline checkpoint, Device 108 |
| `pinn_model_108_for_california.pt` | PINN checkpoint used for California transfer |
| `D101_se.pt` | RichardsPINN-Se checkpoint, Device 101 |
| `dev101se_to_107_finetuned_chronosplit.pt` | Device 101→107 transfer (fine-tuned) |
| `dev101se_to_108_finetuned_chronosplit.pt` | Device 101→108 transfer (fine-tuned) |
| `manuscript_figures_.ipynb` | Main notebook — generates all manuscript figures/tables |
