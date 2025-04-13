# 🔋 Hybrid Battery Degradation Estimation Algorithm

**Estimation & Characterisation of Battery Degradation Using Equivalent Circuit Modelling for Li-ion Cylindrical Cell**

A hybrid approach combining Machine Learning (Random Forest, Gradient Boosting, Neural Network), Kalman Filtering, and Genetic Algorithm optimization to accurately predict battery health (SOH) and degradation patterns in Li-ion cylindrical cells.

This project aims to outperform conventional methods in accuracy, efficiency, and reliability, providing a robust solution for battery health monitoring and lifetime estimation.

---

## 📊 Project Highlights

- ✅ Multi-model ML predictions: RF, GBM, and Neural Network
- ✅ Kalman Filter for prediction smoothing
- ✅ Genetic Algorithm for optimal parameter tuning (Q, R, P0)
- ✅ Comparative latency analysis (Training + Optimization time)
- ✅ Full evaluation metrics: RMSE, R², Latency
- ✅ Professional visualization of performance metrics
- ✅ Complete final report and IEEE-format research paper

---

## 🚀 Summary of Results

| Model                          | RMSE   | R² Score | Total Latency (sec) |
|--------------------------------|--------|----------|--------------------|
| Random Forest                  | *X.XX* | *0.XXX*  | *XXX.X*            |
| Gradient Boosting              | *X.XX* | *0.XXX*  | *XXX.X*            |
| Neural Network                 | *X.XX* | *0.XXX*  | *XXX.X*            |
| Hybrid Kalman + GA Optimized   | **✔ Lowest** | **✔ Highest** | *XXX.X*            |

> ✅ *Hybrid Kalman + GA Optimized model outperforms all individual ML models.*

---

## 📂 Project Structure

Battery_Degradation_Estimation/
│
├── data/
│   ├── B0005_Kalman_GA_Optimized.csv
│   ├── B0005_ML_predictions.csv
│   ├── B0005_Kalman_smoothed.csv
│   └── B0005_Hybrid_Kalman_Output.csv
│
├── scripts/
│   ├── all_graphs_generation.py
│   └── summary_table_generation.py
│
├── results/
│   ├── Final_Summary_Table.csv
│   └── Latency_Summary.csv
│
├── report/
│   ├── Final_Report.docx
│   └── IEEE_Paper.tex
│
├── README.md
└── LICENSE

---

## 📊 Visualizations

- ✅ **SOH vs. Cycles Comparison**
- ✅ **Error Metrics: RMSE & R²**
- ✅ **Residual Distribution**
- ✅ **Prediction vs Actual Scatter Plot**
- ✅ **GA Convergence Curve**
- ✅ **Latency Comparison (Training + Optimization Time)**
- ✅ **Feature Importance**

*Sample visualizations:*

<p align="center">
  <img src="results/soh_vs_cycles.png" alt="SOH vs Cycles" width="500"/>
  <img src="results/ga_convergence.png" alt="GA Convergence" width="500"/>
</p>

---

🔍 Future Scope

    Real-time battery health monitoring integration

    Deployment on embedded systems for EVs

    Expansion to different chemistries (LFP, NMC, etc.)

    Incorporation of temperature effects and aging models
