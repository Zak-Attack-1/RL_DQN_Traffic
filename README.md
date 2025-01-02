RL_DQN_Traffic
This project applies Deep Q-Learning (DQN) for optimizing traffic flow at a highway ramp intersection. Using the SUMO simulation environment and reinforcement learning techniques, it dynamically adapts traffic light timings to reduce vehicle wait times and improve overall traffic efficiency.

Features
Custom SUMO Environment: Seamlessly integrates with SUMO via the TraCI protocol.
Reinforcement Learning: Employs a DQN model with experience replay for effective traffic signal control.
Traffic Optimization: Achieved a 30% reduction in average wait times in simulations.
Methodology
Simulation Setup: Created a custom Gym environment (SumoRampEnv) for traffic modeling in SUMO.
State Representation: Focused on vehicle counts on the ramp and highway.
Action Space: Controlled traffic light states:
Green for highway
Green for ramp
Both green (if safe)
Reward Mechanism: Minimized vehicle wait times through a negative reward system.
Results
Significant improvements in traffic flow.
Demonstrated scalability for more complex intersections.
Future Directions
Scaling to multiple intersections.
Integrating real-world traffic data for better realism.
Exploring advanced RL algorithms like Double DQN and PPO.
Leveraging IoT for real-time data and decision-making.
Setup and Installation
Clone the repository:
bash
Copy code
git clone https://github.com/Zak-Attack-1/RL_DQN_Traffic.git
Install required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the SUMO simulation and RL model:
bash
Copy code
python main.py
Contributing
Feel free to fork this repository, submit issues, or create pull requests. Contributions are welcome!

License
This project is licensed under the MIT License. See the LICENSE file for details
