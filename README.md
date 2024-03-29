Hola :wave:

I am Machine Learning Engineer, originally from Mexico :mexico:, based in Seattle, WA. I have a B.S. in Computer Science by Tecnologico de Monterrey, and a M.S. in Computer Science with a Specialization in Machine Learning by Georgia Institute of Technology. I currently work as a Senior Machine Learning Engineer at Amazon.

I'm interested in Artificial Intelligence, especially Reinforcement Learning, and Robotics. I'm particularly interested in how AI can adopt complex social behaviors that adhere to human preferences, and how these agents can be deployed to improve our lives. I envision a world where humans and intelligent agents (embodied, i.e. robots, and non-embodied) cooperate to solve the world's most pressing problems.

## :computer: Projects

### Index

- Generative AI
  - [Lee AI](#lee-ai)
  - [Aguefort](#aguefort)
- Deep Learning
  - [Deep Learning Mini Projects](#deep-learning-mini-projects)
  - [CommaAI Speed Challenge](#commaai-speed-challenge)
  - [Smash GAN](#smash-gan)
- Deep Reinforcement Learning
  - [Implementations of Deep Reinforcement Learning Algorithms](#implementations-of-deep-reinforcement-learning-algorithms)
  - [Solving the Lunar Lander Problem using Deep Reinforcement Learning](#solving-the-lunar-lander-problem-using-deep-reinforcement-learning)
  - [Chimpanzee Theory of Mind Experiment as RL Problem](#chimpanzee-theory-of-mind-experiment-as-rl-problem)
- Reinforcement Learning
  - [Implementations of Reinforcement Learning Algorithms](#implementations-of-reinforcement-learning-algorithms)
  - [Correlated Q-Learning](#correlated-q-learning)
  - [Temporal Difference Learning The TD Algorithm](#temporal-difference-learning-the-td-algorithm)
  - [Trading using Reinforcement Learning](#trading-using-reinforcement-learning)
- Computer Vision
  - [Activity Classification using Motion History Images](#activity-classification-using-motion-history-images)
- Robotics
  - [Warehouse Robot](#warehouse-robot)
- General Machine Learning
  - [Effect of Attribute Noise on Binary Classification Models](#effect-of-attribute-noise-on-binary-classification-models)
  - [Benchmarking Randomized Optimization Algorithms](#benchmarking-randomized-optimization-algorithms)
  - [A Study On Model-Based And Model-Free Reinforcement Learning](#a-study-on-model-based-and-model-free-reinforcement-learning)
  - [A Study On Clustering and Dimensionality Reduction](#a-study-on-clustering-and-dimensionality-reduction)
- Knowledge-based AI
  - [Solving Ravens Progressive Matrices](#solving-ravens-progressive-matrices)

### Lee AI

Lee is an AI-powered cartoon version of my wife Ash that interacts with her and her audience on Twitch and YouTube, acting as a co-host for her streams. The bot is comprised of three main components, all leveraging the latest technologies:

- Speech-to-text: Allows Lee to listen to Ash's voice when she talks to her.
- Text Generation: Allows Lee to respond to Ash's and her audience comments by using a Large Language Model to generate responses.
- Text-to-speech: Allows Lee to talk back to Ash and her audience with her own unique voice.

Lee has captivated audiences during streams, and is even now playing games along with Ash!

This project allowed me to learn more about Generative AI and associated technologies, and how to build a production-grade system around them.

<p align="center">
  <a href="https://www.youtube.com/watch?v=QrNF2mpT-fo"><img src="https://img.youtube.com/vi/QrNF2mpT-fo/0.jpg" /></a>
</p>

![](https://img.shields.io/badge/Generative%20AI-grey)
![](https://img.shields.io/badge/Large%20Language%20Models-grey)
![](https://img.shields.io/badge/GPT%204-grey)

#### Learn More

- [Official Website](https://restashu.red/lee)

### Aguefort

Aguefort is a chatbot that uses the power of LLM's combined with all the knowledge from Dropout's Adventuring Academy episodes (a podcast where the host and his guests talk about all things TTRPG).

With this chatbot I can ask questions about DM'ing, D&D and role-playing in general, and get answers based on everything that has been discussed in the episodes!

The chatbot was built using:

- Gradio for the UI
- LangChain for the backend
- Anthropic's Claude Haiku (via Amazon Bedrock) for the LLM
- Meta's FAISS for the embeddings store

<p align="center">
  <img src="img/aguefort.png" />
</p>

![](https://img.shields.io/badge/Generative%20AI-grey)
![](https://img.shields.io/badge/LangChain-grey)
![](https://img.shields.io/badge/Large%20Language%20Models-grey)
![](https://img.shields.io/badge/Claude%20Haiku-grey)

#### Learn More

- [Code](https://github.com/rey-allan/aguefort)

### Deep Learning Mini Projects

These are mini applications of various Deep Learning algorithms implemented in PyTorch. The inspiration for these applications comes from assignments of Coursera's Deep Learning Specialization that were originally developed using Tensorflow. I decided to re-implement them from scratch using PyTorch to improve my knowledge of the framework. Below is a list of these mini applications:

- Feed Forward
  - Cat vs Non-cat Classification
- Convolutional
  - Hand Sign Recognition Using CNN
  - Hand Sign Recognition Using ResNet
  - Art Generation Using Neural Style Transfer
- Sequence
  - Dinosaur Name Generation Using RNN
  - Jazz Improvisation Using LSTM
  - Emojifier Using LSTM and Word Embeddings
  - Date Translation Using Neural Machine Translation
- Generative
  - Wardrobe Generation Using DCGAN
  - Wardrobe Generation Using VAE

<p align="center">
  <img src="img/deep-learning-mini-projects.gif" width="80%" />
</p>

![](https://img.shields.io/badge/Deep%20Learning-grey)
![](https://img.shields.io/badge/Neural%20Networks-grey)
![](https://img.shields.io/badge/CNN-grey)
![](https://img.shields.io/badge/RNN-grey)
![](https://img.shields.io/badge/GAN-grey)
![](https://img.shields.io/badge/VAE-grey)
![](https://img.shields.io/badge/PyTorch-grey)
![](https://img.shields.io/badge/Jupyter%20Notebook-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- [Code](https://github.com/rey-allan/deep-learning-mini-projects)

### CommaAI Speed Challenge

This is my attempt at solving [comma.ai](https://comma.ai/)'s speed prediction challenge: given an input video from the front-facing camera of a car, can you predict the speed of the vehicle? Using a video with Ground Truth speed measurements, I trained a ResNet-18 model (pre-trained on ImageNet) with features generated by converting the frames of the video into Motion History Images. The model achieved an MSE of ~5.22 on a dev set of frames obtained from a random split of the training video.

<p align="center">
  <img src="img/commaai-speed-challenge.gif" width="50%" />
</p>

![](https://img.shields.io/badge/Deep%20Learning-grey)
![](https://img.shields.io/badge/Neural%20Networks-grey)
![](https://img.shields.io/badge/Computer%20Vision-grey)
![](https://img.shields.io/badge/PyTorch-grey)
![](https://img.shields.io/badge/Jupyter%20Notebook-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- [Code](https://github.com/rey-allan/commaai-speed-challenge)
- [Training video with predictions](https://drive.google.com/file/d/1rFCEzdO_OH_xdq8la1p4WZpbU-bF-uKv/view?usp=sharing)

### Smash GAN

In this project, I implemented Deep Convolutional Generative Adversarial Networks (DCGAN) to generate new characters from the [Super Smash Bros. Ultimate](https://www.smashbros.com/en_US/) Nintendo game. Although the results weren't exactly as I expected, the model was able to learn some of the fundamental elements that form the characters: legs, arms and weapon-like silhouettes, and fighting poses.

<p align="center">
  <img src="img/smash-gan.png" width="80%" />
</p>

![](https://img.shields.io/badge/Deep%20Learning-grey)
![](https://img.shields.io/badge/Neural%20Networks-grey)
![](https://img.shields.io/badge/DCGAN-grey)
![](https://img.shields.io/badge/PyTorch-grey)
![](https://img.shields.io/badge/Jupyter%20Notebook-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- [Code](https://github.com/rey-allan/smash-gan)

### Implementations of Deep Reinforcement Learning Algorithms

These are implementations of different Deep Reinforcement Learning algorithms in PyTorch, as suggested by OpenAI's [Spinning Up in Deep RL](https://spinningup.openai.com/en/latest/index.html). Below is a list of the algorithms implemented:

- Vanilla Policy Gradients
- Deep-Q Networks
- Advantage Actor-Critic
- Proximal Policy Optimization
- Deep Deterministic Policy Gradients

Agents were trained using each algorithm to solve two classic control Gym environments: `CartpPole-v1` and `Pendulum-v0`. The first one was used with all algorithms except DDPG, which was trained against the second environment. The reason is that DDPG can only be used for continuous action spaces.

The following figure shows a trained DQN agent solving the CartPole environment, and a DDPG agent solving the Pendulum one.

<p align="center">
  <img src="img/dqn-CartPole-v1.gif" width="49%" />
  <img src="img/ddpg-Pendulum-v0.gif" width="49%" />
</p>

![](https://img.shields.io/badge/Deep%20Reinforcement%20Learning-grey)
![](https://img.shields.io/badge/PyTorch-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- [Code](https://github.com/rey-allan/deep-rl)

### Solving the Lunar Lander Problem using Deep Reinforcement Learning

In this project, I solved OpenAI's [Lunar Lander](https://gym.openai.com/envs/LunarLander-v2/) gym environment using Deep Reinforcement Learning. I implemented a Deep Q-Network with Experience Replay. The agent was able to maneuver and land the space ship without crashing.

<p align="center">
  <img src="img/lunar-lander.gif" width="50%" />
</p>

![](https://img.shields.io/badge/Georgia%20Tech-grey)
![](https://img.shields.io/badge/Deep%20Reinforcement%20Learning-grey)
![](https://img.shields.io/badge/DQN-grey)
![](https://img.shields.io/badge/Tensorflow%20Keras-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- Code available on request only
- [Paper](https://drive.google.com/file/d/17b1jgs4LEGsztsRN8qJDjRJNhRFh-2wG/view?usp=sharing)
- [Video presentation](https://youtu.be/fX3W_SKnuMM)

### Chimpanzee Theory of Mind Experiment as RL Problem

In this project I recreated the [Theory of Mind experiment](https://www.researchgate.net/publication/48182381_Chimpanzee_Social_Cognition), done on chimpanzees in 2001 by Joseph Call, as an RL environment. And I investigated whether an RL agent could learn to behave like the subordinate chimpanzee in the experiment. The agent was able to learn how to read the movement of the other subject and make optimal decisions.

The following figure shows the agent (blue) acting optimally in the two experiment settings.

<p align="center">
  <img src="img/chimpainzee_demo_barrier.gif" width="49%" />
  <img src="img/chimpainzee_demo_no_barrier.gif" width="49%" />
</p>

![](https://img.shields.io/badge/Deep%20Reinforcement%20Learning-grey)
![](https://img.shields.io/badge/PPO-grey)
![](https://img.shields.io/badge/PyTorch-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- [Code](https://github.com/rey-allan/chimp-ai-nzee)

### Implementations of Reinforcement Learning Algorithms

These are implementations of different Reinforcement Learning algorithms as described in Sutton and Barto's book _Reinforcement Learning: An Introduction, 2nd Edition_. Below is a list of the algorithms implemented:

- Monte Carlo Methods
  - Monte Carlo with Exploring Starts
  - On-policy Monte Carlo
  - Off-policy Monte Carlo with weighted importance sampling
- Temporal Difference Methods
  - On-policy Sarsa
  - Q-learning
- n-Step Bootstrapping Methods
  - On-policy n-step Sarsa
  - Off-policy n-step Sarsa
  - n-step Tree Backup
- Planning Methods
  - Dyna-Q
  - Prioritized Sweeping
  - Monte Carlo Tree Search
- Function Approximation Methods
  - On-policy Gradient Monte Carlo
  - Semi-gradient TD(0)
  - Semi-gradient n-step TD
  - On-policy semi-gradient Sarsa
  - On-policy semi-gradient n-step Sarsa
- Function Approximation with Eligibility Traces Methods
  - Semi-gradient TD(lambda)
  - On-policy semi-gradient Sarsa(lambda)
- Policy Gradient Methods
  - REINFORCE with Baseline
  - One-step Actor-Critic
  - Actor-Critic with Eligibility Traces

The _optimal_ value function was computed by each algorithm against a simplified Blackjack-like game called _Easy21_. The following figure shows these value functions.

<p align="center">
  <img src="img/rl-value-functions.png" width="100%" />
</p>

![](https://img.shields.io/badge/Reinforcement%20Learning-grey)
![](https://img.shields.io/badge/Sutton%20Barto%20Book-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- [Code](https://github.com/rey-allan/rl)

### Correlated Q-Learning

In this project, I implemented three Multi-Agent Reinforcement Learning algorithms, Friend-Q, Foe-Q and Correlated-Q; as well as, the standard Q-Learning algorithm. These algorithms were evaluated against a "soccer" environment modeled as a Markov game. The final results reproduce the original ones obtained by Amy Greenwald and Keith Hall in their paper _Correlated Q-learning_ (2003).

<p align="center">
  <img src="img/correlated-q-learning.png" width="100%" />
</p>

![](https://img.shields.io/badge/Georgia%20Tech-grey)
![](https://img.shields.io/badge/Multi%20Agent%20Reinforcement%20Learning-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- Code available on request only
- [Paper](https://drive.google.com/file/d/1vqF4m2INpg9K7fTf0lv0ZzXBhDc7UouN/view?usp=sharing)
- [Video presentation](https://youtu.be/l-FL23atD0Y)

### Temporal Difference Learning The TD Algorithm

In this project, I reproduced the results presented in Richard S. Sutton's seminal paper _Learning to Predict by the Methods of Temporal Differences_ (1988). I implemented the TD algorithm against a random walk environment to demonstrate how learning can be achieved by updating weights using the gradients of temporal difference errors.

<p align="center">
  <img src="img/td-lambda-1.png" width="49%" />
  <img src="img/td-lambda-2.png" width="49%" />
  <img src="img/td-lambda-3.png" width="49%" />
</p>

![](https://img.shields.io/badge/Georgia%20Tech-grey)
![](https://img.shields.io/badge/Reinforcement%20Learning-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- Code available on request only
- [Paper](https://drive.google.com/file/d/1HzSnN9EW0Vs5nyRo3cJ-OVWGmQ8nG--3/view?usp=sharing)
- [Video presentation](https://youtu.be/v5W11EkdYYk)

### Trading using Reinforcement Learning

In this project, I applied Q-Learning to the problem of trading equities in the stock market. Technical indicators were used for the _states_ with daily return as the _reward_. The agent was allowed to take three _actions_: long, short or cash (i.e. close a position). The Q-Learning agent was able to find an optimal policy that beat both the benchmark and a rule-based hand-crafted strategy.

<p align="center">
  <img src="img/q-learning-trader.png" width="50%" />
</p>

![](https://img.shields.io/badge/Georgia%20Tech-grey)
![](https://img.shields.io/badge/Algorithmic%20Trading-grey)
![](https://img.shields.io/badge/Reinforcement%20Learning-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- Code available on request only

### Activity Classification using Motion History Images

In this project, I implemented an activity classifier using Random Forests to detect between six different human actvities. The input vector was composed of features derived from different Motion History-based techniques. Using the well-known KTH activity dataset, my model was able to achieve a performance of 86.73% on the test set. Using a video of myself performing the activities, my model was also able to classify multiple activities sequentially with satisfying performance.

<p align="center">
  <img src="img/cv-multiactivity-recognition.png" width="100%" />
</p>

![](https://img.shields.io/badge/Georgia%20Tech-grey)
![](https://img.shields.io/badge/Computer%20Vision-grey)
![](https://img.shields.io/badge/Activity%20Recognition-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- Code available on request only
- [Paper](https://drive.google.com/file/d/1LCSmjYWJbmnlwVG5vxGcU2rgveq0ftZ0/view?usp=sharing)
- [Video presentation](https://youtu.be/9SnzixKRMxM)
- [Multi-activity recognition demo](https://drive.google.com/file/d/1EFPlr3IA4fImDwIlV4Hkck2ddsNhGmvM/view?usp=sharing)

### Warehouse Robot

In this project, I developed a robot capable of navigating through a simulated 2D warehouse with the objective of collecting and delivering packages to a specified dropzone. The layout of the warehouse was unknown to the robot. Instead, the robot was provided with an ultrasonic sensor that measured the distance to surfaces (e.g. walls, obstacles and boxes). The "brain" of the robot consisted of two main modules. A localizer and mapper that uses Graph SLAM to reconstruct an estimate layout of the warehouse, and an approximate position of the robot in it. And a planner that uses A Star search to navigate to/from the dropzone once regions were discovered.

<p align="center">
  <img src="img/warehouse-robot.gif" width="80%" />
  <br />
  <strong>Left:</strong> Estimated map and position. <strong>Right:</strong> Actual map and position.
</p>

![](https://img.shields.io/badge/Georgia%20Tech-grey)
![](https://img.shields.io/badge/SLAM-grey)
![](https://img.shields.io/badge/AStar-grey)
![](https://img.shields.io/badge/Robotics-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- Code available on request only

### Solving Ravens Progressive Matrices

In this project, I implemented an agent to solve Raven's Progressive Matrices tests. RPM's are intended to test human intelligence, in particular, logical associations. My agent works in two phases, each leveraging the knowledge-based technique known as Generate & Test. It first attempts to solve the problem visually via affine transformations of the images. Then, it attempts to solve the problem semantically by building Semantic Networks. My agent obtained a final accuracy of ~69% (133 correct answers out of 192 problems).

<p align="center">
  <img src="img/ravens-test-example.png" width="50%" />
  <br />
  Sample problem with a correct answer 1)
</p>

![](https://img.shields.io/badge/Georgia%20Tech-grey)
![](https://img.shields.io/badge/Knowledge%20Based%20AI-grey)
![](https://img.shields.io/badge/Logical%20Reasoning-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- Code available on request only
- [Paper I](https://drive.google.com/file/d/1-il6RI6ULnCQnQxe8j6ng-7hEqOUwylW/view?usp=sharing)
- [Paper II](https://drive.google.com/file/d/1C_EOI6snuywt0p148vu580ELDlXSDiir/view?usp=sharing)
- [Paper III](https://drive.google.com/file/d/1AYkBr5tamdFS1gS4B9UnmYlKaCEIAyjR/view?usp=sharing)

### Effect of Attribute Noise on Binary Classification Models

In this research project, I investigated the effect on the performance of various Supervised Learning algorithms, in particular binary classifiers, when trained with data containing attribute noise. I studied the behavior of the classifiers with varying levels of noise against two different datasets, and compared their performances using different metrics. I also investigated the impact of the dimension of the feature space with respect to the attribute noise based on the contrasting characteristics of the two datasets. The objective was to understand which classifiers perform best in the presence of noise.

<p align="center">
  <img src="img/attribute-noise-research-1.png" width="49%" />
  <img src="img/attribute-noise-research-2.png" width="49%" />
</p>

![](https://img.shields.io/badge/Georgia%20Tech-grey)
![](https://img.shields.io/badge/Research-grey)
![](https://img.shields.io/badge/Supervised%20Learning-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- Code available on request only
- [Paper](https://drive.google.com/file/d/1pj4zJLumNWsVgyn_qQHRLQsdHAUTi3ZX/view?usp=sharing)

### Benchmarking Randomized Optimization Algorithms

In this research project, I investigated the performance of four different Randomized Optimization algorithms: Randomized Hill Climbing, Simulated Annealing, Genetic Algorithms and MIMIC. I studied their behavior under three different types of optimization problems: Continuous Peaks, Knapsack and Traveling Salesman. I compared their performances using several metrics like fitness, runtime, and others. The objective was to understand which algorithms perform best for each of the problems.

<p align="center">
  <img src="img/randomized-optimization-research-3.png" width="49%" />
  <img src="img/randomized-optimization-research-2.png" width="49%" />
  <img src="img/randomized-optimization-research-1.png" width="49%" />
</p>

![](https://img.shields.io/badge/Georgia%20Tech-grey)
![](https://img.shields.io/badge/Research-grey)
![](https://img.shields.io/badge/Randomized%20Optimization-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- Code available on request only
- [Paper](https://drive.google.com/file/d/1HABCbab2jdR2WGh8GlNSzPrP19CvtKWQ/view?usp=sharing)

### A Study On Model-Based And Model-Free Reinforcement Learning

In this research project, I investigated the performance of three of the most common RL algorithms: Value Iteration, Policy Iteration and Q-Learning. I studied their behavior, in terms of rewards obtained and running times, against two environments with different characteristics. A grid world with _frictionless_ floors, and the classic Taxi problem. The objective was to investigate the impact that the dimension of the state, and the complexity of the problem itself have on the performance of the algorithms.

<p align="center">
  <img src="img/reinforcement-learning-research.png" width="100%" />
</p>

![](https://img.shields.io/badge/Georgia%20Tech-grey)
![](https://img.shields.io/badge/Research-grey)
![](https://img.shields.io/badge/Reinforcement%20Learning-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- Code available on request only
- [Paper](https://drive.google.com/file/d/1QwnXFRB4A1IfAhefWq3wwgrDTirL-Bt8/view?usp=sharing)

### A Study On Clustering and Dimensionality Reduction

In this research project, I studied two of the most common clustering algorithms, K-Means and Expectation-Maximization. I also looked at four different dimensionality reduction techniques: Principal Component Analysis, Independent Component Analysis, Randomized Projections and Factor Analysis. I investigated their features by performing four different experiments using two different datasets. The objective was to understand the behavior of each algorithm under various types of problem spaces, and compare and contrast their advantages and disadvantages.

<p align="center">
  <img src="img/dim-reduction-research-1.png" width="49%" />
  <img src="img/dim-reduction-research-2.png" width="49%" />
  <img src="img/dim-reduction-research-3.png" width="49%" />
  <img src="img/dim-reduction-research-4.png" width="49%" />
</p>

![](https://img.shields.io/badge/Georgia%20Tech-grey)
![](https://img.shields.io/badge/Research-grey)
![](https://img.shields.io/badge/Clustering-grey)
![](https://img.shields.io/badge/Dimensionality%20Reduction-grey)
![](https://img.shields.io/badge/Python-grey)

#### Learn More

- Code available on request only
- [Paper](https://drive.google.com/file/d/1_4DWMhRh7AVmUa-oVL3aiRXt1wjWN2nD/view?usp=sharing)

## :toolbox: Languages, Frameworks and Technologies

<p align="center">
  <img width="24%" src="https://www.vectorlogo.zone/logos/python/python-ar21.svg" />
  <img width="24%" src="https://www.vectorlogo.zone/logos/java/java-ar21.svg" />
  <img width="24%" src="https://www.vectorlogo.zone/logos/javascript/javascript-ar21.svg" />
  <img width="24%" src="https://www.vectorlogo.zone/logos/typescriptlang/typescriptlang-ar21.svg" />
  <img width="24%" src="https://www.vectorlogo.zone/logos/pytorch/pytorch-ar21.svg" />
  <img width="24%" src="https://www.vectorlogo.zone/logos/opencv/opencv-ar21.svg" />
  <img width="24%" src="https://www.vectorlogo.zone/logos/reactjs/reactjs-ar21.svg" />
  <img width="24%" src="https://www.vectorlogo.zone/logos/amazon_aws/amazon_aws-ar21.svg" />
  <img width="24%" src="https://www.vectorlogo.zone/logos/apache_spark/apache_spark-ar21.svg" />
</p>

## :mailbox_with_mail: Want to collaborate? Let's get in touch!

<a href="https://drive.google.com/file/d/14c4OfQg08inF8iPIzytW3n-3sIs0HZ6B/view?usp=sharing">
  <img src="https://img.shields.io/badge/resume-%23EC1C24.svg?&style=for-the-badge&logo=adobe-acrobat-reader&logoColor=white" />
</a>

<a href="https://www.linkedin.com/in/reyallan/">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="https://twitter.com/reyallan_">
  <img src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" />
</a>

<a href="mailto:allan.rexo@gmail.com">
  <img src="https://img.shields.io/badge/email-%23C71610.svg?&style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
