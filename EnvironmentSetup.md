# Setting up OpenAI API Key

## Step 1: Create an OpenAI API Key
Follow the steps provided [here](https://gptforwork.com/help/create-openai-api-key) to create your OpenAI API key.

## Step 2: Copy the OpenAI API Key
Once you have your API key, copy it for the next steps.

## Step 3: Set Up Environment Variable for OpenAI API Key in .env file

1. Create a `.env` file in the root directory of the project. The file should have exactly the same name `.env` without any extension. And being put under the same folder as the `requirements.txt` file.
2. Add the following line to the `.env` file, make sure to replace `<YOUR_OPENAI_API_KEY>` with the API key you copied in Step 2.
```bash
OPENAI_API_KEY=<YOUR_OPENAI_API_KEY>
```

# Install Dependencies
[Readme instructions](README.md)

# Working with AutoGen Studio
1. [AutoGen Studio - Getting Started](https://microsoft.github.io/autogen/0.2/docs/autogen-studio/getting-started)
2. [Using AutoGen Studio](https://microsoft.github.io/autogen/0.2/docs/autogen-studio/usage)


### Note: Use separate python environments for AutoGen development and AutoGen-Studio setup. AutoGen-Studio better works with python 3.11 and above.