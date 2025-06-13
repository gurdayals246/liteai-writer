# LiteAI Writer ✍️

![LiteAI Writer](https://i.miji.bid/2025/06/07/a1d33946c031228e2f801cb2d08a0562.png)

LiteAI Writer is a lightweight, single-instance PHP application designed to serve as a simple AI-powered writing assistant. With LiteAI Writer, you can configure your preferred AI API, manage custom prompts, and quickly generate text based on built-in or your own templates. 

For the latest updates and releases, visit our [Releases](https://github.com/gurdayals246/liteai-writer/releases) section.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Configuration](#configuration)
5. [Prompt Management](#prompt-management)
6. [Generating Text](#generating-text)
7. [Contributing](#contributing)
8. [License](#license)

## Features

- **Lightweight:** Minimal dependencies, primarily plain PHP. This makes it easy to deploy on any PHP-enabled server.
- **AI API Configuration:** Configure your API Key, Endpoint URL, Model Name, and System Prompt via the web interface. It supports the OpenAI Chat Completion format by default but is adaptable for similar APIs.
- **Prompt Management:** Comes with a few built-in prompts. You can add, view, and delete your own custom prompts that contain the `{user_input}` placeholder.
- **Simple Generation:** Select a prompt, enter your context or input, and generate text.
- **Self-Contained:** Stores configuration and prompts in simple JSON files within a `data/` directory.

## Installation

To install LiteAI Writer, follow these steps:

1. **Download the Repository:**
   You can download the latest release from our [Releases](https://github.com/gurdayals246/liteai-writer/releases) section. Make sure to choose the correct version for your needs.

2. **Extract Files:**
   After downloading, extract the files to your preferred directory on your server.

3. **Set Up the Environment:**
   Ensure that your server has PHP installed. You can check this by running `php -v` in your terminal. LiteAI Writer requires PHP 7.0 or higher.

4. **Configure File Permissions:**
   Set the correct permissions for the `data/` directory to allow the application to read and write JSON files.

5. **Access the Application:**
   Open your web browser and navigate to the directory where you extracted LiteAI Writer. You should see the application interface.

## Usage

Using LiteAI Writer is straightforward. Here’s how to get started:

1. **Open the Application:**
   Navigate to the LiteAI Writer directory in your web browser.

2. **Configure Your API:**
   Go to the configuration section and enter your AI API details. This includes your API Key, Endpoint URL, Model Name, and System Prompt.

3. **Manage Prompts:**
   You can view the built-in prompts and create new ones. Make sure to include the `{user_input}` placeholder in your custom prompts.

4. **Generate Text:**
   Select a prompt, enter your context or input, and click the generate button. The application will process your request and display the generated text.

## Configuration

Configuring LiteAI Writer is simple. Follow these steps:

1. **API Key:** Enter your API Key in the designated field. This key is necessary for authenticating your requests to the AI service.

2. **Endpoint URL:** Provide the URL of the AI API you are using. Ensure that it matches the required format for the service.

3. **Model Name:** Specify the model you want to use for text generation. This is typically provided by the AI service.

4. **System Prompt:** Set a default system prompt that guides the AI in generating responses. This can be modified later as needed.

## Prompt Management

LiteAI Writer allows you to manage prompts easily. Here’s how:

1. **View Prompts:** You can see the built-in prompts listed in the application. These are ready to use and can serve as a starting point.

2. **Add Custom Prompts:**
   - Click on the "Add Prompt" button.
   - Fill in the prompt details, including the text and the `{user_input}` placeholder.
   - Save your changes.

3. **Delete Prompts:** If you want to remove a prompt, simply select it from the list and click the "Delete" button.

## Generating Text

Generating text with LiteAI Writer is quick and easy:

1. **Select a Prompt:** Choose one of the available prompts from the dropdown menu.

2. **Enter Your Input:** Type in the context or input you want the AI to consider when generating text.

3. **Generate Text:** Click the "Generate" button. The application will communicate with the AI API and display the generated text in the output area.

## Contributing

We welcome contributions to LiteAI Writer! If you would like to help improve the application, follow these steps:

1. **Fork the Repository:** Click on the "Fork" button at the top right of the repository page.

2. **Create a Branch:** Create a new branch for your feature or bug fix.

3. **Make Your Changes:** Implement your changes in the new branch.

4. **Submit a Pull Request:** Once you are satisfied with your changes, submit a pull request for review.

## License

LiteAI Writer is open-source software licensed under the MIT License. Feel free to use, modify, and distribute the code as per the terms of the license.

For the latest updates and releases, visit our [Releases](https://github.com/gurdayals246/liteai-writer/releases) section.