# Setting up OpenAI API Key

## Step 1: Create an OpenAI API Key
Follow the steps provided [here](https://gptforwork.com/help/create-openai-api-key) to create your OpenAI API key.

## Step 2: Copy the OpenAI API Key
Once you have your API key, copy it for the next steps.

## Step 3: Set Up Environment Variable for OpenAI API Key

### Windows Set-up

To set your `OPENAI_API_KEY` environment variable, follow these steps:

1. Open the **cmd prompt**.
2. Run the following command, replacing `<yourkey>` with your actual API key:

    ```bash
    setx OPENAI_API_KEY "<yourkey>"
    ```

### Linux / macOS Set-up

You have two options to set the `OPENAI_API_KEY` environment variable. Here's Option 1 using zsh:

#### Option 1: Set your `OPENAI_API_KEY` using zsh

1. Run the following command in your terminal, replacing `yourkey` with your actual API key:

    ```bash
    echo "export OPENAI_API_KEY='yourkey'" >> ~/.zshrc
    ```

2. Update the shell with the new variable:

    ```bash
    source ~/.zshrc
    ```

3. Confirm that the environment variable is set by running:

    ```bash
    echo $OPENAI_API_KEY
    ```

The value of your API key should be the resulting output.


# Install AutoGen packages
[Readme instructions](README.md)

# Working with AutoGen Studio
1. [AutoGen Studio - Getting Started](https://microsoft.github.io/autogen/0.2/docs/autogen-studio/getting-started)
2. [Using AutoGen Studio](https://microsoft.github.io/autogen/0.2/docs/autogen-studio/usage)