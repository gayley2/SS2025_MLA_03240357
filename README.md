Name: Gayley Namgay
Student Number: 03240357

#Q.A brief summary of the tasks you completed.
I changed the FrozenLake code to show the action_space and observation_space, as asked in Exercise 1. For Exercise 2, I added a loop to run the code 1000 times. I used a for loop because I knew how many times it should run. I also made a variable called num_episode to keep track of each run. To make the code faster, I removed env.render(), print(), and time.sleep().

1.What type of space is the action space? How many actions are there?
This is a discrete action space with two choices — action 0 moves the cart to the left, while action 1 moves it to the right.

2. What type of space is the observation space? (Box(4,))
The observation space, defined as Box(4), consists of four continuous numerical values that represent the dynamic state of a cart-pole system. These values include the cart's position, which indicates how far the cart has moved from the center of the track, and the cart's velocity, showing how quickly it is traveling either left or right. Additionally, the pole angle reflects how much the pole is tilted away from the vertical axis, while the pole's angular velocity captures the speed at which the pole is rotating or falling. Together, these four parameters provide a comprehensive snapshot of the system's current physical configuration, which is essential for tasks like reinforcement learning and control optimization.

##Q.Run the random agent for one episode. What does the reward seem to represent in this environment? 
reward represent that every time pole is balance reward is equal to 1

#Q.The final average reward you calculated for the random agent in Exercise 2. Ans=>Average reward over 1000 episodes: 0.0100.

#Q.A section on challenges: What was the most difficult part of this practical for you? (e.g., setting up the environment, understanding the step function's return values, structuring the loops). 
The main challenges for me was to structure the loop. I have used for loop as questions already guided us that we have to run the code for 1000 time, so we know the number of episode to run(1000 times).

#A section on key takeaways: What is the most important or surprising thing you learned?
The most surprising thing was that how low the performance of agent is, even after executing the code for 1000 times the total_reward seems to be very low or sometimes zero.