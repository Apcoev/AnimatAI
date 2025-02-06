# AnimatAI
A collection of tamagotchi characters to give AI assistants an identity.
![af25b55d4fb1fabe1d368cea99084be](https://github.com/user-attachments/assets/6ae2f043-ff9a-4870-a201-c2551d8c3513)


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

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

Check the [demo](https://animat.fun/) for more action details.
