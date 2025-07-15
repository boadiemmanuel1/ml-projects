# VMD + LSTM: Hybrid Model for Bitcoin Price Forecasting

This project presents a hybrid approach that combines **Variational Mode Decomposition (VMD)** with **Long Short-Term Memory (LSTM)** neural networks to improve the accuracy of Bitcoin price prediction. The raw price series is decomposed into multiple intrinsic mode functions (IMFs), which are then individually modeled using LSTM and aggregated for final forecasting.

 **Research Preprint:**  
[View Full Paper on ResearchGate](http://dx.doi.org/10.13140/RG.2.2.14871.69280)

**Highlights**
- VMD decomposition of time series into IMFs
- LSTM modeling for each IMF component
- Comparison with standard LSTM model
- Evaluation using RMSE, MAE, and R²

**Tools Used**:  
Python, PyTorch, VMD-Py, Matplotlib, NumPy

 **Date**: July 2025  
 **Status**: Preprint available on ResearchGate
