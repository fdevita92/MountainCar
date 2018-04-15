# MountainCar
Deep Reinforcement learning applied on open AI MountainCar environment

# Training
The script will train the network for 1500 episodes, to train it just type on your command line: python3 dqn_mountaincar.py train. Every 100 episodes the script will save the model weights inside the model directory.

# Testing
To test the system type: python3 dqn_mountaincar.py test (It will use the latest with saved at the 1500th episode)

# Best model
It is possible to run the script after training to verify which is the best model saved (This can take a lot of time). To run it type: python3 dqn_mountaincar.py best, it will test every model for 10 episodes and will return the best one with the highest win count (on average).

# Main Dependencies
1. Tensorflow
2. Keras
3. gym
4. h5py

For any question or suggestion feel free to contact me.
