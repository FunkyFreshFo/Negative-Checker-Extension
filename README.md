
# NEGATIVITY CHECKER

#### Video Demo: <URL HERE>

#### Description

# Table of contents
* [About The Project](#about-the-project)
* [Getting Started](#getting-started)
* [Protoyping Changes](#protoyping-changes)
* [Documentation](#documentation)

# About The Project

In our current timeline where wars and plague outbreaks are happening, we should try not to make the world any more negative. On the internet where things are easier said than taken back, we should ensure that whatever we say are not negative.

**You might be wondering. How can we be less negative with what we say?**

I have created a chrome extensions that measures the negativity level of anything that the user types through the use of Tensorflow models. Even though it might not detect all negativity due to our constantly evolving slang and language.

### Built With

- Node.js
- HTML
- TensorflowJS
- webpack

# Getting Started

Here's how you can add the extension to your own browser

**Prerequisites**
- git (for git clone)
- any browser that supports chrome extensions
- Chrome
- Microsoft Edge
- Brave Browser
- Opera

**Adding extension**


# Protoyping Changes

## Initial Application Idea

Initially, I wanted to create a chrome extension that will block out any negative text on the HTML DOM. I managed to identify all text on a HTML DOM (including lazy loaded and paginated data). However, passing a huge amount of text through a Tensorflow model where predictions take a small amount of time to compute, it slowed down chrome and browsing experience significantly. Therefore, I decided to find another way to implement an application with a similiar idea of measuring negativity.

## Tensorflow Model

From my research, Tensorflow supports using models in Node.js and this is crucial for creating a chrome extension that uses a machine learning model. Therefore, I decided to go with Tensorflow.

Initially I found my own data set, wrote a script for preparing data for training, and wrote and trained my own text classifier model in python.

However, upon converting and using it TensorflowJS, I realized that my model is no where are accurate or as fast as the model developed by Tensorflow. Therefore I decided to go with the TensorflowHub model.

# Documentation

For detailed documentation of each file, [Documentation.md](./documentation.md)
