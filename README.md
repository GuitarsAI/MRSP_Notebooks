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
    
- 03 Frequency Response: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MSP_FrequencyResponse.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MSP_FrequencyResponse.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MSP_FrequencyResponse.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/7XWrH9IV-EA)

    - Frequency Response
    - Example: Obtaining the Frequency Response of a "Black Box" system using Noise
    - Example: Obtaining the Frequency Response of a "Black Box" system using Sweeping Sinusoid
    - Frequency Response: z-Transform and the DTFT
        - Example: Low Pass Filter as Moving Average
            - Discrete Convolution as Matrix Multiplication (Sylvester Matrix)
            - Plotting Poles and Zeros in the Complex Plane
            - Complex Conjugate Symmetry
    - dB Revision
        - dB for Voltage and Power
        - Cascading Filters
        
 - 04 Filters: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MSP_Filters.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MSP_Filters.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MSP_Filters.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/BhyxN_INkNw)

    - Ideal Low Pass Filter
        - Frequency Response
        - Impulse Response
    - Delay (Shift Operator)
  
- 05 Filters and Windows: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_FiltersAndWindows.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MRSP_FiltersAndWindows.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_FiltersAndWindows.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/CmwHW7PBNf8)

    - Ideal Low Pass Filter
        - Quadratic Error
        - Parseval Theorem
    - Rectangular Window
    - Approximation of an Ideal Low Pass Filter using a Rectangular Window and Delay
    
 - 06a Windows: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_Windows.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MRSP_Windows.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_Windows.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/Dwkdlb5xYkM)

    - Rectangular Window
    - Raised Cosine Window
    - Kaiser Window
    - Vorbis Specification
  
 - 06b Filter Design with the Window Method: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_Filter_Design_Windows.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MRSP_Filter_Design_Windows.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_Filter_Design_Windows.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/hxWyLvSwh7k)

    - Design Method
    - Design using Modulation
  
 - 07 Sampling: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_Sampling.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MRSP_Sampling.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_Sampling.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/PEaW9xG5cJM)
 
    - Sampling a Discrete Time Signal
    - Real-Time Python Example
    - Downsampling
    - Upsampling

- 08 Effects in the z-Domain: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_zDomain.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MRSP_zDomain.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_zDomain.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/Ocb7r3ww5Tc)
 
    - Modulation
    - Time-Reversal
        
 - 09 Non-Ideal Filters: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_nonIdeal.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MRSP_nonIdeal.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_nonIdeal.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/wdFrdt3m0BU)
 
    - Filter Banks
    - Analysis Filter Bank
    - Block Transforms
    - Python Example
    - Fast Implementation
 
 - 10 Transforms as Filter Banks: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_DFT_Equivalent.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MRSP_DFT_Equivalent.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_DFT_Equivalent.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/4-5xq47I7gs)
 
    - Equivalent Analysis Filters of a DFT
    - Equivalent Synthesis Filter Bank
    - Python Example
    - Example Transform as Filter Bank
 
 - 11 DCT and Polyphase Representation: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_DCT_Polyphase.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MRSP_DCT_Polyphase.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_DCT_Polyphase.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/sPXt7PBBwnw)
 
    - Notation
    - Discrete Cosine Transfomr (DCT)
    - Introduction to Polyphase Representation
    - Analysis Filter Bank
    - Python Polyphase Example
        - Faster Implementation
    - Application Example
    - Auxiliary Functions
    
 - 12 Polyphase Representation: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_Polyphase.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MRSP_Polyphase.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_Polyphase.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/oGT5GcOIvFo)
 
    - Polyphase Representation
    - Synthesis filter Bank
    - Perfect Reconstruction
    
 - 13 MDCT: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_mdct.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MRSP_mdct.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_mdct.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/RhDB5yKdU5s)
 
    - Modified Discrete Cosine Transform (MDCT)
    - MDCT Filters: Python Example
    - Symmetries of a Cosine Modulation Function
    - Sparse Matrices and the MDCT
        -  Python Computation
    - The Delay Matrix
        - Python Sympy Example
        - Faster Numerical Python Implementation
    - The Python Folding Matrix Function
    - The Factorization
    - Perfect Reconstruction
        - Example in Python
    - MDCT Python Implementation, Analysis
    - MDCT Synthesis Filter Bank
    
- 14 LDFB: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_LDFB.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MRSP_LDFB.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_LDFB.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/MFbMI5yoaOk)
 
    - Low Delay Filter Banks (LDFB)
    - Zero-Delay Matrix
    - Maximum-Delay Matrix
    - Python Fast Implementation Example
    
- 15 Optimization of Filter Banks: [![NBViewer](https://badgen.net/badge/Launch/on%20NBViewer/blue?icon=terminal)](https://nbviewer.jupyter.org/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_Optimization_FilterBanks.ipynb)[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GuitarsAI/MRSP_Notebooks/master?filepath=MRSP_Optimization_FilterBanks.ipynb)[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/black?icon=terminal)](https://colab.research.google.com/github/GuitarsAI/MRSP_Notebooks/blob/master/MRSP_Optimization_FilterBanks.ipynb)[![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://youtu.be/5TdrxOhlROk)
 
    - Goal
    - Approach
    - Newton's Method
    - Gradient Descent
    - Python Example for the Optimization of an MDCT Filter Bank

    
 # YouTube Playlist
 [![Youtube](https://badgen.net/badge/Launch/on%20YouTube/red?icon=terminal)](https://www.youtube.com/playlist?list=PL6QnpHKwdPYiDOUHecdZc1WPTnJ-dd0cT)
 

# Requirements
Please check the following files at the 'binder' folder:
  - environment.yml
  - postBuild
  
 # Note
 Examples requiring a microphone will not work on remote environments such as Binder and Google Colab. 
