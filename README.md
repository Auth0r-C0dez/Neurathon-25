# Neurathon-25

## Overview

**Floor PLanning Using Gen-AI** is an AI-driven project developed by Team ThinkML during the Neurathon hackathon at NIT Silchar, where it secured the 2nd prize. The project focuses on generating detailed and accurate floor plans using a combination of fine-tuned models and pre-trained multi-modal systems.

## Features

- **AI-Generated Floor Plans**: Leverages advanced AI models to create precise floor plans based on user inputs.
- **Model Fine-Tuning**: Utilizes fine-tuned versions of Stable Diffusion with ControlNet to enhance output control and accuracy.
- **API Integrations**: Incorporates several pre-trained models via APIs, including:
  - **Janus 1.3B** and **Janus Pro**: Advanced text-to-image generation capabilities.
  - **Optimized_Cloudqi_Text_to_Image_Model** and **Cloudqi_Text_to_Image_Model**: Enhanced image generation performance.
  - **Vertex AI**: Cloud-based AI tools for scalable model inference.
- **Custom Safety Mechanisms**: Implements NSFW filtering and addresses common errors in ControlNet-based pipelines.
- **Performance Optimization**: Configures the pipeline for efficient GPU utilization and memory management, ensuring faster and more reliable image generation.

## Repository Structure

- **Models/**: Contains the fine-tuned models used for floor plan generation.
- **Notebooks/**: COlab notebooks demonstrating the model training and inference processes.
- **Results/**: Sample outputs and results from the model.
- **Testing/**: Scripts and data for testing the model's performance and accuracy.
- **backend/**: Backend code handling API calls and data processing.
- **src/**: Source code for the frontend interface and integration with the backend.

## Getting Started

### Prerequisites

- Python 3.x
- PyTorch
- Transformers
- Diffusers
- PIL
- NumPy

### Installation

Download the repo and run the notebooks with run time as T4 GPU.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

We extend our gratitude to NIT Silchar and their Machine Learning Club for organizing Neurathon and providing a platform for innovation.

---

*For more details, visit our GitHub repository: [Neurathon-25](https://github.com/Auth0r-C0dez/Neurathon-25)*

---

*Developed with ❤️ by Team ThinkML*
