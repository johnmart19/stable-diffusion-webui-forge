# Stable Diffusion WebUI Forge AMD Installation
* Install [Python 3.11.9](https://www.python.org/ftp/python/3.11.9/python-3.11.9-amd64.exe) as usual and [Git for Windows](https://github.com/git-for-windows/git/releases/download/v2.50.1.windows.1/Git-2.50.1-64-bit.exe)
* Install [Microsoft C++ Build Tools, recommended](https://visualstudio.microsoft.com/visual-cpp-build-tools/)

Installation:
1) Clone Repo
* `git clone https://github.com/johnmart19/stable-diffusion-webui-forge SD_webui_forge && cd SD_webui_forge`
2) Make Venv
* `python -m venv venv`
3) Activate it
* `.\venv\Scripts\activate`
4) Update pip (Optional)
* `python.exe -m pip install --upgrade pip`
5) Install appropriate AMD Torch versions (Mandatory)
* `pip install -r extra-requirements.txt`
6) Launch Stable Diffusion WebUI Forge as usual
* `webui-user.bat`

# After initial installation: 
Simply use `webui-user.bat` to launch Stable Diffusion WebUI Forge, you can also make a shortcut for it by holding alt and moving it to your Desktop etc.

# Stable Diffusion WebUI Forge

Stable Diffusion WebUI Forge is a platform on top of [Stable Diffusion WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) (based on [Gradio](https://www.gradio.app/) <a href='https://github.com/gradio-app/gradio'><img src='https://img.shields.io/github/stars/gradio-app/gradio'></a>) to make development easier, optimize resource management, speed up inference, and study experimental features.

The name "Forge" is inspired from "Minecraft Forge". This project is aimed at becoming SD WebUI's Forge.

Forge is currently based on SD-WebUI 1.10.1 at [this commit](https://github.com/AUTOMATIC1111/stable-diffusion-webui/commit/82a973c04367123ae98bd9abdf80d9eda9b910e2). (Because original SD-WebUI is almost static now, Forge will sync with original WebUI every 90 days, or when important fixes.)

News are moved to this link: [Click here to see the News section](https://github.com/lllyasviel/stable-diffusion-webui-forge/blob/main/NEWS.md)

# Original Full Readme:
https://github.com/lllyasviel/stable-diffusion-webui-forge?tab=readme-ov-file#quick-list