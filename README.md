# Optimizing-Buckets-Default-Rates-by-FICO-Bucketing
Project: Optimized FICO score bucketing using MSE (uniform ranges) and log-likelihood (risk-based). Log-likelihood better separates default rates (0.06-0.69) for predictive modeling. Generated 1-5 rating maps. Best for credit risk analysis.


### **Project Description: FICO Score Bucket Optimization**  

This project focuses on **optimally segmenting FICO credit scores into buckets** to predict borrower default risk. Two quantization methods were compared:  
1. **Mean Squared Error (MSE)**: Minimizes approximation error, creating evenly distributed buckets.  
2. **Log-Likelihood Maximization**: Prioritizes separating borrowers by default probability, yielding sharper risk differentiation.  

**Key Steps & Results**:  
- Generated **rating maps** (1=best, 5=worst) for both methods.  
- Log-likelihood buckets showed **wider default rate ranges** (0.06–0.69 vs. MSE’s 0.04–0.54), proving better for risk modeling.  
- Demonstrated practical mappings (e.g., FICO 450 → Rating 5, FICO 720 → Rating 1).  

**Outcome**: The log-likelihood approach is recommended for **default prediction models**, while MSE suits general-purpose bucketing.
