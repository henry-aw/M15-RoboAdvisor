# *Module 15 Challenge*
## RoboAdvisor using AWS

**Welcome to my Module 15 Challenge repository. Here, you can check out the RoboAdvisor I created that will recommend an investment portfolio for a retirement plan. Find out more in the follwing sections!**

---

## Background
For this project, I assumed the role of a digital transformation consultant by one of the most prominent retirmeent plan providers in the country. They want to increase their client portfolio - especially by engaging young people. Because machine learning and NLP are disrupting finance to improve the customer experience, I decided to create a robo advisor. Both existing and potentially new cusotmers will be able to use this robo advisor to get investment portfolio recommendation for retirement.

This project consists of three technical deliverables:
- Configuring the intial robo advisor: Defining an Amazon Lex bot with a single intent that establishes a conversation about requirements to suggest an investment portfolio for retirement.
- Building and testing the robo advisor: Making sure that the bot works and accurately responds during conversation with the user.
- Enhancing the robo advisor with an Amazon Lambda function: Creating an Amazon Lambda function that validates the user's inout and returns the investment portfolio recommendaiton. This includes testing the Amazon Lambda function and integrating it with the bot.

This repository contains Python script with the final Lambda function.

---

## Demonstration: The RoboAdvisor in Action
Initial test of the robo advisor:

https://user-images.githubusercontent.com/86025349/136702982-2b6331f0-d9ca-4fc7-9a65-f7a163f190dd.mov

Testing with the integrated Lambda function:

https://user-images.githubusercontent.com/86025349/136702992-8378bd42-78de-4a9d-8404-5afc3f166c2f.mov

---

## Technologies & Usage
This project leverages Python 3.7 and Amazon Web Services (AWS), specifically Amazon Lex and Amazon Lambda, with the following requirements and dependencies:
- import pandas as pd
- from pathlib import Path
- import tensorflow as tf
- from tensorflow.keras.layers import Dense
- from tensorflow.keras.models import Sequential
- from sklearn.model_selection import train_test_split
- from sklearn.preprocessing import StandardScaler,OneHotEncoder
