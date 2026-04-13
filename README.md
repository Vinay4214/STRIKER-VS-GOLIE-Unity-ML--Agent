# STRIKER-VS-GOLIE-Unity-ML--Agent

This soccer game is a Unity project using the ML-Agents toolkit. It is like a small robot soccer match where the players are controlled by AI instead of a person.

- The game was created from the Unity ML-Agents “Soccer” example.
- Unity makes the 3D world, field, ball, and players.
- ML-Agents teaches the player robots how to play soccer using training.

## What Exactly Happens

- Two teams of AI robots play on a soccer field.
- Each team has strikers and a goalie.
- The ball moves around, and the robots try to score goals.
- When a robot scores, it gets a reward. If it lets the other team score, it gets a penalty.
- Over time, the AI learns to pass, chase the ball, and defend the goal.

## How It Was Created

- The project was copied from the ML-Agents repository example folder for Soccer.
- Unity Editor is used to open the project and run the game.
- The ML-Agents package is used so the robots can learn from actions and rewards.

## Technologies Used

- Unity Editor: makes the game world and runs the game.
- C#: the scripts that move the players and manage the game.
- Unity ML-Agents: the AI system that trains the soccer robots.
- Reinforcement Learning: the AI learns by trying things and getting rewards.

## Setup Instructions

1. Install Unity Hub from `https://unity.com/download`
2. Install a compatible Unity Editor version (Unity 2021.3 LTS or similar)
3. Open Unity Hub and add the soccer-unity-project folder as a project
4. Open the project in Unity Editor
5. Make sure the ML-Agents package is available in the project

## How to Run the Game

1. In Unity Editor, go to `Assets > ML-Agents > Examples > Soccer > Scenes`
2. Open the `SoccerTwos.unity` scene
3. Press the `Play` button at the top of Unity
4. Watch the AI robots play soccer automatically

## Explanation of the Agent Logic

- Each robot is an “agent.”
- Agents see things like:
  - ball position
  - player positions
  - distance to goal
- Agents choose actions like:
  - move forward/back
  - turn left/right
  - kick the ball
- They get rewards:
  - +1 for scoring a goal
  - -1 for letting the opponent score
  - small penalties for bad moves
- The AI uses a learning method called PPO (a type of reinforcement learning)
- After training, the agents get better at playing soccer by practicing again and again

> In simple terms: the game is like teaching robot soccer players by giving them points for good moves and taking points for bad moves.
<img width="533" height="374" alt="image" src="https://github.com/user-attachments/assets/cf2a1de5-2c64-4889-b70d-fcbfef22bbf3" />
