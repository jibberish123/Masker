# Masker
 
Masker is a Python Application that detects whether a person is wearing a mask. 

## Description

Masker uses Tensorflow, Keras, and OpenCV frameworks to train DNNs using the MobileNetV2 model developed specifically for mobile applications. Masker is currently being used on a Jetson Nano for remote face mask detection using NVIDIA's Tensorflow-gpu technology.

![Screen Shot 2021-03-05 at 3 42 00 PM](https://user-images.githubusercontent.com/69477092/110171806-43d79600-7dca-11eb-8ba6-eec74a8d0ed4.png)

## Installation

Simply click on the Code Button in the project main directory and download the zip of the project. 

## Usage

In a command line application (e.g. Terminal, Powershell, etc.), navigate to the project directory. 

Type in the following command:

```bash
python maskerDetectVideo.py
```

If you want to run the detection model on a single image:

```bash
python maskerDetect.py --image $NameOfImage
```

Where $NameOfImage is the image name.

## Roadmap

This project is still a work in progress, and face mask detection is only the first step. Outlined below is my plan for this project and its potential applications.

1. Create Python Face Mask Detection Application.
2. Use Python Face Mask Detection in a Jetson Nano for remote video face mask detection.
3. Using the Face Mask Detection algorithm, develop a python application that does facial recognition for people while wearing face masks.
4. Migrate application into iOS using Apple's Core ML for an iOS app that can do facial recognition for people wearing face masks.

## Contributing

Pull requests are welcome. For any major suggestions, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
