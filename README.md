# <span style="color:red"> PWFCV-TimeSeries
A production-ready LSTM framework validated on stock price forecasting, applicable to sales prediction, demand forecasting, customer traffic, and any sequential business data.
### Rigorous time series forecasting with 5 purged cross-validation methods

## Methodology: 5 Purged CV Methods Compared
### Systematically evaluated 5 walk-forward cross-validation strategies following López de Prado methodology:

    * Sliding Window CV - Fixed window sliding through data (directional accuracy 73.08%)
    * Nested CV - Rolling window with overlap (directional accuracy 80.77%)
    * Expanding Window CV - Growing training window (directional accuracy 69.23%)
    * Monte Carlo Sorted - Random folds, data-dependent splits (directional accuracy 71.15%)
    * Monte Carlo Independent - Random baseline, data-independent splits (directional accuracy 67.31%)

<img width="1625" height="2984" alt="PURGE WF-CV_SMALL_GIT_1" src="https://github.com/user-attachments/assets/b7fc1e84-39f2-4260-87f6-ab775823cb53" />

<img width="1625" height="2984" alt="PURGE WF-CV_SMALL_GIT_2" src="https://github.com/user-attachments/assets/f6a88186-7898-4c0b-a7eb-7e372275af61" />  

### For different forecast horizons: 
5, 20, 45 days

### And randemly selected other parametres:
train_window, number of folds, loss_function ('mse' or custom_directional_losses)

### 70+ technical, statistical, and domain-specific indicators with adaptive selection logic based on forecust horizon

## Methodology Highlights
### Practices Applied:
    * Purged walk-forward CV (López de Prado)
    * Multiple CV strategies tested
    * Zero data leakage 
    * Independent fold scaling
    * Unseen validation approach
    * Returns-based modeling (stationarity)
    * Latin Hypercube Sampling (HP optimization)

### The model is optimized for DIRECTION, not magnitude
### Disclaimer: Educational/research purposes only. 

 ## Acknowledgments:
    * Marcos López de Prado for purged cross-validation methodology
    * TensorFlow team for excellent deep learning framework
    * Scikit-learn for ML utilities and validation tools
    * Financial ML community for rigorous validation standards

## License
This project is licensed under the MIT License - see the LICENSE file for details.

### Contact
Author
Dmitry Kandrykinski

GitHub: @Swimmov
LinkedIn: Your LinkedIn
Email: d.kandrykinski@gmail.com

