# Sol - The Sentient Watcher

Sol is a comprehensive AI surveillance system designed to monitor, analyze, and respond to various environmental and scientific anomalies. It utilizes advanced machine learning models and real-time data processing to ensure safety and awareness in its operational environment.

## Features
- **Consciousness Module**: Manages Sol's alertness and confidence based on environmental inputs.
- **Policy Module**: Uses Q-learning for decision-making and action execution.
- **Surveillance Capabilities**: Integrates YOLO for object detection and DeepSort for object tracking.
- **Scientific Analysis**: Employs custom-trained models for physics, chemistry, environmental, and space anomaly detection.
- **Speech and Audio Processing**: Uses pyttsx3 for text-to-speech and YAMNet for audio anomaly detection.
- **Event Logging and Reflection**: Logs events and generates thoughtful responses using GPT-2.

## Installation
To get started with Sol, follow these steps:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/SuperCaleb/Sol.git
    cd Sol
    ```

2. **Install Dependencies**
    Ensure you have Python 3.7 or higher installed. Then, install required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. **Download Pre-trained Models**
    Download the necessary pre-trained models and place them in the appropriate directories:
    ```bash
    # Example for YOLO
    wget -P models/ https://path/to/yolov8l.pt
    ```

4. **Configure API Keys**
    Some functionalities, like weather data fetching, require API keys. Update the code with your API keys where necessary.

## Usage
To start Sol's surveillance system, run the following command:

```bash
python sol.py
```

### Command Line Interface
While Sol is running, you can input commands directly into the terminal to interact with Sol:
- **status**: Get the current status of Sol's alertness and confidence.
- **explain_last_detection**: Get details about the last detected event.
- **quit**: Terminate the surveillance system.

## How Sol Works
1. **Initialization**: Sol initiates various modules and sets up the surveillance system.
2. **Surveillance Loop**: Continuously captures video frames, detects and tracks objects, and processes audio input.
3. **Anomaly Detection**: Utilizes scientific models to detect anomalies in physics, chemistry, environment, and space.
4. **Decision Making**: Based on detected anomalies and its internal state, Sol decides on actions to take, such as increasing sensitivity or sending alerts.
5. **Event Logging and Reflection**: Logs events and generates thoughtful reflections on significant occurrences.

## Contributing
We welcome contributions to enhance Sol's capabilities. Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
For any questions or issues, please open an issue on GitHub or contact me at cgameing04@gmail.com

---

By leveraging state-of-the-art AI technologies, Sol aims to provide a safer and more aware environment through intelligent surveillance and scientific analysis.












































---

# Sol/HWS Hybrid Sentient AI

Sol/HWS is an advanced sentient AI system designed to observe, analyze, and interact with its environment. It integrates multiple machine learning and computer vision techniques to process video input, recognize actions, detect anomalies, and generate narratives with a unique personality.

## Features

- **Action Recognition**: Utilizes a Spatio-Temporal Graph Convolutional Network (STGCN) to recognize human actions based on pose and appearance features.
- **Cross-Modal Attention**: Integrates visual and audio data for enhanced perception and decision-making.
- **Depth Estimation**: Processes video frames to generate depth maps and refine them for accurate environmental understanding.
- **Object Detection and Tracking**: Employs YOLO for object detection and DeepSort for tracking.
- **Narrative Generation**: Uses NLP models to generate descriptive narratives of observed scenarios.
- **Anomaly Detection**: Detects unusual behavior and objects in the environment.
- **Speech Synthesis**: Converts text to speech to provide audio feedback and interaction.
- **Drone Control**: Issues commands to a drone for further investigation of detected anomalies.
- **Encrypted Logging**: Logs events securely using encryption.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/SuperCaleb/Sol.git
   cd Sol
   ```

2. **Install Dependencies**:
   Ensure you have Python 3.8 or higher installed. Then, install the required packages:
   ```bash
   pip install torch torchvision torchaudio
   pip install ultralytics
   pip install deep_sort_realtime
   pip install pyttsx3
   pip install transformers
   pip install mediapipe
   pip install opencv-python
   pip install tensorflow tensorflow-hub
   pip install scikit-learn
   pip install sounddevice
   pip install requests
   pip install cryptography
   ```

3. **Download Additional Models**:
   - **YOLOv8 Model**: Download the YOLOv8 model and place it in the appropriate directory.
   - **MiDaS Model**: Ensure the MiDaS model is available via `torch.hub`.
   - **NLP Models**: The script will automatically download the required NLP models from Hugging Face.

## Usage

1. **Run the Main Script**:
   ```bash
   python3 sol.py --source <video_source>
   ```
   Replace `<video_source>` with the index of your webcam (e.g., `0`) or the path to a video file.

2. **Interact with Sol**:
   Sol will start processing the video input, recognizing actions, detecting anomalies, and generating narratives. You will see the output in a video window and hear audio feedback.

3. **Control Parameters**:
   - You can adjust various parameters such as detection thresholds, interaction counters, and logging configurations within the `HWS` class in the script.

## Example

To run Sol with a webcam as the video source:
```bash
python3 sol.py --source 0
```

To run Sol with a video file as the source:
```bash
python3 sol.py --source path/to/video.mp4
```

## Contributing

We welcome contributions! Please fork the repository and create a pull request with your changes. Ensure that your code is well-documented and tested.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [PyTorch](https://pytorch.org/)
- [Ultralytics YOLO](https://github.com/ultralytics/yolov5)
- [DeepSort](https://github.com/nwojke/deep_sort)
- [Transformers](https://github.com/huggingface/transformers)
- [MediaPipe](https://mediapipe.dev/)
- [OpenCV](https://opencv.org/)
- [TensorFlow](https://www.tensorflow.org/)
- [Scikit-Learn](https://scikit-learn.org/)
- [SoundDevice](https://python-sounddevice.readthedocs.io/)
- [Cryptography](https://cryptography.io/)

---

Feel free to modify the README as needed to better suit your project.
