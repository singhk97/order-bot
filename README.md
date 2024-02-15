# Food Ordering Assistant

This example shows how to create a conversational assistant that uses tools to call actions in your bots code. It's a food ordering assistant for a fictional restaurant called The Pub and is capable of complex interactions with the user as it takes their order.

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Food Ordering Assistant](#food-ordering-assistant)
  - [Interacting with the bot](#interacting-with-the-bot)
  - [Setting up the sample](#setting-up-the-sample)
  - [Testing the sample](#testing-the-sample)
    - [Using Teams Toolkit for Visual Studio Code](#using-teams-toolkit-for-visual-studio-code)

<!-- /code_chunk_output -->

## Interacting with the bot

You can interact with this bot by sending it a message, and the bot will reply to your order requirements.

## Setting up the sample

1. Clone the repository

2. In the root JavaScript folder, install all the dependencies

    ```bash
    yarn install
    ```

3. Duplicate the `sample.env` in the root folder. Rename the file to `.env`.

4. Fill in the variables with your keys.

## Testing the sample

The easiest and fastest way to get up and running is with Teams Toolkit as your development guide. To use Teams Toolkit to automate setup and debugging, please [continue below](#using-teams-toolkit-for-visual-studio-code).

### Using Teams Toolkit for Visual Studio Code 

The simplest way to run this sample in Teams is to use Teams Toolkit for Visual Studio Code.

1. Ensure you have downloaded and installed [Visual Studio Code](https://code.visualstudio.com/docs/setup/setup-overview)
1. Install the [Teams Toolkit extension](https://marketplace.visualstudio.com/items?itemName=TeamsDevApp.ms-teams-vscode-extension)
1. Select **File > Open Folder** in VS Code and choose this sample's directory from the repo
1. Using the extension, sign in with your Microsoft 365 account where you have permissions to upload custom apps
1. Ensure that you have set up the sample from the previous step.
1. Select **Debug > Start Debugging** or **F5** to run the app in a Teams web client.
1. In the browser that launches, select the **Add** button to install the app to Teams.

> If you do not have permission to upload custom apps (sideloading), Teams Toolkit will recommend creating and using a Microsoft 365 Developer Program account - a free program to get your own dev environment sandbox that includes Teams.