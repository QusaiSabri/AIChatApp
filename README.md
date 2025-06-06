# AI Chat with Custom Data

This project is an AI chat application that demonstrates how to chat with custom data using an AI language model. Please note that this template is currently in an early preview stage. If you have feedback, please take a [brief survey](https://aka.ms/dotnet-chat-templatePreview2-survey).

>[!NOTE]
> Before running this project you need to configure the API keys or endpoints for the providers you have chosen. See below for details specific to your choices.

### Known Issues

#### Errors running Ollama or Docker

A recent incompatibility was found between Ollama and Docker Desktop. This issue results in runtime errors when connecting to Ollama, and the workaround for that can lead to Docker not working for Aspire projects.

This incompatibility can be addressed by upgrading to Docker Desktop 4.41.1. See [ollama/ollama#9509](https://github.com/ollama/ollama/issues/9509#issuecomment-2842461831) for more information and a link to install the version of Docker Desktop with the fix.

# Configure the AI Model Provider
## Setting up a local environment using Ollama
This project is configured to use Ollama, an application that allows you to run AI models locally on your workstation. Note: Ollama is an excellent open source product, but it is not maintained by Microsoft.

### 1. Install Ollama
First, download and install Ollama from their [official website](https://www.ollama.com). Follow the installation instructions specific to your operating system.

### 2. Choose and Install Models
This project uses the `llama3.2` and `all-minilm` language models. To install these models, use the following commands in your terminal once Ollama has been installed:

```sh
ollama pull llama3.2
ollama pull all-minilm
```

### 3. Learn more about Ollama
Once the models are installed, you can start using them in your application. Refer to the [Ollama documentation](https://github.com/ollama/ollama/blob/main/docs/README.md) for detailed instructions on how to explore models locally.

