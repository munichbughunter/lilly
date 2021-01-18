# Lilly

## Autonomous exploratory Testing with Machine Learning

### Idea

Lilly, autonomously learns to explore a web application and apply test flows as testable patterns are recognized. 
This means evaluating its actions, fields, and forms.

The Lilly agent is capable of independently interacting with the System Under Test via an instrumented Chrome client 
based on Playwright. This AI for Software Testing solution, designed for research and development applications, 
illuminates a new path for advancing the state-of-the-art in testing automation.

### What do we need?

First Brainstorming: 

* A web runner - We try to use Playwright
* A CNN to identify the objects of a website
    * Build up the neural net with Tensorflow and Keras
    * Train the network 
    * Test the network
* Think about how we can map the objects from the network back to interact with playwright?
* Implement reinforcement agent to learn exploring the pages
    * Think about possible rewarding mechanism 
    * How can we know that we do the right - when do we reward?
    
    