# Bayesian-Geot
Bayesian updating for the undrained shear strength of clay soil

Bayesian Updating for Observational Method in Geotechnical Engineering

This repository contains Python code demonstrating the application of Bayesian updating within the observational method for geotechnical engineering. The project focuses on updating the undrained shear strength (Su) of clay soil using simulated Cone Penetration Test (CPT) data during a pile foundation project.

Project Overview
The observational method in geotechnical engineering allows for adaptive design adjustments based on monitoring during construction. This project enhances this approach by using Bayesian updating to probabilistically incorporate new data and refine estimates of soil parameters.

The example scenario simulates updating the undrained shear strength (Su) of clay soil. A prior distribution for Su is established based on initial site investigation, and this distribution is sequentially updated using simulated CPT measurements obtained during pile installation.

Key Features
Prior Distribution Definition: Defines the initial probabilistic understanding of the soil parameter (Su).
Simulated Observational Data: Generates realistic-looking sequential data (CPT measurements) with simulated noise.
Bayesian Updating Implementation: Applies Bayesian principles to update the posterior distribution of Su after each new observation.
Failure Risk Assessment: Calculates the probability of failure based on the updated posterior distribution and a defined failure threshold.
Risk-Based Adjustments: Provides suggestions for project adjustments if the calculated failure risk exceeds a specified threshold.
Result Visualization: Visualizes the evolution of the probability distribution and the probability of failure over time.
Methodology
The project utilizes a normal-normal Bayesian model for updating the mean and standard deviation of the undrained shear strength (Su) as sequential CPT measurements become available. The probability of failure is computed using the cumulative distribution function (CDF) of the final posterior distribution.

Contents
Jupyter Notebook with the complete code and analysis.
(Potentially) Data files used for simulation (if applicable).
Getting Started
To run the code, you will need Python and the following libraries:

numpy
scipy
matplotlib
Clone this repository and run the provided Jupyter Notebook.

Findings
The analysis demonstrates how Bayesian updating can effectively refine the estimate of Su as more data is collected. In the simulated scenario, the updated posterior distribution and the calculated probability of failure provide valuable insights for risk assessment and decision-making in the pile foundation project. The results highlight the importance of incorporating observational data into the design process to manage uncertainties and mitigate risks.

Conclusion
This project serves as a practical example of applying Bayesian updating to the observational method in geotechnical engineering. By providing a probabilistic framework for incorporating new data, it contributes to more informed and adaptive decision-making in construction projects, ultimately leading to improved safety and efficiency.
