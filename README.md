# Assistive Speech Technology System

## Overview

The Assistive Speech Technology System is designed to enhance communication by analyzing and processing various speech and audio inputs. This system integrates multiple modules that specialize in different aspects of speech and audio analysis, catering to a range of applications from assisting individuals with speech impairments to detecting emotional tones and verifying audio authenticity.

## Modules

### 1. Dysarthric ASR (Automatic Speech Recognition)
    This module is designed to recognize and transcribe speech from individuals with dysarthria. 
    It uses advanced machine learning models to accurately interpret impaired speech patterns and convert them into text.

### 2. Emotion Classification
    The Emotion Classification module analyzes the speech input to detect and classify the speaker's emotional state. 
    It helps in understanding the sentiment behind the spoken words, which can be crucial for various assistive and therapeutic applications.

### 3. Deep Fake Audio Detection
    This module is focused on identifying synthetic or manipulated audio, commonly known as deep fake audio. 
    It uses state-of-the-art algorithms to detect signs of audio tampering, ensuring the authenticity of the speech.

### 4. Infant Cry Detection
    The Infant Cry Detection module is designed to analyze audio signals to detect and classify infant cries. 
    It can distinguish between different types of cries (e.g., hunger, discomfort) and provides insights for caregivers or automated monitoring systems.

### 5. Voice Liveness Detection
    This module ensures that the speech input is coming from a live person rather than a recording. 
    It uses various signal processing techniques to detect signs of voice spoofing, adding a layer of security to voice-based systems.

## Technologies Used
- **Python**: The core programming language used for implementing the modules.
- **TensorFlow/PyTorch**: For building and training machine learning models.
- **Flask**: To create the API for the backend.
- **HTML/CSS/Bootstrap**: For the front-end interface.
- **JavaScript (React)**: To enhance user interactions and manage state in the front-end.

## How to Clone the Repository

To clone this repository, follow the steps below:

1. **Open your terminal** and navigate to the directory where you want to clone the project.
2. **Run the following command**:
   ```bash
   git clone https://github.com/your-username/assistive-speech-technology.git
