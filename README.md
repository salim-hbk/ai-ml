# ai-ml
Contains training material and projects related to Tensor flow based Ai ML models

Device based Model:
https://github.com/lmoroney/dlaicourse


Why we need tensorflow Lite:

1) Lightweight
2) Low-latency
3) Privacy
4)Improved powed consumption

Tensorflow Light has 2 components
1. Converter: Transforms tensorflow model into a form efficient for reading by the interpreter. Optimized to improve binary size model performance and/or reduce model.

2. Interpreter: Device platform support, Platform APIs for accelerated support.


TensorFlow Model->Converted->Android

Model Topology:
1) Quantization: reduces the precision of the number
2) Weight pruning: Reduces overall number of weights
3) Model topology transform: optimized model for mobile or resource constrained devices.
