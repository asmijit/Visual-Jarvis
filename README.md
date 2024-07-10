# Visual-Jarvis

Visual Jarvis is an innovative AI project that allows users to draw in the air using fixed hand gestures, with the drawings then processed by Google's Gemini-1.5-flash LLM to produce various results. The project includes a Streamlit web application for ease of use.

## Features:
* **Air Drawing**: Use hand gestures to draw in the air using your video feed.
* **AI Integration**: Drawings are processed by Google's Gemini-1.5-flash LLM to generate various outputs.
    * If the drawings are math problems, the AI will be prompted to provide the solution for them.
    * If the drawings are not math problems, the AI will try to identify the object in the drawing and provide a fun fact about it.
* **Streamlit Webapp**: Simple and intuitive web application interface for user interaction.

## Requirements:
To run this project, you'll need:
* Python
* OpenCV
* MediaPipe
* Pillow
* Streamlit
* Google Generative AI Library

## Installation:
1) Clone the repository.
   ```
   git clone https://github.com/asmijit/visual-jarvis.git
   cd visual-jarvis
   ```
2) Install the required packages:
   ```
   pip install -r requirements.txt
   ```
3) Run the streamlit app:
   ```
   streamlit run main.py
   ```
## Usage
* **Gesture 1**: ☝️ Index finger is used to draw. Make sure the gesuture is similar to the emoji displayed.
* **Gesture 2**: 👍 Thumb finger is used to clear the canvas/drawings. Make sure the gesuture is similar to the emoji displayed.
* **Gesture 3**: 👌 The middle finger, ring finger and little finger together will prompt the AI to compute the drawing made. Make sure the gesuture is similar to the emoji displayed.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](https://www.mit.edu/~amini/LICENSE.md) file for details.

## Contact
If you have any questions or feedback, feel free to reach out to me at [My E-Mail](asmijit756saha@gmail.com).
