---
title: Using the Flask Framework in Azure Functions 
description: A sample of how to leverage the Flask framework in Azure Functions.
author: vrdmr

ms.topic: tutorial
ms.date: 02/03/2022
ms.author: vrdmr
ms.custom: azure, python, flask, devx-track-python
---

# Using Flask in Azure Functions
  
## Prerequisites 

- An Azure account with an active subscription. [Create an account for free](https://azure.microsoft.com/free/?ref=microsoft.com&utm_source=microsoft.com&utm_medium=docs&utm_campaign=visualstudio).
- [Python versions](https://docs.microsoft.com/en-us/azure/azure-functions/supported-languages#languages-by-runtime-version) that are supported by Azure Functions. For more information, see [How to install Python](https://wiki.python.org/moin/BeginnersGuide/Download).
- The [Azure Functions Core Tools](functions-run-local.md#install-the-azure-functions-core-tools)
- A code editor such as [Visual Studio Code](https://code.visualstudio.com/)

### Prerequisite check

1. In a terminal or command window, run `func --version` to check that the Azure Functions Core Tools are version 2.7.1846 or later.
2. Run `python --version` (Linux/MacOS) or `py --version` (Windows) to check your Python version reports to a supported version.

## Setup
1. Clone or download this sample repository.
2. Open the sample folder in Visual Studio Code or your IDE of choice.

## Running the samples
1. Open a terminal window and cd to the directory that the samples is saved in.
2. Set the environment variables specified in the sample file you wish to run.
3. Follow the usage described in the file.

## Next steps
Check out the [Web frameworks](https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference-python?tabs=asgi%2Cazurecli-linux%2Capplication-level#web-frameworks) documentation to learn more about altering Python functions to leverage WSGI and ASGI-compatible frameworks.
