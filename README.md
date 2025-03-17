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
