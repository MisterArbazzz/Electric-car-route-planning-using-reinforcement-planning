# Electric-car-route-planning-using-reinforcement-planning

The goal of this study is to generate a better route for the car under certain conditions (minimise energy usage) while taking battery, motor, traffic time, and other factors into consideration.

# Instructions for usage
Take a moment to download the following Python files: main.py, Environment.py, DoubleDQN.py, battery.py, and motor.py.

1. In main.py, enter your starting location using the name or geocode (lat, lng)
2. Enter the name of the position or the geocode for your destination in main.py (lat, lng)
3. Enter the step length in main.py as each step's length. line 78, which is higher but less precise (ex: 1000m takes less time to train compare to 100m) in main.py, type the number of episodes you wish to train.
4. Main.py has to have several file and folder path names updated to meet your situation.
5. During the training process, make sure you have access to the internet and Google Maps.
