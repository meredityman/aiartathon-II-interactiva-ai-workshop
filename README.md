# Building interactive installations and applications with AI and OpenFrameworks

This workshop explores the challenges of using machine learning models for interactive installations, hardware projects and live experiments. We will examine the trade-offs between frameworks, languages and hardware and the specific challenges of connecting ML systems with generative graphics and user input. Finally we will see one example using sockets to communicate between a Tensorflow runtime and OpenFrameworks.

## Requirements

* [openFrameworks](https://openframeworks.cc/)
* [Python 3.6–3.9](https://docs.python-guide.org/starting/installation/)
* [Tensorflow](https://www.tensorflow.org/install)
* [ofxZmgModelRunner](https://github.com/meredityman/ofxZmqModelRunner)
* [ofxZmq](https://github.com/meredityman/ofxZmq)

## Summary

* Why I'm giving this workshop
* Example?
* Neural Networks and Hardware
* Machine learning ecosystems
    * [Tensorflow](https://www.tensorflow.org)
        * [Tensorflow.js](https://www.tensorflow.org/js)
            * [m5.js](https://ml5js.org/)
        * [TFLite](https://www.tensorflow.org/lite)
            * [Coral](https://coral.ai/)
    * [PyTorch](https://pytorch.org/pytorch)
    * [ONNX](https://onnx.ai/)
    * [NVIDIA Jetson](https://www.nvidia.com/en-gb/autonomous-machines/embedded-systems/)
* Where to find models and repositories:
    * [TensorflowHub](https://www.tensorflow.org/hub)
    * [PyTorch Hub](https://pytorch.org/hub/)
    * [HuggingFace](https://huggingface.co/)
    * [ModelZoo](https://modelzoo.co/)
    * [NVIDIA Examples](https://github.com/NVIDIA/DeepLearningExamples)
    * [Facebook Research](https://github.com/facebookresearch)
* Creative Coding Frameworks
    * Python Only
    * Processing
    * openFrameworks
* Types of Data
    * Images
    * Video
    * Text
* Moving data between runtimes
    * Spout/Syphon
    * RTSP/NDI
    * Sockets/Websockets
* Running installations
    * Experience