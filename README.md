# DeepPRS-BreastCancer  
This repository contains the implementation and results of a study focused on estimating polygenic risk scores (PRS) for breast cancer using computational models. A deep neural network (DNN) demonstrated superior performance compared to traditional statistical and machine learning methods.  

## Key Features  
- **State-of-the-art model**: Utilizes a Deep Neural Network (DNN) for PRS estimation.  
- **High accuracy**: Achieved an AUC of **0.95** on the test set.  
- **Novel insights**: Identifies salient genetic variants missed by association studies, suggesting nonlinear genetic relationships.

## Results  
### Model Performance
- **Final Epoch**:  
  - **Training Error**: 0.275  
  - **Testing Error**: 0.280  
  - **Elapsed Training Time**: 42.71 seconds  

- **Area Under the Curve (AUC)**:  
  - **Test Set**: **0.95**  

### Key Observations  
- **Bimodal PRS Distribution**:  
  - The DNN model separated the case population into distinct genetic risk subpopulations, offering a new approach for precision risk stratification.  

- **Improved Recall at High Precision**:  
  - Achieved **18.8% recall at 90% precision** in a 50% prevalence test cohort.  
  - Extrapolated to **65.4% recall at 20% precision** for a general population with 12% prevalence.  

## Getting Started  
### Prerequisites  
- Python 3.10  
- PyTorch  
- Scikit-learn  

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/RichardDoh/DeepPRS-BreastCancer.git
   cd DeepPRS-BreastCancer
