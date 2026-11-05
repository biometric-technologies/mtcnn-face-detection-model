![](.github/readme/banner.svg)

# MTCNN face detection model

This repository is reserved for the MTCNN face detection model of the Iriscan face pipeline. It is empty for now: no code, weights or releases have been published here yet.

MTCNN (Multi-task Cascaded Convolutional Networks) is a face detector made of three small neural networks that run one after another, each refining the face boxes and landmark points of the previous one, so that a face can be found and cropped before it is passed to a recognition model.

In the Iriscan stack the cropped face goes to a FaceNet-type model that the [Biometric SDK](https://github.com/biometric-technologies/biometric-sdk) loads as a TensorFlow Lite file you supply through `FaceNetModelConfiguration`. See [facenet-recognition-model](https://github.com/biometric-technologies/facenet-recognition-model) for the embedding model and [biometric-models-onnx-converters](https://github.com/biometric-technologies/biometric-models-onnx-converters) for converting the face models to ONNX.

License: not yet specified. Contact: info@iriscan.com, https://www.iriscan.com
