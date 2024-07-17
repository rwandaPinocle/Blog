---
title: "Interesting Software and Software Tools"
date: 2024-06-11T11:26:08-07:00
draft: false
---

# LLMs

[Nemotron 4, 340B](https://huggingface.co/collections/nvidia/nemotron-4-340b-666b7ebaf1b3867caf2f1911):
Nvidia's LLM that is roughly the same size as GPT-4, with public weights.

[Dragonfly](https://www.together.ai/blog/dragonfly-v1):
A vision and text LLM derived from Llama3, outperforms LLaVA and QWEN

[Qwen2](https://qwenlm.github.io/blog/qwen2/):
Open LLM 70B params, beats Lllama 3

# Deep learning

[MAX Engine](https://docs.modular.com/max/engine):
Modular's runtime for serving models. Support Pytorch, Tensorflow, and ONNX models on CPU.

[Stable Diffusion from Scratch](https://github.com/Animadversio/DiffusionFromScratch): A Harvard tutorial on Stable Diffusion

[Wonnx](https://github.com/webonnx/wonnx):
Onnx runtime for WebGPU

[Stable-Diffusion.mojo](https://github.com/lrmantovani10/Stable-Diffusion.mojo):
An implementation of the forward pass of Tiny Stable Diffusion in Mojo.
Includes an implementation of CLIP in Mojo as well.

[OpenVINO](https://github.com/openvinotoolkit/openvino):
Intel's toolkit for deploying DL models

[ONNX-MLIR](https://github.com/onnx/onnx-mlir):
A tool for compiling ONNX models down to code

[Pytorch MLIR](https://github.com/llvm/torch-mlir)

[TVM](https://github.com/apache/tvm/):
A neural network compiler

[MLP-Mixer](https://arxiv.org/pdf/2105.01601v4):
An MLP based architecture that matches transformer performance

[CLIP.cpp](https://github.com/monatis/clip.cpp/tree/main):
A C++ implementation of CLIP

# GPU/Multithreaded Computing 

[Scale](https://docs.scale-lang.com/):
A toolkit that compiles CUDA code to AMD GPUs.

[NVIDIA Warp](https://github.com/NVIDIA/warp): 
NVIDIA's Python framework for compiling Python code into compute kernels. 

[Triton](https://github.com/triton-lang/triton):
OpenAI's Python framework for compiling Python code into compute kernels.
Uses an MLIR backend.
Supports CUDA.

[Taichi](https://github.com/taichi-dev/taichi):
Python framework for compiling Python code into compute kernels.
Has modules for physics sims, NERFs, differentiable programming.
Supports CUDA, Vulkan, AMD.

[Pythran](https://pythran.readthedocs.io/en/latest/):
A Python tool that compiles Python code into multithreaded and SIMD modules.
