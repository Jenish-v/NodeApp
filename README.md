# Text-to-Video Generator

This project is a simple tool to generate videos from text using Python. It takes a script as input, converts it into audio using Google Text-to-Speech (gTTS), and then combines the audio with the text to create a video.

## Installation

1. Clone this repository to your local machine.

git clone https://github.com/your-username/text-to-video.git

2. Install ImageMagick (required by MoviePy):

apt-get install imagemagick

Change the ImageMagick binary path in text_to_video.py to the appropriate location on your system.

3. Run the text_to_video.py script.

python text_to_video.py

Enter the script when prompted.
The script will generate a video based on the provided script and save it as output_video.mp4 in the current directory.


## Dependencies

gTTS: for text-to-speech conversion
MoviePy: for video editing and manipulation
ImageMagick: required by MoviePy for image processing (installation instructions provided above)


Feel free to customize it further based on your project's specific details and requirements.
