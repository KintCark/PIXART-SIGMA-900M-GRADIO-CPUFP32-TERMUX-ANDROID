# PIXART-SIGMA-900M-GRADIO-CPUFP32-TERMUX-ANDROID
Chat gpt is a big help im making gradio mods now for android this space I downloaded from huggingface and nodded it for lower memory phones ,now that I found the secret sauce ima try animatediff gradio!!!



Just extract the pixart space and copy the folder to the termux ubuntu root folder then just cd into the pixart spaces folder and run

python3 app.py

It will download everything for you

Makesure you install UBUNTU FIRST:

1>

pkg update -y && pkg install wget curl proot tar -y && wget https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Installer/Ubuntu22/ubuntu22.sh -O ubuntu22.sh && chmod +x ubuntu22.sh && bash ubuntu22.sh

2>

apt update && apt upgrade -y && apt-get install curl git gcc make build-essential python3 python3-dev python3-distutils python3-pip python3-venv python-is-python3 -y &&
pip install torch typing_extensions numpy Pillow requests pytorch_lightning absl-py && pip install torch safetensors gradio spaces


make sure you

 pip install accelerate --break-system-packages


 