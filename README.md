# How to setup Langflow on Docker and Create your first RAG app

## How to install LangFlow on VirtualBox

- Download and install Vagrant (https://www.vagrantup.com/downloads.html) for your operating system.   
- Download and install VirtualBox (https://www.virtualbox.org/wiki/Downloads) for your operating system.
- Create an `.env` file in this directory, and add your OpenAI key into it as follows:
  - `OPENAI_API_KEY=<YOUR_KEY>`
- `vagrant up`; This starts installing the VirtualBox VM with Docker and LangFlow on it.
  - When asked; `Which interface should the network bridge to?` Choose the card that is connected to your internet.
- `make vm`. (Requires Linux or compatible OS) to (start) connect to the VM.

## How to use LangFlow:

Navigate to `http://localhost:7860/` to start using LangFlow

More on how to use LangFlow, via an example, in this How-To: https://rolfstreefkerk.com/posts/how-to-create-your-own-rag-ai-with-langflow

