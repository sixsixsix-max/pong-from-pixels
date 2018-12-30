### Introduction

This repo trains a Deep Reinforcement Learning Neural Network, so that's its able to play Pong from the pixels.

It is largely based on this Gist: https://gist.github.com/karpathy/a4166c7fe253700972fcbc77e4ea32c5, which
in turn is based on this paper: https://arxiv.org/abs/1312.5602

It uses the Open AI Gym environments in order to run the Atari emulator
and environments:
https://github.com/openai/gym

### Modifcations vs Source Gist
* Records output video of the play
* Boosted learning rate from 1e-4 to 1e-3
* Comments for clarity - which is pretty messy atm

### Requirements
The instructions below are for Mac OS & assume you have Homebrew installed.

* You'll need to run the code with Python 2.7
* Install Open AI Gym `brew install gym`
* Install Cmake `brew install cmake`
* Instal ffmpeg `brew install ffmpeg` - Required for monitoring / videos
