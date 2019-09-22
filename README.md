# Multirate Signal Processing Notebooks and Tutorials
<p align="center">
    <img src="./images/msp_header.png">
</p>

#### Prof. Dr. -Ing. Gerald Schuller <br> Jupyter Notebooks and Videos: Renato Profeta
[Applied Media Systems Group](https://www.tu-ilmenau.de/en/applied-media-systems-group/) <br>
[Technische Universität Ilmenau](https://www.tu-ilmenau.de/)

# Content
- 01 Introduction: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MSP_Intro.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MSP_Intro.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MSP_Intro.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/rkQN6WVi8ak)

  - What is Multirate Signal Processing? Where is it used?
  - Python Example of a Discrete Time Signal
  - Python Example for a Live Plot of a Microphone Signal
  - Javascript Example for a Live Plot of a Microphone Signal
  - Nyquist Theorem
  - Simple Sample Rate Conversion Example
  - Basic Building Blocks of Multirate Signal Processing
  - Critical Sampling
  - Analysis Filter Bank
  - Synthesis Filter Bank
  
- 02 Multiresolution: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MSP_Multiresolution.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MSP_Multiresolution.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MSP_Multiresolution.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/O4m8fZHgl0c)

  - Uniform Filter Banks
  - Python Example: Live Spectrogram and Aliasing
  - Non-Uniform Frequency Decomposition
  - Frequency Domain and Notation
  - Common Types of Frequency Transforms:
    - Discrete Time Fourier Transform (DTFT)
    - Discrete Fourier Transform (DFT)
    - Discrete Cosine Transform (DCT)
    - z-Transform
    - Short-Time Fourier Transform (STFT)
    
- 03 Frequency Response: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MSP_Multiresolution.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MSP_Multiresolution.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MSP_Multiresolution.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/O4m8fZHgl0c)


    - Frequency Response
    - Example: Obtaining the Frequency Response of a "Black Box" system using Noise
    - Example: Obtaining the Frequency Response of a "Black Box" system using Sweeping Sinusoid
    - Frequency Response: z-Transform and the DTFT
        - Example: Low Pass Filter as Moving Average
            - Discrete Convolution as Matrix Multiplication (Sylvester Matrix)
            - Plotting Poles and Zeros in the Complex Plane
    - dB Revision
        - dB for Voltage and Power
        - Cascading Filters
    
  
 # YouTube Playlist
 [![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://www.youtube.com/playlist?list=PL6QnpHKwdPYiDOUHecdZc1WPTnJ-dd0cT)
 

# Requirements
For the requirements for this project to run, please check the following files at the 'binder' folder:
  - apt.txt
  - requirements.txt
  - postBuild
  
 # Note
 Examples requiring a microphone will not work on remote environments such as Binder and Google Colab. 
