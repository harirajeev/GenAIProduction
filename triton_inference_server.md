- [Triton Inference Server API Endpoints Deep Dive](https://medium.com/@manikandan_t/triton-inference-server-api-endpoints-deep-dive-05b3061b156e)

- Triton Inference Server is an open-source, high-performance inference serving software that facilitates the deployment of machine learning models in production environments.
  Developed by NVIDIA, Triton provides a flexible and scalable solution for serving deep learning models in real-time and batch scenarios.
- Triton model-repository structure
![image](https://github.com/user-attachments/assets/42981a92-466d-405b-be10-077ce49f9eff)

  -  1/: This subdirectory suggests different model versions might be stored here, with "1" representing the first version.
  -  config.pbtxt: This file stores the model configuration in a text-based format, specifying details like input/output tensors, metadata, and backend used.
  -  model.py: This Python file contains the model definition or code for loading and preprocessing the model.
 
    The config.pbtxt file is written in Protocol Buffer Text Format (PBTxt), a human-readable representation of Protocol Buffer messages.
    This file provides essential information to Triton Inference Server about how to serve the model, including details such as input and output tensor names, data types,
    batching parameters, and other runtime settings. It’s typically structured like this:

