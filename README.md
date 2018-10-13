# How to design AI for your video games using Deep Reinforcement Learning

Using this repo as a tutorial series for new game developers such as myself that want to easily add AI to their games. I like strategy games like Starcraft and Civ so I'll be working my way up to show how to design AI for real time and turn based strategy games. However, before we get there, we have to start off with simpler games and make sure we understand the basics

It's important to note that all you need to build game AI is encode what are the actions your agent can take and a snapshot of the state of the game at any point in time (e.g: health bars, number of resources left etc..)

## What you will learn
1. Setting up Tensorflow and Open AI gym on a docker container
2. Go over Q learning and how it can work for small games
3. Upgrade to deep Q learning for larger games
4. Making the appropriate changes to your game to make hooking up AI really easy using UnityML agents

## Setting up
I used a docker image to get setup quickly, I'd recommend you do the same unless you wanna spend your whole weekend installing stuff. https://hub.docker.com/r/eboraas/tensorflow/

## Q learning and deep Q learning
1. [Q learning](FrozenLakeQLearning.ipynb)
2. [Deep Q learning](FrozenLakeDeepQLearning.ipynb)
