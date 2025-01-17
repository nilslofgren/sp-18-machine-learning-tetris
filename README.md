<h> sp-18-machine-learning-tetris
</h>

This project will hope to use Machine Learning tactics of deep learning to teach a computer to play the game of Tetris. I chose this project because Machine Learning and its applications fascinate me and I want to learn how to implement these strategies while programming. While achieving human-level performance may not be possible given the time frame of the project, it will serve as a strong introduction of utilizing machine learning.

For this project, I will use Python with its Tensorflow and Keras libraries to create a machine learning network. The Tetris game will also be run from python so that I have access to its game states and variables to feed into the network and help it learn. By the first sprint review, I would like to have the computer being able to make moves in the tetris game and the algorithm to be able to store the game state per frame.

I am building off code created from https://github.com/asrivat1/DeepLearningVideoGames.  I chose to optimize a learning algorithm that is already set up to learn becuase creating the frameowrk would take too long for the timeline of the project.  This learning algorithm is a "general-purpose" algorithm that showed strong results for pong, but fell short for tetris.  I am hoping to build off their code and implement some strategies used from a Stanford research paper,http://cs231n.stanford.edu/reports/2016/pdfs/121_Report.pdf, that helped improve their learning accuracy. 

When I first ran the script, it took over 50,000 timesteps for the algorithm to get 3 lines complete in Tetris, with some changes I've made, I've brought down the number of timesteps to achieve a line as quick as 1,000 timesteps, and 3 lines closer to 20,000 timesteps.  Unfortuntely, this performance varies because the computer is still performing random actions pretty frequently in the earlier timesteps.
