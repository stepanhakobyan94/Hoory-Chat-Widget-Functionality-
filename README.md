# Cypress Test for Chat Widget Functionality

This repository contains a Cypress test for the chat widget functionality on the website `https://uat.hoory.ai/hoory`.

## Test Description

The test checks the following functionalities of the chat widget:

1. Clicking on the widget icon opens the widget.
2. Clicking on the "Start Conversation" button starts a new conversation and the chat input appears.
3. The test sends a message and checks if the message appears in the chat.
4. The test goes back to the conversation list and checks if the conversation appears in the list.
5. The test starts a new conversation, sends a second message, and checks if the second message appears in the chat.
6. The test goes back to the conversation list and checks if both conversations appear in the list.

## Setup

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install the necessary dependencies with `npm install`.

## Running the Test

To run the test, use the following command:

```bash
npx cypress open
