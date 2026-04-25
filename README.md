# AI-for-Interior-Design
Developed an AI-based interior design generator using Stable Diffusion to create room designs from text prompts. Implemented using Python, PyTorch, and Gradio with an interactive user interface.
 AI Interior Design Generator (Gradio + Stable Diffusion)

 Project Description

The AI Interior Design Generator is a deep learning-based application that generates realistic interior design images based on user preferences. It leverages the Stable Diffusion model to create high-quality room designs by taking inputs such as room type, design style, color theme, and lighting conditions. The application is built using Gradio, providing an interactive and user-friendly interface.

Objectives

- To design an AI system that generates interior design visuals
- To use text-to-image generation for creative room layouts
- To build an interactive UI using Gradio
- To provide customized design outputs based on user inputs

Features

- Generate interior designs using AI prompts
- Customize room type, style, color, and lighting
- Uses Stable Diffusion for high-quality image generation
- Simple and interactive interface using Gradio
- Fast and automated design output

Technologies Used

- Python
- PyTorch
- Diffusers (Stable Diffusion)
- Gradio
- Deep Learning

Model Used

- Stable Diffusion v1.5 ("runwayml/stable-diffusion-v1-5")
- Text-to-image generation using prompt engineering

 Project Structure

AI-Interior-Design/
│
├── app.py              # Main application file
├── requirements.txt    # Dependencies
├── README.md
└── outputs/            # Generated images (optional)

 How to Run the Project

1. Clone the repository:
   
   git clone https://github.com/your-username/ai-interior-design.git

2. Navigate to the folder:
   
   cd ai-interior-design

3. Install dependencies:
   
   pip install -r requirements.txt

4. Run the application:
   
   python app.py
5. Open the link shown in terminal (usually):
   
   http://127.0.0.1:7860

 Sample Prompt

Example of generated prompt:

Living Room interior design, Modern style, White color theme, Warm lighting, high quality, realistic

 Output

The system generates realistic interior design images based on selected inputs.
Users can visualize different styles instantly.

(Add screenshots of your generated images here)

Limitations

- Runs on CPU (slower performance)
- Requires high memory for model loading
- Image generation may take time

 Future Enhancements

- GPU acceleration for faster generation
- More room types and design styles
- Upload custom room images for redesign
- Deploy as a web application (Hugging Face / Cloud)

 Author

D Vyshnavi
B.Tech IT Student

 License

This project is developed for educational and academic purposes.
