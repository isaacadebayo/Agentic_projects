# This repository consist of agentic projects conducted on colab

Agentic Projects

* A collection of agentic AI systems built and run on Google Colab, spanning multimodal chatbots, MCP (Model Context Protocol) servers/clients, and experiment tracking with MLflow.

Contents

* Multi-modal/ — Multimodal chatbot with a Gradio interface that accepts image uploads and device camera input alongside audio.
* Semi Agentic using MCP/ — MCP server for a financial chatbot, plus an MCP client that tunnels between the server and host.
* Truly Agentic/ — Fully agentic workflow implementations with memory and reasoning agent.
* MLflow/ — Experiment logging for hyperparameters, including validation loss tracking, token cost tracking etc.
* data/ — Supporting datasets (advertising.csv, credit_risk_dataset.csv).


Highlights

* Multimodal chatbot built with Gradio, supporting image upload, live camera capture, and audio input.
* MCP server implementation powering a financial chatbot.
* MCP client that tunnels communication between the MCP server and host application.
* MLflow logging of hyperparameters with validation loss tracking for model comparison.


Tech Stack

* Python, Gradio, MLflow, Model Context Protocol (MCP), DVC (for data versioning).

Getting Started

Most notebooks are designed to run on Google Colab. Open the relevant notebook from a project folder above and run the cells in order; install any missing dependencies via pip install as prompted.
