# Machine-Learning-Python-Project: Well Game

This project collected and processed data from a well drilling simulation API for a previous hackathon. The goal is to log well conditions across multiple turns and failure scenarios to generate a dataset for potential use in machine learning models for predicting well performance and failure outcomes.

The notebook uses Python to automate interactions with a backend API, running over 150 turns of simulated drilling. It checks for system failures and responds by either drilling further or triggering repairs, depending on the state of the well. For each turn, the system logs a comprehensive set of well parameters and operational metrics.

The data collection focuses on key variables such as bit temperature, mud circulation, casing integrity, permeability, porosity, rotary speed and torque, depth, and pressure. Each record also includes contextual information like the failure status, score, session ID, team ID, and turn number. This information is stored in a CSV file (data_well.csv) that can be used for further analysis, visualization, or as training data for predictive modeling.
