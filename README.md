# AI Media Project: Full-Stack AI-Powered Media Generation Web App

![AI Media Project](https://img.shields.io/badge/Release-v1.0.0-blue.svg) ![License](https://img.shields.io/badge/License-MIT-green.svg) ![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen.svg)

[![Download Releases](https://img.shields.io/badge/Download%20Releases-v1.0.0-orange.svg)](https://github.com/HOYOOOOOUNG/ai-media-project/releases)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

The **AI Media Project** is a full-stack web application that leverages artificial intelligence to generate media content. Built using **React** with **Vite** for the frontend and **Flask** with **Diffusers** for the backend, this application enables users to create images and videos from text prompts. 

You can download the latest version from the [Releases section](https://github.com/HOYOOOOOUNG/ai-media-project/releases).

## Features

- **Text-to-Image Generation**: Convert text prompts into stunning images using advanced AI models.
- **Text-to-Video Generation**: Transform text descriptions into engaging video content.
- **User-Friendly Interface**: Designed with a clean and intuitive layout for seamless user experience.
- **Fast Performance**: Utilizes Vite for rapid frontend development and quick load times.
- **Scalable Backend**: Built with Flask, ensuring that the backend can handle multiple requests efficiently.
- **Integration with Hugging Face**: Leverage powerful models from Hugging Face for media generation.
- **OpenAI Support**: Use OpenAI's capabilities for enhanced content creation.

## Technologies Used

- **Frontend**: 
  - [React](https://reactjs.org/)
  - [Vite](https://vitejs.dev/)
  
- **Backend**: 
  - [Flask](https://flask.palletsprojects.com/)
  - [Diffusers](https://huggingface.co/docs/diffusers/index)
  
- **AI Models**:
  - Stable Diffusion
  - OpenAI Models
  
- **Other Tools**:
  - Torch
  - GitHub Pages for deployment

## Installation

To get started with the AI Media Project, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/HOYOOOOOUNG/ai-media-project.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd ai-media-project
   ```

3. **Install Frontend Dependencies**:

   Navigate to the frontend directory and install dependencies:

   ```bash
   cd frontend
   npm install
   ```

4. **Install Backend Dependencies**:

   Navigate to the backend directory and install dependencies:

   ```bash
   cd backend
   pip install -r requirements.txt
   ```

5. **Run the Application**:

   - Start the backend server:

     ```bash
     cd backend
     flask run
     ```

   - Start the frontend development server:

     ```bash
     cd frontend
     npm run dev
     ```

Now, you can access the application at `http://localhost:3000`.

## Usage

Once the application is running, you can start generating media content:

1. **Text-to-Image**:
   - Enter a descriptive text prompt in the designated input field.
   - Click on the "Generate Image" button.
   - View the generated image displayed on the screen.

2. **Text-to-Video**:
   - Enter a narrative or description in the input area.
   - Click on the "Generate Video" button.
   - Watch as the application creates a video based on your text.

## Contributing

We welcome contributions to the AI Media Project. To contribute:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature/YourFeatureName
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m "Add your message here"
   ```

4. Push to the branch:

   ```bash
   git push origin feature/YourFeatureName
   ```

5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or inquiries, feel free to reach out:

- **Email**: your-email@example.com
- **GitHub**: [HOYOOOOOUNG](https://github.com/HOYOOOOOUNG)

You can also check the [Releases section](https://github.com/HOYOOOOOUNG/ai-media-project/releases) for updates and downloads.