# Vyouris_Test_assignment

This project implements an autonomous agent using reinforcement learning to navigate in a 2D grid-based virtual environment. The agent learns to reach a goal while avoiding both static and dynamic obstacles using Q-learning.

## 🚀 Objective

- Build a smart agent that:
  - Starts at a given point
  - Avoids static and dynamic obstacles
  - Learns to reach a goal using trial and error (no hardcoded rules)
  - Operates in a visual 2D grid-based environment


Requirements

Install the required libraries:

pip install numpy matplotlib



**How to Run**

Open the notebook in Google Colab / Jupyter / Kaggle.

Run the cells from start to end:

Cells 1-4: Environment, movement logic, obstacle setup

Cell 5: Q-learning training loop with logging

Cell 6: Simulate the agent's path

Cell 7: Draw environment and path

Cell 8: Print final results

Cell 9: (Optional) Visualize training progress with a success-rate dashboard

# ML Technique Used

Reinforcement Learning (Q-learning)

The agent maintains a Q-table: one value per state-action pair.

It learns via trial-and-error using a reward system:

+10 for reaching the goal

-5 for hitting an obstacle or staying in the same place

-0.1 for each move to encourage shortest paths

## 🗺️ Final Path Visualization

<img width="438" alt="Screenshot 2025-04-09 at 1 18 10 PM" src="https://github.com/user-attachments/assets/5c8eaf89-c434-4141-b0e2-b7907eee5f4b" />


<img width="441" alt="Screenshot 2025-04-10 at 8 10 40 AM" src="https://github.com/user-attachments/assets/f4458fe2-bf4f-4355-b96c-7339fb42fabf" />


<img width="801" alt="Screenshot 2025-04-10 at 8 12 48 AM" src="https://github.com/user-attachments/assets/09a0644b-76c6-458f-985b-3e4958f704fb" />



✅ Requirements

Python 3.x

OpenCV

Numpy

OpenCV (cv2)



📉 Features Implemented

✅ Grid-based 2D environment with visualization

✅ Dynamic obstacle updates every 5 steps

✅ Q-learning training with reward shaping

✅ Logging and training performance dashboard (success rate)

✅ Final path simulation and drawing using matplotlib
