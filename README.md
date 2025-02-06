# AnimatAI
A collection of tamagotchi characters to give AI assistants an identity.
![f0c76321ac1839d25f97248cda6d6c9](https://github.com/user-attachments/assets/bfe9edea-8e59-45d0-af6b-f4c2356def48)

# Tamagotchi

This project is inspired by the classic Tamagotchi device, featuring a virtual character drawn with JavaScript. The character can be controlled through various buttons, or it can dynamically change based on interactions with an AI assistant.


## How to Use:

1. **Manual Mode**: Click on the buttons to perform actions.
2. **AI-Controlled Mode**: Connect this with an AI assistant to automatically update the character.


Feel free to customize the project, or expand it for AI assistant interaction.

## AI Characters:

### Eyes
<img src="images/device1_eyes.png" width="400px" />


### Notion
<img src="images/device2_notion.png" width="400px" />


### Cat
<img src="images/device1_cat.png" width="400px" />

## Plant
<img src="images/device2_plant.png" width="400px" />

## How to Connect to Chatbot:

Call `setAction` based on the AI model’s status or reactions. For example:

- `setAction('curious')` if the AI’s response includes a question.
- `setAction('excited')` if the response shows excitement.
- `setAction('speaking')` for general replies.

Check the [demo](https://animat.fun/) for more action details.
