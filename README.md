# Autonomous_Vehicle_AI
A simple code write on Python to create an autonomous vehicle looking for the best path to go from point A to point B

To make it run properly, you will need to download somes depencies and programs.

First, you will need Anaconda
# Anaconda Installation
# For Windows:
    
Go on https://www.anaconda.com/download/#windows and click on "Download" button of Python 3.7 version (You can always use the last version of Python)

Once the installer has downloaded, launch it and start following the instructions.

/!\ Warning: You must check the "Add Anaconda to my PATH environment variable" option, as on the screenshot below:

[![Image from Gyazo](https://i.gyazo.com/f1384162ea68b95b6186a1f0d4272a19.png)](https://gyazo.com/f1384162ea68b95b6186a1f0d4272a19)

# For Mac:

Go on https://www.anaconda.com/download/#macos and click on "Download" button of Python 3.7 version (You can always use the last version of Python), then follow the installation instuctions.

# For Linux:

Go on https://www.anaconda.com/download/#linux and follow the same instructions as above.

Then, go on your terminal and type `sh Anaconda3-5.2.0-Linux-x86_64.sh` after navigating to the folder where you downloaded Anaconda, then follow the installation instructions.

# Pytorch Installation

Go on https://pytorch.org/ then choose your os

We have previously downloaded Anaconda, so choose Conda

Python: Choose Python 3.7

Cuda: If you have a CUDA compatible GPU, you can choose the associated CUDA version. If you don't have one or don't know, choose None.
You will then get the commands to type in the terminal just below.

# Where type thoses command ?

# For Windows:

In the Start Menu, search "Anaconda Prompt", launch it as an Administrator, then on this command prompt, you can copy the commands that you received below.

# For Mac and Linux:

Just open a command prompt and paste the command you received below.

It's recommended to create an Anaconda environment beforehand. An environment makes it possible to install modules specifically for the project on which to work, in order to avoid conflicts between different versions.

To create an environement, type thoses commands:
  conda create --name artificialintelligenceaz python=3.7 anaconda
  conda activate artificialintelligence
  conda install pytorch-cpu torchvision-cpu -c pytorch
  spyder

The first line creates the environment in Python 3.7

The second line activates the environment. You will need to activate the environment each time you resume your work in this project.

The third line depends on your OS (Mac, Linux, or Windows), use the PyTorch site to get the exact command.

The fourth line launches Spyder IDE. It is important to launch it from the console to stay in the environment you just created.

# Kivy Installation

Go on Kivy website here -> https://kivy.org/#download

# For Windows

You can type on the command prompt:
  python -m pip install --upgrade pip wheel setuptools
  python -m pip install docutils pygments pypiwin32 kivy.deps.sdl2 kivy.deps.glew
  python -m pip install kivy.deps.gstreamer
  python -m pip instal l kivy.deps.angle
  python -m pip install kivy
  python -m pip install pygame

# For Mac

In the command prompt:
  brew install pkg-config sdl2 sdl2_image sdl2_ttf sdl2_mixer gstreamer
  pip install Cython==0.28.3
  pip install kivy
  pip install pygame

# For Linux

In the command prompt:</br>
  `sudo add-apt-repository ppa:kivy-team/kivy`</br>
  `sudo apt-get install python3-kivy`</br>
  <ol>
  <code>sudo apt-get install -y \</code></br>
      <code>`python-pip \`</code></br>
      <code>`build-essential \`</code></br>
      <code>`git \`</code></br>
      <code>`python3 \`</code></br>
      <code>`python3-dev \`</code></br>
      <code>`ffmpeg \`</code></br>
      <code>`libsdl2-dev \`</code></br>
      <code>`libsdl2-image-dev \`</code></br>
      <code>`libsdl2-mixer-dev \`</code></br>
      <code>`libsdl2-ttf-dev \`</code></br>
      <code>`libportmidi-dev \`</code></br>
      <code>`libswscale-dev \`</code></br>
      <code>`libavformat-dev \`</code></br>
      <code>`libavcodec-dev \`</code></br>
      <code>`zlib1g-dev`</code></br>
   </ol>
  <code>`sudo pip install --upgrade pip virtualenv setuptools`</code></br>
  <code>`pip install Cython==0.28.2`</code></br>
  <code>`pip install kivy`</code></br>
  <code>`pip install pygame`</code></br>

Have fun !
