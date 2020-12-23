# TinyML Study Group

## Syllabus

- Day 1: Introduction to TinyML
  - What is TinyML?
  - Why TinyML is important?
  - TinyML Hardware
    - Microcontrollers
    - Accelerators: Neural Compute Stick, EdgeTPU
    - Mobile
  - TinyML Algorithms
    - Quantization, Knowledge Distillation, Pruning, Early Exits
  - TinyML Software
    - TFLite
    - ONNX
    - OpenVINO
  - Why learn TinyML?
    - Job prospects, research, projects, community
  - General information about this study group
  - Homework: Find an algorithm/hardware/framework not mentioned today

- Day 2: Basics of Running Neural Networks at the Edge
  - Edge Performance Metrics
    - Latency
    - Throughput
    - Size
    - FLOPs
    - Other Metrics
  - Measuring performance metrics
  - Which metrics to optimize your network for?
  - Homework: Read a paper that compares performance of different networks, hardwares, frameworks

- Day 3: Quantization
  - What is Quantization?
  - Different Quantization Specs
    - Weight Quantization
    - Weight and Activation Quantization
  - How does Quantization improve performance at the edge?
  - Quantization using TFLite
  - Running a Quantized network on a hardware
  - Measuring Quantization Performance
    - How much does quantization improve performance?
  - Homework: Quantize a network using OpenVINO and measure its performance

-Day 4: Edge Hardware
  - Introduction to the Intel Neural Compute Stick 2 (NCS)
  - NCS Internals: How does it work?
  - How to use OpenVINO to interface with the NCS
  - Using Multiple NCS devices
  - Homework: Compare the Latency and Throughput of NCS, CPU and GPU
  
- Day 5: Pruning
  - What is Pruning?
  - Different Pruning Methods
  - How does Pruning improve performance at the edge?
  - Pruning using TFLite
  - Running a pruned network on a hardware
  - Measuring Pruning Performance
    - How much does Pruning improve performance?
  - Homework: Prune a network and measure its performance

- Day 6: Research Day - Early Exits in Neural Networks
  - Read and discuss a paper on Early Exits

- Day 7: Edge Hardware: EdgeTPU and EdgeTPU Accelerator
  - Introduction to the EdgeTPU
  - EdgeTPU Internals: How does it work?
  - How to use TFLite to interface with the NCS
  - Homework: Compare the Latency and Throughput of EdgeTPU and the EdgeTPU accelerator
  
- Day 8: Project 1 - Train and Deploy a model at the edge

- Day 9: Security and Privacy in Edge Computing
  - Security of Hardware
  - Security of Data
  - Security of Networks running on Edge Deployed Hardware
    - Cold Boot Attacks
    - Side Channel Attacks
    
- Day 10: Edge Hardware: TinyML on an Arduino
  - Introduction to the Arduino
  - Arduino Internals: How does it work?
  - TinyML on Arduino: [link](https://twitter.com/ElectromakerIO/status/1341782133656969216?s=20)
