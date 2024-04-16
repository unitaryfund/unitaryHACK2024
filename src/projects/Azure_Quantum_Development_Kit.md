---
title: Azure Quantum Development Kit
emoji: 
project_url: https://github.com/microsoft/qsharp
metaDescription: Azure Quantum Development Kit, including Q# programming language, Azure Quantum Resource Estimator, and Quantum Katas.
date: 2024-04-16
summary: Is it possible to distinguish the given random numbers are produced from a specific quantum computer? More generally, this problem is related to the topic of cross-platform comparison of quantum circuits.
tags:
  - Qsharp
  - Quantum Resource Estimation
  - Tutorials
bounties:
  - TBD
---

Welcome to the Azure Quantum Development Kit!

This repository contains tooling for the Q# language, specifically:

[compiler](https://github.com/microsoft/qsharp/blob/main/compiler/qsc): core compiler logic and command-line tooling
[fuzz](https://github.com/microsoft/qsharp/blob/main/fuzz): fuzz testing infrastructure
[jupyterlab](https://github.com/microsoft/qsharp/blob/main/jupyterlab): JupyterLab extension
[language_service](https://github.com/microsoft/qsharp/blob/main/language_service): Q# language service and editor features
[library](https://github.com/microsoft/qsharp/blob/main/library): Q# standard library
[npm](https://github.com/microsoft/qsharp/blob/main/npm): Q# npm package
[pip](https://github.com/microsoft/qsharp/blob/main/pip): Q# Python pip package
[playground](https://github.com/microsoft/qsharp/blob/main/playground): simple website for interacting with Q#
[resource_estimator](https://github.com/microsoft/qsharp/blob/main/resource_estimator): Implementation for the Azure Quantum Resource Estimator
[vscode](https://github.com/microsoft/qsharp/blob/main/vscode): Visual Studio Code extension
[wasm](https://github.com/microsoft/qsharp/blob/main/wasm): The bindings and logic for the WebAssembly module
[widgets](https://github.com/microsoft/qsharp/blob/main/widgets): The Q# Jupyter widgets Python package
There are also the tutorials and samples in the `./katas` and `./samples` directories, respectively.

Code from this repository powers the Q# development experience on https://quantum.microsoft.com.
