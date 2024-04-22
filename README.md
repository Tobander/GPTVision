# 🔴 What is GPT Vision?

## Problem
Historically, language model systems have been limited by taking in a single input modality, text. However, sometimes when communicating with an LLM, it would be easier to show the model an image instead of text. So to be able to take in images and text and answer questions about it, would greatly expand the areas where a model can be used.

## Solution
The new `GPT-4 Turbo` models are now able to work with text and images as input. So we can start a conversation with text and then provide the model with details in the fomr of an image and continue the conversation. For our example here, we create an app that helps us deciding what we can cook for dinner and takes as input what we would like to cook as well what we already have in our fridge by uploading an image of its contents.

## How To
To be able to work with text as well as images, we can use the same model, but with **different** API calls. Basically we save the image of the user to a specific folder and then pass it to the model in base 64 encoded format. We can also use the previous conversation as input for the API call.

So here are the basic steps visualized:

![CookGPT_ARCHITECTURE](https://github.com/Tobander/MLProject-GPTVision/assets/45336196/472b6770-40b0-4557-b15d-43f4d6269e8e)
