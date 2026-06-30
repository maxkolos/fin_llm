## Overview

This repository contains example Colab notebooks for prototyping on-premise deployments of open-source LLM systems.

## Projects 
* [llm_workspace.ipynb](.llm_workspace.ipynb): Main LLM workspaces that combines several examples (vLLM, multi-agent system). ***This serves as the master notebook for active updates.** Other notebooks are now legacy versions kept for standalone examples.* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/maxkolos/fin_llm/blob/llm_workspace/llm_workspace.ipynb)
* [vLLM_server.ipynb](./vLLM_server.ipynb): Deploying a vLLM server for high-throughput, low-latency LLM serving. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/maxkolos/fin_llm/blob/vllm-v1/vLLM_server.ipynb)
* [multi_agent_system.ipynb](./multi_agent_system.ipynb): Multi-agent LLM system. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/maxkolos/fin_llm/blob/vllm-v1/multi_agent_system.ipynb)

## How to Use

Every notebook in this repository includes a **"Open in Colab"** badge at the top for immediate access. 

All projects are fully tested on the free Google Colab **T4 GPU** (16G VRAM) runtime and contain step-by-step instructions inside the notebook to help you configure the correct environment.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
