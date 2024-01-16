# NEAT-Loan-Approval-Prediction

Welcome to the NEAT Loan Approval Prediction project! This repository demonstrates the use of NeuroEvolution of Augmenting Topologies (NEAT) to predict loan approval using a classic loan classification dataset. NEAT is a genetic algorithm for evolving artificial neural networks.



## About NEAT

NEAT (NeuroEvolution of Augmenting Topologies) is a powerful neuroevolution technique used to evolve artificial neural networks. It enables the automatic generation and evolution of neural network architectures, making it particularly well-suited for complex tasks like loan approval prediction.


## Usage

Follow these steps to run the NEAT-based loan approval prediction:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/neat-loan-approval.git
   cd neat-loan-approval
   ```

2. Install the required Python dependencies:

   ```bash
   pip install neat-python pandas numpy
   ```


4. Configure NEAT: Customize the NEAT configuration in `neat_config.txt` according to your dataset and problem requirements.



## NEAT Configuration

The NEAT configuration can be fine-tuned in the `neat_config.txt` file. Adjust the parameters to optimize the evolution process for your specific loan approval prediction task.

## Making Predictions

To make a loan approval prediction using the trained model, you can use the following code snippet:

```python

# Define input features for prediction
marital_status_encoded = 1.0  # For example, 'Married'
previous_loan_encoded = 0.0   # For example, 'No'
annual_income = 10000         # Example income

# Make a prediction
# Predicted Loan Approval Probability: 0.04027875121489312
```

## Contributing

Contributions to this project are welcome! If you have ideas for improvements, want to enhance the NEAT implementation, or suggest new features, please follow the contribution guidelines in the repository.

